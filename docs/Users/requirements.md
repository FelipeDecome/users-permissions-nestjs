# Users Requirements

## Functional Requirements
<details open>
<summary>Users</summary>

 - [ ] Users should be able to create users
 - [ ] Users should be able to update users
 - [ ] Users should have an name, email, password and a role
 - [ ] Users could have permissions besides their role's permissions
 - [ ] Created users must receive an email with instructions to create their password
 - [ ] Users should be able to sign in
 - [ ] Users should be able to request a forgot password email
</details>

<details open>
<summary>Roles</summary>

  - [ ] Users should be able to create roles
  - [ ] Users should be able to delete roles
</details>

<details open>
<summary>Permissions</summary>

  - [ ] Users should be able to add permissions to users/roles
  - [ ] Users should be able to remove permissions from users/roles
</details>

## Non-functional Requirements
 - [ ] NestJS
 - [ ] Prisma ORM
 - [ ] Postgres
 - [ ] BCrypt
 - [ ] JWT token for auth

## Business Rules
 - [ ] Must be logged to create users
 - [ ] Must be logged to update users
##
 - [ ] Must have permissions to create users
 - [ ] Must have permissions to create roles
 - [ ] Must have permissions to delete roles
 - [ ] Must have permissions to add permissions
 - [ ] Must have permissions to remove permissions

<details open>
<summary>Password</summary>
    
   - [ ] Password must have at least 8 digits
   - [ ] Password must have at least 1 word
   - [ ] Password must have at least 1 symbol
</details>