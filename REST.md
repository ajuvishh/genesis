Techinically,
Post is an abstract layer
whereas PUT is more specific

POST creates new resources
PUT is idempotent and updates/replaces a resource if it already exists

What I have seen?
On update, both methods fetch the entity and replace the entity's instance variable with the members of request body.
Even though I can find the difference in theory, I can not see the difference in real scenarios.
