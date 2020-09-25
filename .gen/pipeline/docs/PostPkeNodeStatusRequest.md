# PostPkeNodeStatusRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | name of node | [optional] 
**NodePool** | **string** | name of nodepool | [optional] 
**Ip** | **string** | ip address of node (where the other nodes can reach it) | [optional] 
**Message** | **string** | detailed description about the current bootstrapping status (including the cause of the failure) | [optional] 
**Phase** | **string** | the current phase of the bootstrap process | [optional] 
**Finished** | **bool** | if the installation process is finished (either with success or failure) | [optional] 
**Failure** | **bool** | if a fatal failure occurred (i.e. the node will not come up) | [optional] 
**Timestamp** | Pointer to [**time.Time**](time.Time.md) | exact time of event | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


