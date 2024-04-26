# Documentation for SignON Orchestrator OpenAPI

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *http://signon-api-endpoint/orchestrator*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**getConsentForm**](Apis/DefaultApi.md#getconsentform) | **GET** /consent-form | Return Consent Form
*DefaultApi* | [**getDatasetStorageAuth**](Apis/DefaultApi.md#getdatasetstorageauth) | **GET** /dataset-storage-auth | Request Credentials for the App to write on Minio
*DefaultApi* | [**getEafFormat**](Apis/DefaultApi.md#geteafformat) | **POST** /eaf-format | Format data in EAF Annotation Format for ELAN  (https://archive.mpi.nl/tla/elan)
*DefaultApi* | [**getEndpoints**](Apis/DefaultApi.md#getendpoints) | **GET** /endpoints | Request to return all the possible Endpoints
*DefaultApi* | [**getInferenceStorageAuth**](Apis/DefaultApi.md#getinferencestorageauth) | **GET** /inference-storage-auth | Request Credentials for the App to write on Minio
*DefaultApi* | [**getStatus**](Apis/DefaultApi.md#getstatus) | **GET** /status | Request status relative to the Orchestrator
*DefaultApi* | [**getVersion**](Apis/DefaultApi.md#getversion) | **GET** /version | Request Version Number related to Orchestrator, OpenAPI and AsyncAPI
*DefaultApi* | [**sendMessage**](Apis/DefaultApi.md#sendmessage) | **POST** /message | JSON Message Between App and orchestrator


<a name="documentation-for-models"></a>
## Documentation for Models

 - [Annotation](./Models/Annotation.md)
 - [App](./Models/App.md)
 - [AppToOrchestrator](./Models/AppToOrchestrator.md)
 - [EafFormatRequest](./Models/EafFormatRequest.md)
 - [EafFormatResponse](./Models/EafFormatResponse.md)
 - [Error](./Models/Error.md)
 - [Languages](./Models/Languages.md)
 - [Metadata](./Models/Metadata.md)
 - [OrchestratorRequest](./Models/OrchestratorRequest.md)
 - [OrchestratorResponse](./Models/OrchestratorResponse.md)
 - [OrchestratorToApp](./Models/OrchestratorToApp.md)
 - [RabbitMQ](./Models/RabbitMQ.md)
 - [consentFormRequest](./Models/consentFormRequest.md)
 - [consentFormResponse](./Models/consentFormResponse.md)
 - [dataset-storage-auth-request](./Models/dataset-storage-auth-request.md)
 - [inference-storage-auth-request](./Models/inference-storage-auth-request.md)
 - [inference-storage-auth-response](./Models/inference-storage-auth-response.md)
 - [status](./Models/status.md)
 - [version](./Models/version.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

All endpoints do not require authorization.
