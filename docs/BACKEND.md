# Backend & Services

List backend services, data models, and integration points.

## Data Models

Describe entities, fields, and relationships.

## Services / Modules

For each service, include: Purpose, Configuration, Methods/Endpoints, Error Handling, and Examples.

### Example Service: `UserService`

- Purpose: Manage user accounts.
- Methods:
  - `createUser(input: CreateUserInput): User`
  - `getUserById(userId: string): User | null`
- Example:

```ts
const user = await userService.createUser({ email: 'a@b.com', password: 'secret' })
```
