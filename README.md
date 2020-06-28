![Structurizr](docs/images/structurizr-banner.png)

# Structurizr JSON

This GitHub repository contains the definition of the JSON schema for describing software architecture models based upon the [C4 model](https://c4model.com) with Structurizr. __This repository is supported by Structurizr Limited__, as a part of the Structurizr service.

The JSON format is __not__ designed to be authored manually. See [Structurizr - Getting started](https://structurizr.com/help/getting-started) for details about creating software architecture models using code, text, or the UI.

* [OpenAPI 3.0 definition ](structurizr.yaml)
* [Swagger Editor](https://editor.swagger.io/?url=https://raw.githubusercontent.com/structurizr/json/master/structurizr.yaml)
* Examples
	* [Getting Started](https://structurizr.com/json?src=https://raw.githubusercontent.com/structurizr/json/master/examples/getting-started.json)
	* [Financial Risk System](https://structurizr.com/json?src=https://raw.githubusercontent.com/structurizr/json/master/examples/financial-risk-system.json)
	* [Big Bank plc](https://structurizr.com/json?src=https://raw.githubusercontent.com/structurizr/json/master/examples/big-bank-plc.json)
	* [Amazon Web Services](https://structurizr.com/json?src=https://raw.githubusercontent.com/structurizr/json/master/examples/amazon-web-services.json)

## Workspace validation rules

In addition to the JSON schema, workspaces are also subject to the following rules:

- Element and relationship IDs must be unique.
- View keys must be unique.
- Software and people names must be unique.
- Container names must be unique within the context of a software system.
- Component names must be unique within the context of a container.
- Deployment node names must be unique with their parent context.
- Infrastructure node names must be unique with their parent context.
- All relationships from a source element to a destination element must have a unique description.
