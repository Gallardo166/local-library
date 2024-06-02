# local-library

### Concepts Learnt

1. MVC (Model-View-Controller)
- Arranging files using the MVC pattern to allow CRUD operations
- Using controllers to manage how incoming requests are handled by routes, with the help of `express-async-handler` to wrap async functions in try-catch statements

2. Interacting with database
- Connecting to database with development/production URL
- Reading and making changes to documents in MongoDB
- Visualising data using UML association diagrams

3. Data Validation and Sanitization
- Use `express-validator`'s `escape()` function to change characters to HTML entities
- Use Pug's buffered (`#{...}`) and unescaped buffered (`!{...}`) code
- Use `express-validator`'s validation chains to validate data and show error messages

4. View Templates
- Use Pug to generate views