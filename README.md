# SignON Orchestrator OpenAPI
The SignON Orchestrator OpenAPI repository is part of [SignON](https://signon-project.eu/) an EU H2020 research and innovation funded project.  
This repository specifies the REST API of the [SignON Orchestrator](https://github.com/signon-project/wp2-orchestrator), that are used by the [SignON Mobile
App](https://github.com/signon-project/wp2-mobile-app).

For further details please refer to public deliverable [D2.4 - Intermediate release of the Open SignON Framework](https://signon-project.eu/publications/public-deliverables/).

## Getting Started
To generate the SignON Orchestrator OpenAPI documentation, please follow the following steps.

### Prerequisites
- NVM:  
```curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash ```
- Node and NPM:  
```nvm install 14```

### Installation
- OpenAPI Generator:  
```npm install @openapitools/openapi-generator-cli -g```


### Usage
- Generate Documentation:
Start the Script from the root folder of this repository with:  
```. openapi_docgen.sh```


## Additional information

### Compatibility Matrix

| SignON Orchestrator OpenAPI | SignON Orchestrator Shared Schemas |
|:---------------------------:|:-------------------:|
|        14.0                 |         6.1         |

### Documentation
The generated documentation can be found in `docs` folder.  
It is provided in two formats:
- [HTML](docs/html/index.html)
- [Markdown](docs/markdown/README.md)

### Guideline for API styles
In order to standardize the AsyncAPI names for messages, components and fields the official guide from Swagger OpenAPI has been followed [link](https://swagger.io/specification/).

Some of the most important rules are:
 - Messages names are in Camel Case with the first letter in upper case
 - Components names are in Camel Case with the first letter in upper case
 - Fields names are in Camel Case with the first letter in lower case

#### Other details
- IDE: Visual Studio Code

## Authors
This project was developed by [FINCONS GROUP AG](https://www.finconsgroup.com/) within the Horizon 2020 European project SignON under grant agreement no. [101017255](https://doi.org/10.3030/101017255).  
For any further information, please send an email to [signon-dev@finconsgroup.com](mailto:signon-dev@finconsgroup.com).

## Licence
This project is released under the [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0.html).