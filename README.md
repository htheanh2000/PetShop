constants: Static data that doesn’t change.
api: API endpoints, static info that might change in different
environments.
models: Shared models/interfaces.
selectors: Business logic code, models/interfaces generated for views.
stores:
- models: API related models.
- actions: Events to trigger application changes.
- effects: Handles APIs and sanitizes response data.
- reducers: Adds/removes/edits data from the global store.
utilities: Helper code, abstract code to prevent duplication.
views: All view components.