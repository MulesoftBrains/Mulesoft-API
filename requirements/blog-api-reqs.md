# Requirements for our blog API

## MulesoftBrains Blog

### Resources:
These are the nouns on which the basic CRUD operations can be performed.

CRUD stands for:

    C = CREATE
    R = READ
    U = UPDATE
    D = DELETE

List of resources :

- Blog
- Articles
- Writers
- Categories
- Comments

Data Types :

- Articles
    - id
    - title
    - content
    - writerId
    - categoryId
    - comments
- Writer
    - id
    - name
    - bio
    - articles
- category
    - id
    - name
    - articles
- comment
    - id
    - content
    - articleId
    - author
- error
    - code
    - description