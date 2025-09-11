# Project API Reference

This repository currently has no source files detected for automatic API extraction. This document provides a scaffold to document public APIs, functions, and components as they are added.

- See Components Guide: `./COMPONENTS.md`
- See Backend & Services: `./BACKEND.md`
- See Writing & Maintaining Docs: `./CONTRIBUTING.md`

## Conventions

- Public APIs are any exported functions, classes, types, or modules intended for external use.
- Each API entry should include: Description, Parameters, Returns, Examples, and Notes.

## Modules

Add modules here as they are created. Example template:

### module: `path/to/module`

- Purpose: One-line summary.
- Status: stable | experimental | deprecated

#### Functions

##### `functionName(arg1: Type, arg2: Type): ReturnType`

- Description: What the function does.
- Parameters:
  - `arg1` (Type): Meaning.
  - `arg2` (Type): Meaning.
- Returns: ReturnType — What is returned.
- Throws: Known error cases.
- Example:

```ts
import { functionName } from 'path/to/module'

const result = functionName('value1', 42)
console.log(result)
```

#### Classes

##### `ClassName`

- Description: Purpose.
- Constructor:
  - `new ClassName(options: Options)`
- Methods:
  - `doThing(input: Type): Output` — Description.
- Example:

```ts
const instance = new ClassName({ /* options */ })
instance.doThing('input')
```

## HTTP APIs

Document any REST/HTTP endpoints here.

- Method: GET | POST | PUT | DELETE
- Path: `/api/example`
- Query/Body: fields and types
- Responses: success and error shapes
- Example:

```bash
curl -sS -X GET 'http://localhost:3000/api/example?foo=bar'
```

## CLI Commands

Document any CLI commands.

- Command: `bin/cli subcommand --flag`
- Description: What it does
- Options:
  - `--flag`: Meaning
- Example:

```bash
bin/cli greet --name "World"
```
