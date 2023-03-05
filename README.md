# Structurizr JSON

This GitHub repository contains the definition of the JSON schema for describing software architecture models based upon the [C4 model](https://c4model.com) with Structurizr.

The JSON format is __not__ designed to be authored manually. See [Authoring tools](https://github.com/structurizr#authoring-tools) for details about creating software architecture models using code-based libraries or text-based DSLs.

* [OpenAPI 3.0 definition ](structurizr.yaml)
* [Swagger Editor](https://editor.swagger.io/?url=https://raw.githubusercontent.com/structurizr/json/master/structurizr.yaml)
* [Examples](https://github.com/structurizr/examples)
* [JSON demo page](https://structurizr.com/json)

## Workspace validation rules

In addition to the JSON schema, workspaces are also subject to the following rules, which are implemented by the [Structurizr for Java library](https://github.com/structurizr/java):

- Element and relationship IDs must be unique.
- View keys must be unique.
- Software and people names must be unique.
- Container names must be unique within the context of a software system.
- Component names must be unique within the context of a container.
- Deployment node names must be unique with their parent context.
- Infrastructure node names must be unique with their parent context.
- All relationships from a source element to a destination element must have a unique description.
