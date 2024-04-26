# DefaultApi

All URIs are relative to *http://signon-api-endpoint/orchestrator*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getConsentForm**](DefaultApi.md#getConsentForm) | **GET** /consent-form | Return Consent Form
[**getDatasetStorageAuth**](DefaultApi.md#getDatasetStorageAuth) | **GET** /dataset-storage-auth | Request Credentials for the App to write on Minio
[**getEafFormat**](DefaultApi.md#getEafFormat) | **POST** /eaf-format | Format data in EAF Annotation Format for ELAN  (https://archive.mpi.nl/tla/elan)
[**getEndpoints**](DefaultApi.md#getEndpoints) | **GET** /endpoints | Request to return all the possible Endpoints
[**getInferenceStorageAuth**](DefaultApi.md#getInferenceStorageAuth) | **GET** /inference-storage-auth | Request Credentials for the App to write on Minio
[**getStatus**](DefaultApi.md#getStatus) | **GET** /status | Request status relative to the Orchestrator
[**getVersion**](DefaultApi.md#getVersion) | **GET** /version | Request Version Number related to Orchestrator, OpenAPI and AsyncAPI
[**sendMessage**](DefaultApi.md#sendMessage) | **POST** /message | JSON Message Between App and orchestrator


<a name="getConsentForm"></a>
# **getConsentForm**
> consentFormResponse getConsentForm(language)

Return Consent Form

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **language** | [**Languages**](../Models/.md)| Language in which you want the consent-form | [default to null] [enum: VGT, SSP, BFI, ISG, DSE, ENG, GLE, NLD, SPA, DUT]

### Return type

[**consentFormResponse**](../Models/consentFormResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getDatasetStorageAuth"></a>
# **getDatasetStorageAuth**
> inference-storage-auth-response getDatasetStorageAuth(hashPhoneNUmber, metadata)

Request Credentials for the App to write on Minio

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **hashPhoneNUmber** | **String**| Identifier to recognize which instance of the app is requesting permission to upload an object on Minio. | [optional] [default to null]
 **metadata** | [**Metadata**](../Models/.md)|  | [optional] [default to null]

### Return type

[**inference-storage-auth-response**](../Models/inference-storage-auth-response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getEafFormat"></a>
# **getEafFormat**
> EafFormatResponse getEafFormat(EafFormatRequest)

Format data in EAF Annotation Format for ELAN  (https://archive.mpi.nl/tla/elan)

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **EafFormatRequest** | [**EafFormatRequest**](../Models/EafFormatRequest.md)|  |

### Return type

[**EafFormatResponse**](../Models/EafFormatResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="getEndpoints"></a>
# **getEndpoints**
> List getEndpoints()

Request to return all the possible Endpoints

### Parameters
This endpoint does not need any parameter.

### Return type

**List**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getInferenceStorageAuth"></a>
# **getInferenceStorageAuth**
> inference-storage-auth-response getInferenceStorageAuth(appInstanceID, fileFormat)

Request Credentials for the App to write on Minio

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appInstanceID** | **String**| Identifier to recognize which instance of the app is requesting permission to upload an object on Minio. | [optional] [default to null]
 **fileFormat** | **String**| The format in which the file containing data regarding the video or the audio given by the user is saved. | [optional] [default to null]

### Return type

[**inference-storage-auth-response**](../Models/inference-storage-auth-response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getStatus"></a>
# **getStatus**
> status getStatus()

Request status relative to the Orchestrator

### Parameters
This endpoint does not need any parameter.

### Return type

[**status**](../Models/status.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getVersion"></a>
# **getVersion**
> version getVersion()

Request Version Number related to Orchestrator, OpenAPI and AsyncAPI

### Parameters
This endpoint does not need any parameter.

### Return type

[**version**](../Models/version.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="sendMessage"></a>
# **sendMessage**
> OrchestratorToApp sendMessage(AppToOrchestrator)

JSON Message Between App and orchestrator

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **AppToOrchestrator** | [**AppToOrchestrator**](../Models/AppToOrchestrator.md)|  |

### Return type

[**OrchestratorToApp**](../Models/OrchestratorToApp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

