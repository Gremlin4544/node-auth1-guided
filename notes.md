# Auth Notes


## Objectives

    - implement secure password storage.
    - implment authentication using sessions and cookies.
    - use sessions to protect resources.
    - use a database to store sessions.+

### Implement secure password storage
    Never store passwords in plain text, hash them instead.

    password--> hashing function --> hash

    Hash passwords before they are stored in the database    

> When using sessions, the information is saved in the server.
> The cookie only needs the sessions id.    