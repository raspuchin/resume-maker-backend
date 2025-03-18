# resume-maker-backend

This project is the backend for resume maker.

It should have the following contents/values:

- A database to connect to, it should have the following tables:
    - user -> to map users, contains general user info: name, email, address, phone, email, linked in, portfolios (?)
    - education -> one field per education mapped with user id
    - experience/employment history -> one row per place of work w/ expirience id, tags
        - expierience bullet -> one row per bullet, mapped with expieience id, tags
    - skills, w/ tags + user id
    - references, w/ tags + user id
    - projects, w/ tags + user id
- a user should be able to log in, pass a bunch of tags and have a resume generated. tags passed first have higher preference.