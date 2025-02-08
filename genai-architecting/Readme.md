## Functional Requirements

- The users should be able to log into a device of their choice and continue learning from where they left. This requires authentication and storage of the student's learning progress.
- Clever caching mechanisms should be employed to reduce query costs.
- Guardrails to provide from harmful and sensitive content in and out of GenAI model.
- The AI should be multi-model catering to users of different learning preferences.

## Data Strategy

- There is a concerned of copyrighted materials, so we must purchase and supply materials and store them for access in our database.

## Considerations

- We're considering using IBM Granite because its a truley open-source model with training data that is traceable so we can avoid any copyright issues and we are able to know what is going on in the model. 
- We'll also provide an option for the students to bring their API keys for their desired model.