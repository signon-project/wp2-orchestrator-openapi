# App
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sourceKey** | **String** | Where to find the video or the audio given by the user, if value not available use \&quot;NONE\&quot;. | [default to null]
**sourceText** | **String** | Text that the user wants to be translated, if value not available use \&quot;NONE\&quot;. | [default to null]
**sourceLanguage** | [**Languages**](Languages.md) |  | [default to null]
**sourceMode** | **String** | ENUM representing the mode in which the message is given by the user. | [default to null]
**sourceFileFormat** | **String** | The format in which the file containing data regarding the video or the audio given by the user is saved, if value not available use \&quot;NONE\&quot;. | [default to null]
**sourceVideoCodec** | **String** | The codec used to compress the video, if value not available use \&quot;NONE\&quot;. | [default to null]
**sourceVideoResolution** | **String** | The resolution used for the video, if value not available use \&quot;NONE\&quot;. | [default to null]
**sourceVideoFrameRate** | **BigDecimal** | The frame rate used for the video, if value not available use \&quot;-1\&quot;. | [default to null]
**sourceVideoPixelFormat** | **String** | The pixel format used for the video, if value not available use \&quot;NONE\&quot;. | [default to null]
**sourceAudioCodec** | **String** | The codec used to compress the audio, if value not available use \&quot;NONE\&quot;. | [default to null]
**sourceAudioChannels** | **String** | The channels used for the audio, if value not available use \&quot;NONE\&quot;. | [default to null]
**sourceAudioSampleRate** | **BigDecimal** | The sample rate used for the audio, if value not available use \&quot;-1\&quot;. | [default to null]
**translationLanguage** | [**Languages**](Languages.md) |  | [default to null]
**translationMode** | **String** | ENUM representing the mode in which the message has to be returned to the user. | [default to null]
**appInstanceID** | **String** | Identifier to recognize which instance of the app has sent the message. | [default to null]
**appVersion** | **String** | App Version Number | [default to null]
**T0App** | **BigDecimal** | Timestamp at which the message has been sent from the App to the orchestrator (yyyy-MM-dd HH:mm:ss,SSS). | [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

