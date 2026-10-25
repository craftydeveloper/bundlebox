# Data model

## Proposed fields

Assets need a name, version, location, optional digest, tags, and handoff notes.

The examples are synthetic contract examples and are not loaded automatically. Before changing persistence, inspect the current serialized state and write a migration that preserves user data. Validate imported records and avoid storing credentials.