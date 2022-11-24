# Datastore API JSON Schema

Here you can find the [JSON Schema](https://json-schema.org) for validating Datastore API documents.

As a reminder, the JSON Schema is not the source of truth for the [Datastore API Specification ](../../versions/1.0.0.md). In cases of conflicts between the Specification itself and the JSON Schema, the Specification wins. Also, some Specification constraints cannot be represented with the JSON Schema so it's highly recommended to employ other methods to ensure compliance.

## Schema documentation

[Schema documentation](./docs) is generated using [JSON Schema for Humans](https://coveooss.github.io/json-schema-for-humans). It is available in markdown and html format. The documentation is generated using the settings contained in config.yaml file running the following command:

`./generate-schema-doc --config-file ./schemas/v1.0/config.yaml ./schemas/v1.0/dataProductDescriptor.json ./schemas/v1.0/.html`



## Roadmap

- Review schema structure
- Complete schema documentation
    - see https://github.com/OAI/OpenAPI-Specification/tree/main/schemas/v3.1
    - see https://github.com/asyncapi/spec-json-schemas
- Add examples
    - see https://jsoncrack.com/editor
- Add schema to schemaStore
    - see https://www.schemastore.org/json/
- Translate [./docs/README.md](./docs/README.md)
- Rename repo :)