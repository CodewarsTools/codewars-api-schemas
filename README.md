# codewars-api-schemas

JSON Schemas for Codewars API.

## Installation

```bash
npm install @codewarstools/codewars-api-schemas
```

## Schemas

* `challenges/challenge.schema.json`
* `user/authored-challenges.schema.json`
* `user/completed-challenges.schema.json`
* `user/profile.schema.json`

## API Documentation

* [Users API](https://dev.codewars.com/#users-api)
* [Code Challenges API](https://dev.codewars.com/#code-challenges-api)

## JSON Schema

The schemas use [JSON Schema Draft 2020-12](https://json-schema.org/draft/2020-12).

See the [official JSON Schema specification](https://json-schema.org/specification).

## Validation

The schemas can be validated using JSON Schema validators such as [AJV](https://ajv.js.org/).

## Tests

Schema tests are maintained in a separate repository:

[codewars-api-schemas-tests](https://github.com/CodewarsTools/codewars-api-schemas-tests)

The tests validate Codewars API data against the schemas provided by this package.

## License

MIT
