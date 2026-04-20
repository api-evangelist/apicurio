# Apicurio (apicurio)
Apicurio is an open source API and schema tooling platform maintained by Red Hat under the Apache 2.0 license. It includes Apicurio Registry (a high-performance schema and API design registry), Apicurio Studio (a visual API designer for OpenAPI and AsyncAPI), Apicurio Data Models (a data modeling library), Apicurio Codegen (Java code generation from OpenAPI), and Apicurito (an embedded API editor).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apicurio/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache License, API Design, API Registry, Avro, AsyncAPI, Java, Open Source, OpenAPI, Red Hat, Schema Registry

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-04-19

## APIs

### Apicurio Registry
Apicurio Registry is a high-performance, runtime registry for schemas and API designs. It stores and manages OpenAPI, AsyncAPI, Avro, JSON Schema, Protobuf, and other artifact types, providing a REST API for schema management with compatibility checking and content versioning.

**Human URL:** [https://www.apicur.io/registry/](https://www.apicur.io/registry/)

#### Tags:

 - Avro, AsyncAPI, Open Source, OpenAPI, Protobuf, Schema Registry

#### Properties

- [Documentation](https://www.apicur.io/registry/docs/)
- [GitHubRepository](https://github.com/Apicurio/apicurio-registry)

### Apicurio Studio
Apicurio Studio is a visual, zero-code API design tool for creating and editing OpenAPI and AsyncAPI specifications. Note: Apicurio Studio is deprecated in favor of the integrated design capabilities in Apicurio Registry.

**Human URL:** [https://www.apicur.io/studio/](https://www.apicur.io/studio/)

#### Tags:

 - API Design, AsyncAPI, Deprecated, OpenAPI, Visual Designer

#### Properties

- [Documentation](https://www.apicur.io/studio/docs/)
- [GitHubRepository](https://github.com/Apicurio/apicurio-studio)

### Apicurio Data Models
Apicurio Data Models is a Java and TypeScript library for parsing, validating, and manipulating OpenAPI and AsyncAPI specification documents programmatically.

**Human URL:** [https://github.com/Apicurio/apicurio-data-models](https://github.com/Apicurio/apicurio-data-models)

#### Tags:

 - AsyncAPI, Data Modeling, Java, Library, OpenAPI, TypeScript

#### Properties

- [GitHubRepository](https://github.com/Apicurio/apicurio-data-models)

### Apicurio Codegen
Apicurio Codegen generates Java JAX-RS server stubs and client code from OpenAPI specifications, enabling design-first API development workflows.

**Human URL:** [https://github.com/Apicurio/apicurio-codegen](https://github.com/Apicurio/apicurio-codegen)

#### Tags:

 - Code Generation, JAX-RS, Java, OpenAPI

#### Properties

- [GitHubRepository](https://github.com/Apicurio/apicurio-codegen)

## Common Properties

- [Website](https://www.apicur.io)
- [Documentation](https://www.apicur.io/registry/docs/)
- [GitHubOrganization](https://github.com/Apicurio)
- [License](https://github.com/Apicurio/apicurio-registry/blob/main/LICENSE)

## Features

| Name | Description |
|------|-------------|
| Schema Registry | High-performance registry for storing and versioning schemas including Avro, JSON Schema, Protobuf, OpenAPI, and AsyncAPI. |
| Schema Compatibility Checking | Enforce backward, forward, or full compatibility rules when evolving schemas to prevent breaking changes. |
| Visual API Design | Zero-code visual editor for creating OpenAPI and AsyncAPI specifications without writing raw YAML or JSON. |
| REST API for Schema Management | Full REST API for programmatic schema registration, retrieval, and version management. |
| Java Code Generation | Generate JAX-RS server stubs and client code from OpenAPI specifications for design-first Java development. |
| Multi-Format Support | Support for OpenAPI, AsyncAPI, Avro, JSON Schema, Protobuf, WSDL, XSD, and GraphQL artifact types. |
| Apache License 2.0 | Open source under the Apache License 2.0, maintained by Red Hat with community contributions. |

## Use Cases

| Name | Description |
|------|-------------|
| Schema Governance | Centrally manage and version schemas across microservices with compatibility enforcement to prevent breaking changes. |
| Design-First API Development | Design OpenAPI and AsyncAPI specifications visually before writing code for design-first development. |
| Event-Driven Architecture | Manage Avro and Protobuf schemas for Kafka and other messaging systems in event-driven architectures. |
| API Contract Management | Store and version API specifications as the system of record for API contracts across teams. |
| Java Code Scaffolding | Generate JAX-RS server stubs from OpenAPI specs to accelerate Java API implementation. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
