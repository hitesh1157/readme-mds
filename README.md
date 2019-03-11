# Protocol Documentation
<a name="top"></a>

## Table of Contents

- [accepted_transactions.proto](#accepted_transactions.proto)
    - [AcceptedTransactionMessage](#acceptedTransactions.AcceptedTransactionMessage)
    - [CompletedTransactionMessage](#acceptedTransactions.CompletedTransactionMessage)
    - [Error](#acceptedTransactions.Error)
    - [ExpireTransactionMessage](#acceptedTransactions.ExpireTransactionMessage)
    - [Response](#acceptedTransactions.Response)
    - [Response.FieldsEntry](#acceptedTransactions.Response.FieldsEntry)
    - [StatusChangeToNotFinalizedMessage](#acceptedTransactions.StatusChangeToNotFinalizedMessage)
    - [StatusChangeToOnMoveMessage](#acceptedTransactions.StatusChangeToOnMoveMessage)
    - [Value](#acceptedTransactions.Value)
  
    - [NullValue](#acceptedTransactions.NullValue)
  
  
    - [AcceptedTransactionService](#acceptedTransactions.AcceptedTransactionService)
  

- [account.proto](#account.proto)
    - [Account](#account.Account)
    - [DisplayComment](#account.DisplayComment)
    - [Error](#account.Error)
    - [Response](#account.Response)
    - [Response.FieldsEntry](#account.Response.FieldsEntry)
    - [UpdateAccountMessage](#account.UpdateAccountMessage)
    - [UserIdentification](#account.UserIdentification)
    - [Value](#account.Value)
  
    - [NullValue](#account.NullValue)
  
  
    - [AccountService](#account.AccountService)
  

- [annotations.proto](#annotations.proto)
  
  
    - [File-level Extensions](#annotations.proto-extensions)
  
  

- [basic_enums.proto](#basic_enums.proto)
  
    - [CurrencyUnit](#.CurrencyUnit)
    - [DimensionUnit](#.DimensionUnit)
    - [DistanceUnit](#.DistanceUnit)
    - [ModeOfTravel](#.ModeOfTravel)
    - [PersonType](#.PersonType)
    - [Status](#.Status)
    - [WeightUnit](#.WeightUnit)
  
  
  

- [common.proto](#common.proto)
    - [PersonalityStructure](#.PersonalityStructure)
    - [RatingStructure](#.RatingStructure)
  
  
  
  

- [completed_transaction.proto](#completed_transaction.proto)
    - [CompletedTransactionMessage](#completedTransactions.CompletedTransactionMessage)
    - [Error](#completedTransactions.Error)
    - [Response](#completedTransactions.Response)
    - [Response.FieldsEntry](#completedTransactions.Response.FieldsEntry)
    - [Value](#completedTransactions.Value)
  
    - [NullValue](#completedTransactions.NullValue)
  
  
    - [CompletedTransactionService](#completedTransactions.CompletedTransactionService)
  

- [http.proto](#http.proto)
    - [CustomHttpPattern](#google.api.CustomHttpPattern)
    - [Http](#google.api.Http)
    - [HttpRule](#google.api.HttpRule)
  
  
  
  

- [item.proto](#item.proto)
    - [Address](#item.Address)
    - [Error](#item.Error)
    - [ItemForNotificationMessage](#item.ItemForNotificationMessage)
    - [ItemIdentification](#item.ItemIdentification)
    - [ItemMessage](#item.ItemMessage)
    - [Response](#item.Response)
    - [Response.FieldsEntry](#item.Response.FieldsEntry)
    - [StringList](#item.StringList)
    - [UpdateItemMessage](#item.UpdateItemMessage)
    - [Value](#item.Value)
  
    - [NullValue](#item.NullValue)
  
  
    - [ItemService](#item.ItemService)
  

- [item_post.proto](#item_post.proto)
    - [Error](#itemPosts.Error)
    - [ExpireItemPostMessage](#itemPosts.ExpireItemPostMessage)
    - [ItemPostIdentification](#itemPosts.ItemPostIdentification)
    - [ItemPostMessage](#itemPosts.ItemPostMessage)
    - [ItemPostUpdateMessage](#itemPosts.ItemPostUpdateMessage)
    - [Response](#itemPosts.Response)
    - [Response.FieldsEntry](#itemPosts.Response.FieldsEntry)
    - [StatusChangeToInRequestMessage](#itemPosts.StatusChangeToInRequestMessage)
    - [StatusChangeToNotFinalizedMessage](#itemPosts.StatusChangeToNotFinalizedMessage)
    - [UpdateStatusMessage](#itemPosts.UpdateStatusMessage)
    - [Value](#itemPosts.Value)
  
    - [NullValue](#itemPosts.NullValue)
  
  
    - [ItemPostService](#itemPosts.ItemPostService)
  

- [job.proto](#job.proto)
    - [CreateJobMessage](#jobs.CreateJobMessage)
    - [Error](#jobs.Error)
    - [JobMessage](#jobs.JobMessage)
    - [Response](#jobs.Response)
    - [Response.FieldsEntry](#jobs.Response.FieldsEntry)
    - [Value](#jobs.Value)
  
    - [NullValue](#jobs.NullValue)
  
  
    - [JobService](#jobs.JobService)
  

- [notifications.proto](#notifications.proto)
    - [Error](#notifications.Error)
    - [NotificationMessage](#notifications.NotificationMessage)
    - [NotificationMessage.ContentsEntry](#notifications.NotificationMessage.ContentsEntry)
    - [NotificationMessage.HeadingsEntry](#notifications.NotificationMessage.HeadingsEntry)
    - [OsNotificationReschedule](#notifications.OsNotificationReschedule)
    - [Response](#notifications.Response)
    - [Response.FieldsEntry](#notifications.Response.FieldsEntry)
    - [Value](#notifications.Value)
  
    - [NullValue](#notifications.NullValue)
  
  
    - [NotificationService](#notifications.NotificationService)
  

- [pending_rating.proto](#pending_rating.proto)
    - [DeletePendingRatingMessage](#pendingRatings.DeletePendingRatingMessage)
    - [Error](#pendingRatings.Error)
    - [PendingRatingsForCTIdMessage](#pendingRatings.PendingRatingsForCTIdMessage)
    - [Response](#pendingRatings.Response)
    - [Response.FieldsEntry](#pendingRatings.Response.FieldsEntry)
    - [Value](#pendingRatings.Value)
  
    - [NullValue](#pendingRatings.NullValue)
  
  
    - [PendingRatingService](#pendingRatings.PendingRatingService)
  

- [rating.proto](#rating.proto)
    - [CreateRatingMessage](#ratings.CreateRatingMessage)
    - [Error](#ratings.Error)
    - [Response](#ratings.Response)
    - [Response.FieldsEntry](#ratings.Response.FieldsEntry)
    - [Value](#ratings.Value)
  
    - [NullValue](#ratings.NullValue)
  
  
    - [RatingService](#ratings.RatingService)
  

- [request_post.proto](#request_post.proto)
    - [Error](#requestPost.Error)
    - [IntList](#requestPost.IntList)
    - [RequestPostMessage](#requestPost.RequestPostMessage)
    - [Response](#requestPost.Response)
    - [Response.FieldsEntry](#requestPost.Response.FieldsEntry)
    - [StatusChangeToFinalizedMessage](#requestPost.StatusChangeToFinalizedMessage)
    - [UpdateAllStatusesOf](#requestPost.UpdateAllStatusesOf)
    - [Value](#requestPost.Value)
  
    - [NullValue](#requestPost.NullValue)
  
  
    - [RequestPostService](#requestPost.RequestPostService)
  

- [travel_plan_post.proto](#travel_plan_post.proto)
    - [Error](#travelPlanPosts.Error)
    - [ExpireTravelPlanPostMessage](#travelPlanPosts.ExpireTravelPlanPostMessage)
    - [Response](#travelPlanPosts.Response)
    - [Response.FieldsEntry](#travelPlanPosts.Response.FieldsEntry)
    - [StatusChangeToInRequestMessage](#travelPlanPosts.StatusChangeToInRequestMessage)
    - [StatusChangeToNotFinalizedMessage](#travelPlanPosts.StatusChangeToNotFinalizedMessage)
    - [TravelPlanPostIdentification](#travelPlanPosts.TravelPlanPostIdentification)
    - [TravelPlanPostMessage](#travelPlanPosts.TravelPlanPostMessage)
    - [TravelPlanPostUpdateMessage](#travelPlanPosts.TravelPlanPostUpdateMessage)
    - [UpdateStatusMessage](#travelPlanPosts.UpdateStatusMessage)
    - [Value](#travelPlanPosts.Value)
  
    - [NullValue](#travelPlanPosts.NullValue)
  
  
    - [TravelPlanPostService](#travelPlanPosts.TravelPlanPostService)
  

- [travel_plans.proto](#travel_plans.proto)
    - [Address](#travelPlans.Address)
    - [Error](#travelPlans.Error)
    - [Response](#travelPlans.Response)
    - [Response.FieldsEntry](#travelPlans.Response.FieldsEntry)
    - [TravelPlanForNotificationMessage](#travelPlans.TravelPlanForNotificationMessage)
    - [TravelPlanIdentification](#travelPlans.TravelPlanIdentification)
    - [TravelPlanMessage](#travelPlans.TravelPlanMessage)
    - [UpdateTravelPlanMessage](#travelPlans.UpdateTravelPlanMessage)
    - [Value](#travelPlans.Value)
  
    - [NullValue](#travelPlans.NullValue)
  
  
    - [TravelPlanService](#travelPlans.TravelPlanService)
  

- [user.proto](#user.proto)
    - [Address](#user.Address)
    - [Error](#user.Error)
    - [NewRatingFeatureMessage](#user.NewRatingFeatureMessage)
    - [OsTokensMessage](#user.OsTokensMessage)
    - [Personal](#user.Personal)
    - [Response](#user.Response)
    - [Response.FieldsEntry](#user.Response.FieldsEntry)
    - [UpdateUserFields](#user.UpdateUserFields)
    - [User](#user.User)
    - [UserAccountPart](#user.UserAccountPart)
    - [UserIdentification](#user.UserIdentification)
    - [UserIdentifications](#user.UserIdentifications)
    - [UsersMobileNumber](#user.UsersMobileNumber)
    - [Value](#user.Value)
    - [Verifications](#user.Verifications)
  
    - [NullValue](#user.NullValue)
    - [Personal.Gender](#user.Personal.Gender)
  
  
    - [UserService](#user.UserService)
  

- [Scalar Value Types](#scalar-value-types)



<a name="accepted_transactions.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## accepted_transactions.proto
Accepted Transaction related messages


<a name="acceptedTransactions.AcceptedTransactionMessage"></a>

### AcceptedTransactionMessage
Represents an Accepted Transaction


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |
| traveller_id | [string](#string) |  |  |
| owner_id | [string](#string) |  |  |
| non_owner_id | [string](#string) |  |  |
| owner_type | [PersonType](#PersonType) |  |  |
| non_owner_type | [PersonType](#PersonType) |  |  |
| item_status | [Status](#Status) |  |  |
| travel_plan_status | [Status](#Status) |  |  |
| requested_by_traveller | [bool](#bool) |  | Represents if the initial request was made by traveller or not |






<a name="acceptedTransactions.CompletedTransactionMessage"></a>

### CompletedTransactionMessage
Represents a message to complete a transaction


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |
| completed_by_user_id | [string](#string) |  |  |






<a name="acceptedTransactions.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="acceptedTransactions.ExpireTransactionMessage"></a>

### ExpireTransactionMessage
Represents a message to expire a given transaction


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |
| expire_item | [bool](#bool) |  | Represents if item is expired or travelplan is expired |






<a name="acceptedTransactions.Response"></a>

### Response
Represents a AcceptedTransactionService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#acceptedTransactions.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="acceptedTransactions.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#acceptedTransactions.Value) |  |  |






<a name="acceptedTransactions.StatusChangeToNotFinalizedMessage"></a>

### StatusChangeToNotFinalizedMessage
Represents a message to change status to NOT_FINALIZED of both item and travel plan


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |






<a name="acceptedTransactions.StatusChangeToOnMoveMessage"></a>

### StatusChangeToOnMoveMessage
Represents a message to change status to ON_MOVE  of both item and travel plan


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |






<a name="acceptedTransactions.Value"></a>

### Value



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| accepted_transaction_message_value | [AcceptedTransactionMessage](#acceptedTransactions.AcceptedTransactionMessage) |  | AcceptedTransactionMessage value |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#acceptedTransactions.Error) |  | Error value |
| null_value | [NullValue](#acceptedTransactions.NullValue) |  | NULL value |





 


<a name="acceptedTransactions.NullValue"></a>

### NullValue
Represents a NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 | NULL value |


 

 


<a name="acceptedTransactions.AcceptedTransactionService"></a>

### AcceptedTransactionService
Service for handling events after transaction is finalized

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateAcceptedTransaction | [AcceptedTransactionMessage](#acceptedTransactions.AcceptedTransactionMessage) | [Response](#acceptedTransactions.Response) | Creates an accepted transaction |
| StatusChangeToNotFinalized | [StatusChangeToNotFinalizedMessage](#acceptedTransactions.StatusChangeToNotFinalizedMessage) | [Response](#acceptedTransactions.Response) | Sets status of item and travel plan to NOT_FINALIZED. Delete&#39;s the accepted transaction, sets item status and travel plan status to IN_REQUEST, creates a RequestPost iff both item and travel plan are not expired, updates statuses of all other request posts of that item and that travel plan. |
| StatusChangeToOnMove | [StatusChangeToOnMoveMessage](#acceptedTransactions.StatusChangeToOnMoveMessage) | [Response](#acceptedTransactions.Response) | Sets the status of accepted transaction to ON_MOVE, updates the status of ItemPost and TravelPlanPost to ON_MOVE as well and deletes all RequestPosts of Item and TravelPlan. |
| CompleteTransaction | [CompletedTransactionMessage](#acceptedTransactions.CompletedTransactionMessage) | [Response](#acceptedTransactions.Response) | Completes the ON_MOVE transaction. Creates a CompletedTransaction document (for History), gets the item&#39;s name from Item and calls `createPendingRatingsForCTId` from PendingRatingServiceGrpc to create 6 pendingRating documents to provided ratings for all users involved in the transaction, deletes ItemPost and TravelPlanPost |
| ExpireTransaction | [ExpireTransactionMessage](#acceptedTransactions.ExpireTransactionMessage) | [Response](#acceptedTransactions.Response) | Expires the accepted transaction to denote that the item/travel plans&#39;s time has passed. If ExpireTransactionMessage.expireItem is set true, sets itemExpired=true otherwise travelPlanExpired=true |

 



<a name="account.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## account.proto
User.Account related messages.


<a name="account.Account"></a>

### Account
Represents a complete Account


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| number_of_authorisations | [int32](#int32) |  |  |
| number_of_recommendations | [int32](#int32) |  |  |
| rating | [double](#double) |  |  |
| number_of_ratings | [int32](#int32) |  |  |
| personality_structure | [PersonalityStructure](#PersonalityStructure) |  | Personality Structure |
| rating_structure | [RatingStructure](#RatingStructure) |  | Rating Structure |
| comments | [DisplayComment](#account.DisplayComment) | repeated | Comment from or to a given user |






<a name="account.DisplayComment"></a>

### DisplayComment
Represents a comment from or to a given user


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| from | [string](#string) |  | UserId |
| to | [string](#string) |  | UserId |
| given | [bool](#bool) |  |  |
| rating | [double](#double) |  |  |
| timestamp | [int64](#int64) |  |  |






<a name="account.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="account.Response"></a>

### Response
Represents a UserService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#account.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="account.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#account.Value) |  |  |






<a name="account.UpdateAccountMessage"></a>

### UpdateAccountMessage
Represents an User.Account update message


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| user_id | [string](#string) |  |  |
| personality_structure | [PersonalityStructure](#PersonalityStructure) |  |  |
| rating | [double](#double) |  |  |
| recommended | [bool](#bool) |  |  |






<a name="account.UserIdentification"></a>

### UserIdentification
Message to identify User.Account


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| user_id | [string](#string) |  |  |






<a name="account.Value"></a>

### Value
Represents Value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| account_value | [Account](#account.Account) |  | Account value |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#account.Error) |  | Error value |
| null_value | [NullValue](#account.NullValue) |  | NULL value |





 


<a name="account.NullValue"></a>

### NullValue
NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |


 

 


<a name="account.AccountService"></a>

### AccountService
Service for handling User.Account

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateAccount | [UserIdentification](#account.UserIdentification) | [Response](#account.Response) | Creates an account document of a given user |
| GetAccountInfo | [UserIdentification](#account.UserIdentification) | [Response](#account.Response) | Returns aggregated Account info by collecting data of a given userId from User collection and itself. |
| UpdateAccount | [UpdateAccountMessage](#account.UpdateAccountMessage) | [Response](#account.Response) | Aggregates a new rating to a given user |

 



<a name="annotations.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## annotations.proto


 

 


<a name="annotations.proto-extensions"></a>

### File-level Extensions
| Extension | Type | Base | Number | Description |
| --------- | ---- | ---- | ------ | ----------- |
| http | HttpRule | .google.protobuf.MethodOptions | 72295728 | See `HttpRule`. |

 

 



<a name="basic_enums.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## basic_enums.proto
Basic enum objects.

 


<a name=".CurrencyUnit"></a>

### CurrencyUnit
Represents local currency unit

| Name | Number | Description |
| ---- | ------ | ----------- |
| RS | 0 | Default |



<a name=".DimensionUnit"></a>

### DimensionUnit
Represents dimension unit of length/width/height

| Name | Number | Description |
| ---- | ------ | ----------- |
| CM | 0 | Default |
| IN | 1 |  |



<a name=".DistanceUnit"></a>

### DistanceUnit
Represents distance unit

| Name | Number | Description |
| ---- | ------ | ----------- |
| KM | 0 |  |
| MT | 1 |  |



<a name=".ModeOfTravel"></a>

### ModeOfTravel
Represents mode of travel of a travel plan

| Name | Number | Description |
| ---- | ------ | ----------- |
| RAIL | 0 |  |
| ROAD | 1 |  |
| AIR | 2 |  |



<a name=".PersonType"></a>

### PersonType
Represents type of person

| Name | Number | Description |
| ---- | ------ | ----------- |
| SENDER | 0 |  |
| RECEIVER | 1 |  |
| TRAVELLER | 2 |  |



<a name=".Status"></a>

### Status
Represents status of item/travel plan

| Name | Number | Description |
| ---- | ------ | ----------- |
| NOT_FINALIZED | 0 | Default |
| FINALIZED | 1 |  |
| ON_MOVE | 2 |  |
| IN_REQUEST | 3 |  |



<a name=".WeightUnit"></a>

### WeightUnit
Represents weight unit

| Name | Number | Description |
| ---- | ------ | ----------- |
| KG | 0 | Default |
| GM | 1 |  |


 

 

 



<a name="common.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## common.proto
Common messages


<a name=".PersonalityStructure"></a>

### PersonalityStructure
Account&#39;s Personality Structure


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| good_behavior | [int32](#int32) |  |  |
| good_communication | [int32](#int32) |  |  |
| punctual | [int32](#int32) |  |  |
| reliable | [int32](#int32) |  |  |






<a name=".RatingStructure"></a>

### RatingStructure
Account&#39;s RatingStructure


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| disappointing | [int32](#int32) |  |  |
| excellent | [int32](#int32) |  |  |
| good | [int32](#int32) |  |  |
| outstanding | [int32](#int32) |  |  |
| poor | [int32](#int32) |  |  |





 

 

 

 



<a name="completed_transaction.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## completed_transaction.proto
Completed Transaction related messages


<a name="completedTransactions.CompletedTransactionMessage"></a>

### CompletedTransactionMessage
Represents a CompletedTransaction


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| completed_by_user | [string](#string) |  | UserId of the user who initiated the completion |
| completed_on | [int64](#int64) |  | Date of completion of this transaction |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |
| traveller_id | [string](#string) |  |  |
| owner_id | [string](#string) |  |  |
| non_owner_id | [string](#string) |  |  |
| owner_type | [PersonType](#PersonType) |  |  |
| non_owner_type | [PersonType](#PersonType) |  |  |
| requested_by_traveller | [bool](#bool) |  | Represents if this transaction was initially requested by traveller or not |
| item_expired | [bool](#bool) |  | Represents if item has expired or not |
| travel_plan_expired | [bool](#bool) |  |  |
| transit_end_date | [int64](#int64) |  |  |
| transit_start_date | [int64](#int64) |  |  |
| transit_start_otp | [string](#string) |  |  |
| transit_end_otp | [string](#string) |  |  |
| item_status | [Status](#Status) |  |  |
| travel_plan_status | [Status](#Status) |  |  |






<a name="completedTransactions.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="completedTransactions.Response"></a>

### Response
Represents a CompletedTransactionService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#completedTransactions.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="completedTransactions.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#completedTransactions.Value) |  |  |






<a name="completedTransactions.Value"></a>

### Value
Represents a return Value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#completedTransactions.Error) |  | Error value |
| null_value | [NullValue](#completedTransactions.NullValue) |  | NULL value |





 


<a name="completedTransactions.NullValue"></a>

### NullValue
NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |


 

 


<a name="completedTransactions.CompletedTransactionService"></a>

### CompletedTransactionService
Service for handling CompletedTransaction

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateCompletedTransaction | [CompletedTransactionMessage](#completedTransactions.CompletedTransactionMessage) | [Response](#completedTransactions.Response) | Creates a new CompletedTransaction |

 



<a name="http.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## http.proto



<a name="google.api.CustomHttpPattern"></a>

### CustomHttpPattern
A custom pattern is used for defining custom HTTP verb.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| kind | [string](#string) |  | The name of this custom HTTP verb. |
| path | [string](#string) |  | The path matched by this custom verb. |






<a name="google.api.Http"></a>

### Http
Defines the HTTP configuration for an API service. It contains a list of
[HttpRule][google.api.HttpRule], each specifying the mapping of an RPC method
to one or more HTTP REST API methods.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| rules | [HttpRule](#google.api.HttpRule) | repeated | A list of HTTP configuration rules that apply to individual API methods.

**NOTE:** All service configuration rules follow &#34;last one wins&#34; order. |
| fully_decode_reserved_expansion | [bool](#bool) |  | When set to true, URL path parmeters will be fully URI-decoded except in cases of single segment matches in reserved expansion, where &#34;%2F&#34; will be left encoded.

The default behavior is to not decode RFC 6570 reserved characters in multi segment matches. |






<a name="google.api.HttpRule"></a>

### HttpRule
`HttpRule` defines the mapping of an RPC method to one or more HTTP
REST API methods. The mapping specifies how different portions of the RPC
request message are mapped to URL path, URL query parameters, and
HTTP request body. The mapping is typically specified as an
`google.api.http` annotation on the RPC method,
see &#34;google/api/annotations.proto&#34; for details.

The mapping consists of a field specifying the path template and
method kind.  The path template can refer to fields in the request
message, as in the example below which describes a REST GET
operation on a resource collection of messages:


    service Messaging {
      rpc GetMessage(GetMessageRequest) returns (Message) {
        option (google.api.http).get = &#34;/v1/messages/{message_id}/{sub.subfield}&#34;;
      }
    }
    message GetMessageRequest {
      message SubMessage {
        string subfield = 1;
      }
      string message_id = 1; // mapped to the URL
      SubMessage sub = 2;    // `sub.subfield` is url-mapped
    }
    message Message {
      string text = 1; // content of the resource
    }

The same http annotation can alternatively be expressed inside the
`GRPC API Configuration` YAML file.

    http:
      rules:
        - selector: &lt;proto_package_name&gt;.Messaging.GetMessage
          get: /v1/messages/{message_id}/{sub.subfield}

This definition enables an automatic, bidrectional mapping of HTTP
JSON to RPC. Example:

HTTP | RPC
-----|-----
`GET /v1/messages/123456/foo`  | `GetMessage(message_id: &#34;123456&#34; sub: SubMessage(subfield: &#34;foo&#34;))`

In general, not only fields but also field paths can be referenced
from a path pattern. Fields mapped to the path pattern cannot be
repeated and must have a primitive (non-message) type.

Any fields in the request message which are not bound by the path
pattern automatically become (optional) HTTP query
parameters. Assume the following definition of the request message:


    service Messaging {
      rpc GetMessage(GetMessageRequest) returns (Message) {
        option (google.api.http).get = &#34;/v1/messages/{message_id}&#34;;
      }
    }
    message GetMessageRequest {
      message SubMessage {
        string subfield = 1;
      }
      string message_id = 1; // mapped to the URL
      int64 revision = 2;    // becomes a parameter
      SubMessage sub = 3;    // `sub.subfield` becomes a parameter
    }


This enables a HTTP JSON to RPC mapping as below:

HTTP | RPC
-----|-----
`GET /v1/messages/123456?revision=2&amp;sub.subfield=foo` | `GetMessage(message_id: &#34;123456&#34; revision: 2 sub: SubMessage(subfield: &#34;foo&#34;))`

Note that fields which are mapped to HTTP parameters must have a
primitive type or a repeated primitive type. Message types are not
allowed. In the case of a repeated type, the parameter can be
repeated in the URL, as in `...?param=A&amp;param=B`.

For HTTP method kinds which allow a request body, the `body` field
specifies the mapping. Consider a REST update method on the
message resource collection:


    service Messaging {
      rpc UpdateMessage(UpdateMessageRequest) returns (Message) {
        option (google.api.http) = {
          put: &#34;/v1/messages/{message_id}&#34;
          body: &#34;message&#34;
        };
      }
    }
    message UpdateMessageRequest {
      string message_id = 1; // mapped to the URL
      Message message = 2;   // mapped to the body
    }


The following HTTP JSON to RPC mapping is enabled, where the
representation of the JSON in the request body is determined by
protos JSON encoding:

HTTP | RPC
-----|-----
`PUT /v1/messages/123456 { &#34;text&#34;: &#34;Hi!&#34; }` | `UpdateMessage(message_id: &#34;123456&#34; message { text: &#34;Hi!&#34; })`

The special name `*` can be used in the body mapping to define that
every field not bound by the path template should be mapped to the
request body.  This enables the following alternative definition of
the update method:

    service Messaging {
      rpc UpdateMessage(Message) returns (Message) {
        option (google.api.http) = {
          put: &#34;/v1/messages/{message_id}&#34;
          body: &#34;*&#34;
        };
      }
    }
    message Message {
      string message_id = 1;
      string text = 2;
    }


The following HTTP JSON to RPC mapping is enabled:

HTTP | RPC
-----|-----
`PUT /v1/messages/123456 { &#34;text&#34;: &#34;Hi!&#34; }` | `UpdateMessage(message_id: &#34;123456&#34; text: &#34;Hi!&#34;)`

Note that when using `*` in the body mapping, it is not possible to
have HTTP parameters, as all fields not bound by the path end in
the body. This makes this option more rarely used in practice of
defining REST APIs. The common usage of `*` is in custom methods
which don&#39;t use the URL at all for transferring data.

It is possible to define multiple HTTP methods for one RPC by using
the `additional_bindings` option. Example:

    service Messaging {
      rpc GetMessage(GetMessageRequest) returns (Message) {
        option (google.api.http) = {
          get: &#34;/v1/messages/{message_id}&#34;
          additional_bindings {
            get: &#34;/v1/users/{user_id}/messages/{message_id}&#34;
          }
        };
      }
    }
    message GetMessageRequest {
      string message_id = 1;
      string user_id = 2;
    }


This enables the following two alternative HTTP JSON to RPC
mappings:

HTTP | RPC
-----|-----
`GET /v1/messages/123456` | `GetMessage(message_id: &#34;123456&#34;)`
`GET /v1/users/me/messages/123456` | `GetMessage(user_id: &#34;me&#34; message_id: &#34;123456&#34;)`

# Rules for HTTP mapping

The rules for mapping HTTP path, query parameters, and body fields
to the request message are as follows:

1. The `body` field specifies either `*` or a field path, or is
   omitted. If omitted, it indicates there is no HTTP request body.
2. Leaf fields (recursive expansion of nested messages in the
   request) can be classified into three types:
    (a) Matched in the URL template.
    (b) Covered by body (if body is `*`, everything except (a) fields;
        else everything under the body field)
    (c) All other fields.
3. URL query parameters found in the HTTP request are mapped to (c) fields.
4. Any body sent with an HTTP request can contain only (b) fields.

The syntax of the path template is as follows:

    Template = &#34;/&#34; Segments [ Verb ] ;
    Segments = Segment { &#34;/&#34; Segment } ;
    Segment  = &#34;*&#34; | &#34;**&#34; | LITERAL | Variable ;
    Variable = &#34;{&#34; FieldPath [ &#34;=&#34; Segments ] &#34;}&#34; ;
    FieldPath = IDENT { &#34;.&#34; IDENT } ;
    Verb     = &#34;:&#34; LITERAL ;

The syntax `*` matches a single path segment. The syntax `**` matches zero
or more path segments, which must be the last part of the path except the
`Verb`. The syntax `LITERAL` matches literal text in the path.

The syntax `Variable` matches part of the URL path as specified by its
template. A variable template must not contain other variables. If a variable
matches a single path segment, its template may be omitted, e.g. `{var}`
is equivalent to `{var=*}`.

If a variable contains exactly one path segment, such as `&#34;{var}&#34;` or
`&#34;{var=*}&#34;`, when such a variable is expanded into a URL path, all characters
except `[-_.~0-9a-zA-Z]` are percent-encoded. Such variables show up in the
Discovery Document as `{var}`.

If a variable contains one or more path segments, such as `&#34;{var=foo/*}&#34;`
or `&#34;{var=**}&#34;`, when such a variable is expanded into a URL path, all
characters except `[-_.~/0-9a-zA-Z]` are percent-encoded. Such variables
show up in the Discovery Document as `{&#43;var}`.

NOTE: While the single segment variable matches the semantics of
[RFC 6570](https://tools.ietf.org/html/rfc6570) Section 3.2.2
Simple String Expansion, the multi segment variable **does not** match
RFC 6570 Reserved Expansion. The reason is that the Reserved Expansion
does not expand special characters like `?` and `#`, which would lead
to invalid URLs.

NOTE: the field paths in variables and in the `body` must not refer to
repeated fields or map fields.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| selector | [string](#string) |  | Selects methods to which this rule applies.

Refer to [selector][google.api.DocumentationRule.selector] for syntax details. |
| get | [string](#string) |  | Used for listing and getting information about resources. |
| put | [string](#string) |  | Used for updating a resource. |
| post | [string](#string) |  | Used for creating a resource. |
| delete | [string](#string) |  | Used for deleting a resource. |
| patch | [string](#string) |  | Used for updating a resource. |
| custom | [CustomHttpPattern](#google.api.CustomHttpPattern) |  | The custom pattern is used for specifying an HTTP method that is not included in the `pattern` field, such as HEAD, or &#34;*&#34; to leave the HTTP method unspecified for this rule. The wild-card rule is useful for services that provide content to Web (HTML) clients. |
| body | [string](#string) |  | The name of the request field whose value is mapped to the HTTP body, or `*` for mapping all fields not captured by the path pattern to the HTTP body. NOTE: the referred field must not be a repeated field and must be present at the top-level of request message type. |
| response_body | [string](#string) |  | Optional. The name of the response field whose value is mapped to the HTTP body of response. Other response fields are ignored. When not set, the response message will be used as HTTP body of response. |
| additional_bindings | [HttpRule](#google.api.HttpRule) | repeated | Additional HTTP bindings for the selector. Nested bindings must not contain an `additional_bindings` field themselves (that is, the nesting may only be one level deep). |





 

 

 

 



<a name="item.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## item.proto
Item related messages. Strictly, not related directly to any transactions or even match results.


<a name="item.Address"></a>

### Address
Represents address (From and To) of an item


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| line_one | [string](#string) |  | Required. |
| city | [string](#string) |  | Required. |
| state | [string](#string) |  | Required. |
| country | [string](#string) |  | Required. |
| postal_code | [string](#string) |  | Required. |






<a name="item.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="item.ItemForNotificationMessage"></a>

### ItemForNotificationMessage
Represents minimum information of item required for insightful app notification


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| name | [string](#string) |  | Required. |
| owner_id | [string](#string) |  | Required. |
| non_owner_id | [string](#string) |  | Required. |
| end_date_epoch | [int64](#int64) |  | Required. |
| image_thumbnail | [string](#string) |  | Required. |






<a name="item.ItemIdentification"></a>

### ItemIdentification
Repesents a unique itemId


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  | Required. |






<a name="item.ItemMessage"></a>

### ItemMessage
Represents an item


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| end_date_epoch | [int64](#int64) |  |  |
| end_lat | [double](#double) |  |  |
| end_lon | [double](#double) |  |  |
| start_lat | [double](#double) |  |  |
| start_lon | [double](#double) |  |  |
| end_address | [Address](#item.Address) |  |  |
| start_address | [Address](#item.Address) |  |  |
| owner_id | [string](#string) |  |  |
| non_owner_id | [string](#string) |  |  |
| owner_type | [PersonType](#PersonType) |  |  |
| non_owner_type | [PersonType](#PersonType) |  |  |
| name | [string](#string) |  |  |
| category | [string](#string) |  |  |
| description | [string](#string) |  |  |
| images | [string](#string) | repeated |  |
| image_thumbnail | [string](#string) |  |  |
| length | [int32](#int32) |  |  |
| width | [int32](#int32) |  |  |
| height | [int32](#int32) |  |  |
| weight | [int32](#int32) |  |  |
| value | [int32](#int32) |  |  |
| dimension_unit | [DimensionUnit](#DimensionUnit) |  |  |
| weight_unit | [WeightUnit](#WeightUnit) |  |  |
| currency_unit | [CurrencyUnit](#CurrencyUnit) |  |  |






<a name="item.Response"></a>

### Response
Represents a ItemService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#item.Response.FieldsEntry) | repeated | Represents a response map |






<a name="item.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#item.Value) |  |  |






<a name="item.StringList"></a>

### StringList
Represents list of strings


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| list | [string](#string) | repeated | List of string |






<a name="item.UpdateItemMessage"></a>

### UpdateItemMessage
Represents mutable fields of an item


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| id | [string](#string) |  | Required. |
| description | [string](#string) |  | Required. |
| non_owner_id | [string](#string) |  | Required. |
| value | [int32](#int32) |  | Required. |
| end_time_epoch | [int64](#int64) |  | Required. |






<a name="item.Value"></a>

### Value
Represents a return value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_for_notification_message_value | [ItemForNotificationMessage](#item.ItemForNotificationMessage) |  | Minimum item info required for insightful app notification |
| string_list_value | [StringList](#item.StringList) |  | List of strings |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#item.Error) |  | Error value |
| null_value | [NullValue](#item.NullValue) |  | NULL value |





 


<a name="item.NullValue"></a>

### NullValue
NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |


 

 


<a name="item.ItemService"></a>

### ItemService
Service for Item handling.

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateItem | [ItemMessage](#item.ItemMessage) | [Response](#item.Response) | Creates a new item; details specified by `ItemMessage` (Unbounded). Also creates one entry in ItemPost collection corresponding to this item. This ItemPost and Item are strongly connected, i.e. any change in Item will be reflected in the corresponding fields in ItemPost. |
| UpdateItem | [UpdateItemMessage](#item.UpdateItemMessage) | [Response](#item.Response) | Updates an item. Correspondingly updates ItemPost as well. Returns non-null error.message if item with id does not exists. |
| DeleteItem | [ItemIdentification](#item.ItemIdentification) | [Response](#item.Response) | Deletes an item. Correspondingly deletes ItemPost as well. |
| GetItemName | [ItemIdentification](#item.ItemIdentification) | [Response](#item.Response) | Returns name of the item identified by its id |
| GetItemForNotification | [ItemIdentification](#item.ItemIdentification) | [Response](#item.Response) | Returns minimum item information identified by id required for sending insightful app notification to user. |

 



<a name="item_post.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## item_post.proto
ItemPost related messages.


<a name="itemPosts.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="itemPosts.ExpireItemPostMessage"></a>

### ExpireItemPostMessage
Represents an ItemId


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |






<a name="itemPosts.ItemPostIdentification"></a>

### ItemPostIdentification
Represents an itemId


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |






<a name="itemPosts.ItemPostMessage"></a>

### ItemPostMessage
Represents an ItemPostMessage


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| end_date_epoch | [int64](#int64) |  |  |
| end_lat | [double](#double) |  |  |
| end_lon | [double](#double) |  |  |
| start_lat | [double](#double) |  |  |
| start_lon | [double](#double) |  |  |
| owner_id | [string](#string) |  |  |
| non_owner_id | [string](#string) |  |  |
| owner_type | [PersonType](#PersonType) |  |  |
| non_owner_type | [PersonType](#PersonType) |  |  |
| status | [Status](#Status) |  |  |
| expired | [bool](#bool) |  |  |






<a name="itemPosts.ItemPostUpdateMessage"></a>

### ItemPostUpdateMessage
Represents mutable fields of ItemPost


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| non_owner_id | [string](#string) |  |  |
| end_time_epoch | [int64](#int64) |  |  |






<a name="itemPosts.Response"></a>

### Response
Represents a ItemPostService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#itemPosts.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="itemPosts.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#itemPosts.Value) |  |  |






<a name="itemPosts.StatusChangeToInRequestMessage"></a>

### StatusChangeToInRequestMessage
Represents an itemId and travelPlanId


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |






<a name="itemPosts.StatusChangeToNotFinalizedMessage"></a>

### StatusChangeToNotFinalizedMessage
Represents an itemId and travelPlanId


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |






<a name="itemPosts.UpdateStatusMessage"></a>

### UpdateStatusMessage
Represents a status update message


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| new_status | [Status](#Status) |  |  |






<a name="itemPosts.Value"></a>

### Value
Represents a return value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_post_value | [ItemPostMessage](#itemPosts.ItemPostMessage) |  | ItemPostMessage value |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#itemPosts.Error) |  | Error value |
| null_value | [NullValue](#itemPosts.NullValue) |  | NULL value |





 


<a name="itemPosts.NullValue"></a>

### NullValue
Represents a NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |


 

 


<a name="itemPosts.ItemPostService"></a>

### ItemPostService
Service for handling ItemPost

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateItemPost | [ItemPostMessage](#itemPosts.ItemPostMessage) | [Response](#itemPosts.Response) | Creates an ItemPost corresponding to an Item. Also creates a Job scheduled at item&#39;s endDate. |
| UpdateItemPost | [ItemPostUpdateMessage](#itemPosts.ItemPostUpdateMessage) | [Response](#itemPosts.Response) | Updates the mutable fields of ItemPost corresponding to an item. If item.endDate is updated, then it also updates the Job scheduled time. |
| DeleteItemPost | [ItemPostIdentification](#itemPosts.ItemPostIdentification) | [Response](#itemPosts.Response) | Deletes ItemPost and the corresponding Job scheduled at item.endDate. |
| ExpireItemPost | [ExpireItemPostMessage](#itemPosts.ExpireItemPostMessage) | [Response](#itemPosts.Response) | Expires ItemPost identified by itemId. Takes action based on current item status. If the status is NOT_FINALIZED -&gt; Just notify the sender and receiver, If IN_REQUEST -&gt; delete all RequestPost of this item and notify sender and receiver, If FINALIZED or ON_MOVE -&gt; delete all RequestPost of this item, expire item in AcceptedTransaction, finally notify sender,receiver and involved traveller |
| UpdateStatus | [UpdateStatusMessage](#itemPosts.UpdateStatusMessage) | [Response](#itemPosts.Response) | Updates status of ItemPost identified by itemId |
| CancelRequest | [StatusChangeToNotFinalizedMessage](#itemPosts.StatusChangeToNotFinalizedMessage) | [Response](#itemPosts.Response) | Deletes all Request post for itemId &amp; travelPlanId |
| RequestIn | [StatusChangeToInRequestMessage](#itemPosts.StatusChangeToInRequestMessage) | [Response](#itemPosts.Response) | Updates status of itemPost and travelPlanPost to IN_REQUEST and creates a new RequestPost |
| GetItemPostMessage | [ItemPostIdentification](#itemPosts.ItemPostIdentification) | [Response](#itemPosts.Response) | Returns ItemPost identified by itemId |

 



<a name="job.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## job.proto
Job related messages


<a name="jobs.CreateJobMessage"></a>

### CreateJobMessage
Message to create a job


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| name | [string](#string) |  | Name of the job |
| data | [string](#string) |  | Information associated with the job. Commonly itemId or travelPlanId |
| priority | [int32](#int32) |  | Priority of the Job on scaled of 1-10 |
| type | [int32](#int32) |  | Type of Job. 0 -&gt; normal, 1 -&gt; repeat |
| task_type | [int32](#int32) |  | Type of task of Job. 0 -&gt; Expiry, else -&gt; any other task |
| next_run_at | [int64](#int64) |  | Epoch of next run scheduled time of the job |
| repeat_after | [int64](#int64) |  | Only for Job with type -&gt; &#34;repeat&#34;. Represents after how much time the Job should schedule its nextRunAt |






<a name="jobs.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="jobs.JobMessage"></a>

### JobMessage
Message for Job updation and deletion


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| ids | [string](#string) | repeated | List of ids |
| next_run_ats | [int64](#int64) | repeated | List of next run at [Date] |






<a name="jobs.Response"></a>

### Response
Represents a NotificationsService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#jobs.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="jobs.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#jobs.Value) |  |  |






<a name="jobs.Value"></a>

### Value
Represents a return Value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#jobs.Error) |  | Error value |
| null_value | [NullValue](#jobs.NullValue) |  | NULL value |





 


<a name="jobs.NullValue"></a>

### NullValue
NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |


 

 


<a name="jobs.JobService"></a>

### JobService
Service for handling Job

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateJob | [CreateJobMessage](#jobs.CreateJobMessage) | [Response](#jobs.Response) | Creates a Job to run at a given time or periodically. Least count = 5000ms |
| UpdateJob | [JobMessage](#jobs.JobMessage) | [Response](#jobs.Response) | Updates a job with its `nextRunAt` time identified by its id. |
| DeleteJob | [JobMessage](#jobs.JobMessage) | [Response](#jobs.Response) | Deletes a Job identified by its id. |

 



<a name="notifications.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## notifications.proto
Notification related messages


<a name="notifications.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="notifications.NotificationMessage"></a>

### NotificationMessage
Notification Message. High priority by default


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| send_to | [string](#string) | repeated | List of userIds |
| headings | [NotificationMessage.HeadingsEntry](#notifications.NotificationMessage.HeadingsEntry) | repeated | Locale-wise map { &#39;en&#39;: &#39;message in english&#39;, &#39;fr&#39;: &#39;Message in french&#39; } |
| contents | [NotificationMessage.ContentsEntry](#notifications.NotificationMessage.ContentsEntry) | repeated | Locale-wise map { &#39;en&#39;: &#39;message in english&#39;, &#39;fr&#39;: &#39;Message in french&#39; } |
| json_stringified_payload | [string](#string) |  | Json payload but stringified |
| big_picture | [string](#string) |  | Android big picture url |






<a name="notifications.NotificationMessage.ContentsEntry"></a>

### NotificationMessage.ContentsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [string](#string) |  |  |






<a name="notifications.NotificationMessage.HeadingsEntry"></a>

### NotificationMessage.HeadingsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [string](#string) |  |  |






<a name="notifications.OsNotificationReschedule"></a>

### OsNotificationReschedule
Message for rescheduling an already scheduled One Signal notification


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| os_notification_id | [string](#string) |  |  |
| new_time_epoch | [int64](#int64) |  |  |






<a name="notifications.Response"></a>

### Response
Represents a CompletedTransactionService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#notifications.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="notifications.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#notifications.Value) |  |  |






<a name="notifications.Value"></a>

### Value
Represents a return Value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#notifications.Error) |  | Error value |
| null_value | [NullValue](#notifications.NullValue) |  | NULL value |





 


<a name="notifications.NullValue"></a>

### NullValue
NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |


 

 


<a name="notifications.NotificationService"></a>

### NotificationService
Service for handling Notifications and SMSs

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| SendNotificationNow | [NotificationMessage](#notifications.NotificationMessage) | [Response](#notifications.Response) | Dispatches a new notification. Accepts a list of userIds, asks User service for corresponding One Signal tokens. If one signal token is unavailable then it grabs the phone number of that user and send an SMS (like a fallback). |

 



<a name="pending_rating.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## pending_rating.proto
Pending rating related messages


<a name="pendingRatings.DeletePendingRatingMessage"></a>

### DeletePendingRatingMessage
Message to delete a PendingRating


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| from_user_id | [string](#string) |  |  |
| to_user_id | [string](#string) |  |  |
| completed_transaction_id | [string](#string) |  |  |






<a name="pendingRatings.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="pendingRatings.PendingRatingsForCTIdMessage"></a>

### PendingRatingsForCTIdMessage
Message to create 6 pending rating documents for a given CompletedTransaction


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| completed_on | [int64](#int64) |  | Timestamp |
| completed_transaction_id | [string](#string) |  |  |
| owner_id | [string](#string) |  |  |
| non_owner_id | [string](#string) |  |  |
| traveller_id | [string](#string) |  |  |
| item_name | [string](#string) |  |  |






<a name="pendingRatings.Response"></a>

### Response
Represents a CompletedTransactionService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#pendingRatings.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="pendingRatings.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#pendingRatings.Value) |  |  |






<a name="pendingRatings.Value"></a>

### Value
Represents a return Value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#pendingRatings.Error) |  | Error value |
| null_value | [NullValue](#pendingRatings.NullValue) |  | NULL value |





 


<a name="pendingRatings.NullValue"></a>

### NullValue
NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |


 

 


<a name="pendingRatings.PendingRatingService"></a>

### PendingRatingService
Service for handling Pending Rating

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreatePendingRatingsForCTId | [PendingRatingsForCTIdMessage](#pendingRatings.PendingRatingsForCTIdMessage) | [Response](#pendingRatings.Response) | Create 6 pending rating documents for 3 involved users in a CompletedTransaction |
| DeletePendingRating | [DeletePendingRatingMessage](#pendingRatings.DeletePendingRatingMessage) | [Response](#pendingRatings.Response) | Deletes a pending rating |

 



<a name="rating.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## rating.proto
Rating related messages


<a name="ratings.CreateRatingMessage"></a>

### CreateRatingMessage
Message to create Rating


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| completed_on | [int64](#int64) |  |  |
| from_user_id | [string](#string) |  |  |
| to_user_id | [string](#string) |  |  |
| text | [string](#string) |  |  |
| completed_transaction_id | [string](#string) |  |  |
| rating | [double](#double) |  |  |
| personalityStructure | [PersonalityStructure](#PersonalityStructure) |  |  |
| recommended | [bool](#bool) |  |  |






<a name="ratings.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="ratings.Response"></a>

### Response
Represents a CompletedTransactionService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#ratings.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="ratings.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#ratings.Value) |  |  |






<a name="ratings.Value"></a>

### Value
Represents a return Value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#ratings.Error) |  | Error value |
| null_value | [NullValue](#ratings.NullValue) |  | NULL value |





 


<a name="ratings.NullValue"></a>

### NullValue
NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |


 

 


<a name="ratings.RatingService"></a>

### RatingService
Service for handling Ratings

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateRating | [CreateRatingMessage](#ratings.CreateRatingMessage) | [Response](#ratings.Response) | Creates a Rating document. Deletes its corresponding PendingRating and updates the Account of the user who has received the rating. |

 



<a name="request_post.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## request_post.proto
RequestPost related messages


<a name="requestPost.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="requestPost.IntList"></a>

### IntList
List of Integers


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| int_list | [int64](#int64) | repeated | List of integers |






<a name="requestPost.RequestPostMessage"></a>

### RequestPostMessage
Message to create a new RequestPost


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |
| requested_by_traveller | [bool](#bool) |  |  |






<a name="requestPost.Response"></a>

### Response
Represents a CompletedTransactionService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#requestPost.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="requestPost.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#requestPost.Value) |  |  |






<a name="requestPost.StatusChangeToFinalizedMessage"></a>

### StatusChangeToFinalizedMessage
Message to identify unique RequestPost


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |






<a name="requestPost.UpdateAllStatusesOf"></a>

### UpdateAllStatusesOf
Message to assign new statuses to item and travelPlan respectively.


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |
| new_item_status | [Status](#Status) |  |  |
| new_travel_plan_status | [Status](#Status) |  |  |






<a name="requestPost.Value"></a>

### Value
Represents a response Value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#requestPost.Error) |  | Error value |
| null_value | [NullValue](#requestPost.NullValue) |  | NULL value |
| int_list_value | [IntList](#requestPost.IntList) |  | List of integers |





 


<a name="requestPost.NullValue"></a>

### NullValue
NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |


 

 


<a name="requestPost.RequestPostService"></a>

### RequestPostService
Service to handle RequestPost

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateRequestPost | [RequestPostMessage](#requestPost.RequestPostMessage) | [Response](#requestPost.Response) | Creates a new RequestPost. Gathers item and travelplan info from Item and TravelPlan respectively. Throws an error if it exists already. |
| GetRequestPostCount | [RequestPostMessage](#requestPost.RequestPostMessage) | [Response](#requestPost.Response) | Returns a integer count of all RequestPost individually for a given itemId and a given travelPlanId |
| GetRequestPostCountAndSetStatus | [RequestPostMessage](#requestPost.RequestPostMessage) | [Response](#requestPost.Response) | NOT overridden yet |
| DeleteRequestPost | [RequestPostMessage](#requestPost.RequestPostMessage) | [Response](#requestPost.Response) | Deletes a request post identified by itemId and travelPlanId |
| DeleteAllRequestPost | [RequestPostMessage](#requestPost.RequestPostMessage) | [Response](#requestPost.Response) | Deletes all RequestPost individually for a given itemId and a given travelPlanId |
| UpdateAllStatuses | [UpdateAllStatusesOf](#requestPost.UpdateAllStatusesOf) | [Response](#requestPost.Response) | Updates statuses of all RequestPost individually for a given itemId and a given travelPlanId to a given new status. |
| StatusChangeToFinalized | [StatusChangeToFinalizedMessage](#requestPost.StatusChangeToFinalizedMessage) | [Response](#requestPost.Response) | Handles status change to FINALIZED. Updates statuses of all RequestPost individually for a given itemId and a given travelPlanId to FINALIZED, updates ItemPost and travelPlanPost &#39;s status to FINALIZED, creates a new AcceptedTransaction and finally deletes this RequestPost. |

 



<a name="travel_plan_post.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## travel_plan_post.proto
TravelPlanPost related message


<a name="travelPlanPosts.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="travelPlanPosts.ExpireTravelPlanPostMessage"></a>

### ExpireTravelPlanPostMessage
Represents a travelPlanId


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| travel_plan_id | [string](#string) |  |  |






<a name="travelPlanPosts.Response"></a>

### Response
Represents a ItemPostService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#travelPlanPosts.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="travelPlanPosts.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#travelPlanPosts.Value) |  |  |






<a name="travelPlanPosts.StatusChangeToInRequestMessage"></a>

### StatusChangeToInRequestMessage
Represents an itemId and travelPlanId


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |






<a name="travelPlanPosts.StatusChangeToNotFinalizedMessage"></a>

### StatusChangeToNotFinalizedMessage
Represents an itemId and travelPlanId


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| item_id | [string](#string) |  |  |
| travel_plan_id | [string](#string) |  |  |






<a name="travelPlanPosts.TravelPlanPostIdentification"></a>

### TravelPlanPostIdentification
Represents a travelPlanId


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| travel_plan_id | [string](#string) |  |  |






<a name="travelPlanPosts.TravelPlanPostMessage"></a>

### TravelPlanPostMessage
Represents a TravelPlanPostMessage


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| travel_plan_id | [string](#string) |  |  |
| end_date_epoch | [int64](#int64) |  |  |
| start_date_epoch | [int64](#int64) |  |  |
| end_lat | [double](#double) |  |  |
| end_lon | [double](#double) |  |  |
| start_lat | [double](#double) |  |  |
| start_lon | [double](#double) |  |  |
| traveller_id | [string](#string) |  |  |
| status | [Status](#Status) |  |  |
| expired | [bool](#bool) |  |  |






<a name="travelPlanPosts.TravelPlanPostUpdateMessage"></a>

### TravelPlanPostUpdateMessage
Represents mutable fields of TravelPlanPost


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| travel_plan_id | [string](#string) |  |  |
| start_time_epoch | [int64](#int64) |  |  |
| end_time_epoch | [int64](#int64) |  |  |






<a name="travelPlanPosts.UpdateStatusMessage"></a>

### UpdateStatusMessage
Represents a status update message


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| travel_plan_id | [string](#string) |  |  |
| new_status | [Status](#Status) |  |  |






<a name="travelPlanPosts.Value"></a>

### Value
Represents a return value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| travel_plan_post_value | [TravelPlanPostMessage](#travelPlanPosts.TravelPlanPostMessage) |  | TravelPlanPostMessage value |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#travelPlanPosts.Error) |  | Error value |
| null_value | [NullValue](#travelPlanPosts.NullValue) |  | NULL value |





 


<a name="travelPlanPosts.NullValue"></a>

### NullValue
Represents a NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |


 

 


<a name="travelPlanPosts.TravelPlanPostService"></a>

### TravelPlanPostService
Service to handle TravelPlanPost

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateTravelPlanPost | [TravelPlanPostMessage](#travelPlanPosts.TravelPlanPostMessage) | [Response](#travelPlanPosts.Response) | Creates a TravelPlanPost corresponding to a TravelPlan. Also creates two Jobs scheduled at travelPlan&#39;s endDate and startDate. |
| UpdateTravelPlanPost | [TravelPlanPostUpdateMessage](#travelPlanPosts.TravelPlanPostUpdateMessage) | [Response](#travelPlanPosts.Response) | Updates the mutable fields of TravelPlanPost corresponding to a TravelPlan. If travelPlan.endDate etc. is updated, then it also updates the respective Job scheduled time. |
| DeleteTravelPlanPost | [TravelPlanPostIdentification](#travelPlanPosts.TravelPlanPostIdentification) | [Response](#travelPlanPosts.Response) | Deletes TravelPlanPost and the corresponding Jobs scheduled at travelPlan.endDate and travelPlan.startDate. |
| GetTravelPlanPostMessage | [TravelPlanPostIdentification](#travelPlanPosts.TravelPlanPostIdentification) | [Response](#travelPlanPosts.Response) | Returns TravelPlanPost identified by travelPlanId |
| RequestIn | [StatusChangeToInRequestMessage](#travelPlanPosts.StatusChangeToInRequestMessage) | [Response](#travelPlanPosts.Response) | Updates status of itemPost and travelPlanPost to IN_REQUEST and creates a new RequestPost |
| CancelRequest | [StatusChangeToNotFinalizedMessage](#travelPlanPosts.StatusChangeToNotFinalizedMessage) | [Response](#travelPlanPosts.Response) | Deletes all Request post for itemId &amp; travelPlanId |
| UpdateStatus | [UpdateStatusMessage](#travelPlanPosts.UpdateStatusMessage) | [Response](#travelPlanPosts.Response) | Updates status of TravelPlanPost identified by travelPlanId |
| ExpireTravelPlanPost | [ExpireTravelPlanPostMessage](#travelPlanPosts.ExpireTravelPlanPostMessage) | [Response](#travelPlanPosts.Response) | Expires TravelPlanPost identified by travelPlanId. Takes action based on current travelPlan status. If the status is NOT_FINALIZED -&gt; Just notify the traveller, If IN_REQUEST -&gt; delete all RequestPost of this travelPlan and notify traveller, If FINALIZED or ON_MOVE -&gt; delete all RequestPost of this travelPlan, expire travelPlan in AcceptedTransaction, finally notify traveller and involved sender,receiver |

 



<a name="travel_plans.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## travel_plans.proto
Travel plan related messages.


<a name="travelPlans.Address"></a>

### Address
Represents address (From and to)


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| line_one | [string](#string) |  |  |
| city | [string](#string) |  |  |
| state | [string](#string) |  |  |
| country | [string](#string) |  |  |
| postal_code | [string](#string) |  |  |






<a name="travelPlans.Error"></a>

### Error



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="travelPlans.Response"></a>

### Response
Represents a TravelPlanService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#travelPlans.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="travelPlans.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#travelPlans.Value) |  |  |






<a name="travelPlans.TravelPlanForNotificationMessage"></a>

### TravelPlanForNotificationMessage
Minimum information of travel plan required for insightful in-app notification


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| from_to | [string](#string) |  |  |
| traveller_id | [string](#string) |  |  |
| start_time_epoch | [int64](#int64) |  |  |
| end_date_epoch | [int64](#int64) |  |  |






<a name="travelPlans.TravelPlanIdentification"></a>

### TravelPlanIdentification
Represents unique travel plan id


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| travel_plan_id | [string](#string) |  |  |






<a name="travelPlans.TravelPlanMessage"></a>

### TravelPlanMessage
Represents travel plan message


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| end_date_epoch | [int64](#int64) |  |  |
| start_date_epoch | [int64](#int64) |  |  |
| end_lat | [double](#double) |  |  |
| end_lon | [double](#double) |  |  |
| start_lat | [double](#double) |  |  |
| start_lon | [double](#double) |  |  |
| end_address | [Address](#travelPlans.Address) |  |  |
| start_address | [Address](#travelPlans.Address) |  |  |
| traveller_id | [string](#string) |  |  |
| description | [string](#string) |  |  |
| mode_of_travel | [ModeOfTravel](#ModeOfTravel) |  |  |






<a name="travelPlans.UpdateTravelPlanMessage"></a>

### UpdateTravelPlanMessage
Mutable fields of travel plan


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| id | [string](#string) |  |  |
| description | [string](#string) |  |  |
| mode_of_travel | [ModeOfTravel](#ModeOfTravel) |  |  |
| start_time_epoch | [int64](#int64) |  |  |
| end_time_epoch | [int64](#int64) |  |  |






<a name="travelPlans.Value"></a>

### Value
Return Value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| travel_plan_for_notification_message_value | [TravelPlanForNotificationMessage](#travelPlans.TravelPlanForNotificationMessage) |  | Minimum information of travel plan required for insightful in-app notification |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#travelPlans.Error) |  | Error value |
| null_value | [NullValue](#travelPlans.NullValue) |  | NULL value |





 


<a name="travelPlans.NullValue"></a>

### NullValue
NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |


 

 


<a name="travelPlans.TravelPlanService"></a>

### TravelPlanService
Service for handling Travel plans

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateTravelPlan | [TravelPlanMessage](#travelPlans.TravelPlanMessage) | [Response](#travelPlans.Response) | Creates a new travelPlan; details specified by `TravelPlanMessage` (Unbounded). Also creates one entry in TravelPlanPost collection corresponding to this travelPlan. This TravelPlanPost and TravelPlan are strongly connected, i.e. any change in TravelPlan will be reflected in the corresponding fields in TravelPlanPost. |
| UpdateTravelPlan | [UpdateTravelPlanMessage](#travelPlans.UpdateTravelPlanMessage) | [Response](#travelPlans.Response) | Updates an travelPlan. Correspondingly updates TravelPlanPost as well. Returns non-null error.message if travelPlan with id does not exists. |
| DeleteTravelPlan | [TravelPlanIdentification](#travelPlans.TravelPlanIdentification) | [Response](#travelPlans.Response) | Deletes an travelPlan. Correspondingly deletes TravelPlanPost as well. |
| TravelPlanForNotification | [TravelPlanIdentification](#travelPlans.TravelPlanIdentification) | [Response](#travelPlans.Response) | Returns minimum travelPlan information identified by id required for sending insightful app notification to user. |

 



<a name="user.proto"></a>
<p align="right"><a href="#top">Top</a></p>

## user.proto
User related messages.


<a name="user.Address"></a>

### Address
Represents a user&#39;s address


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| house_number | [string](#string) |  | Required. |
| street_number | [string](#string) |  |  |
| city | [string](#string) |  | Required. |
| state | [string](#string) |  | Required. |
| country | [string](#string) |  | Required. |
| pincode | [int32](#int32) |  | Required. |






<a name="user.Error"></a>

### Error
Represents an error


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| method | [string](#string) |  | The method in which this error occurred. |
| message | [string](#string) |  | Localized error message |
| metadata | [string](#string) |  | Meta information required for debugging etc. |






<a name="user.NewRatingFeatureMessage"></a>

### NewRatingFeatureMessage
Message to add a new rating to User&#39;s profile and Account. See UserService.AggregateRatingFeatures


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| user_id | [string](#string) |  | Required. UserId of user |
| rating | [double](#double) |  | Required. User rating |
| recommended | [bool](#bool) |  | Required. Is this user recommended by the user who gave this rating |
| delta_trust_factor | [int32](#int32) |  | Required. Equivalent delta in trust factor of this user |






<a name="user.OsTokensMessage"></a>

### OsTokensMessage
Represents List of One Signal tokens of Users. See UserService.GetUsersOsTokens


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| os_tokens | [string](#string) | repeated | Required. List of One Signal tokens |






<a name="user.Personal"></a>

### Personal
Represents User&#39;s personal fields


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| name | [string](#string) |  | Required. Concatenation of first_name, last_name as &#34;$first_name $last_name&#34; |
| first_name | [string](#string) |  | Required. |
| last_name | [string](#string) |  | Required. |
| gender | [Personal.Gender](#user.Personal.Gender) |  | Required. |
| image_url | [string](#string) |  | Required. |
| image_thumbnail_url | [string](#string) |  | Required. |
| mobile | [string](#string) |  | Required. Ex: 7081103173 |
| country_code | [string](#string) |  | Required. Ex: 91, 1 |
| email | [string](#string) |  |  |
| about_me | [string](#string) |  |  |
| address | [Address](#user.Address) |  |  |
| year_of_birth | [int32](#int32) |  | Default = 0 |
| number_of_fb_friends | [int32](#int32) |  | Required. Default = 0 |
| number_of_google_conns | [int32](#int32) |  | Required. Default = 0 |
| number_of_linkedIn_conns | [int32](#int32) |  | Required. Default = 0 |
| aadhaar_number | [string](#string) |  | 12 digit string |
| aadhaar_doc_url | [string](#string) |  | Firebase Storage File URL |






<a name="user.Response"></a>

### Response
Represents a UserService response


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| fields | [Response.FieldsEntry](#user.Response.FieldsEntry) | repeated | Map of `kind` Value |






<a name="user.Response.FieldsEntry"></a>

### Response.FieldsEntry



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| key | [string](#string) |  |  |
| value | [Value](#user.Value) |  |  |






<a name="user.UpdateUserFields"></a>

### UpdateUserFields
Represents fields which are mutable for a User


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| id | [string](#string) |  | Required. UserId |
| image_url | [string](#string) |  | Required. Firebase Storage URL |
| first_name | [string](#string) |  | Required. |
| last_name | [string](#string) |  | Required. |
| gender | [string](#string) |  | Required. |
| year_of_birth | [int32](#int32) |  |  |
| about_me | [string](#string) |  |  |
| email | [string](#string) |  |  |
| address | [Address](#user.Address) |  |  |
| aadhaar_number | [string](#string) |  |  |






<a name="user.User"></a>

### User
Represents a User


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| id | [string](#string) |  | Required. UserId |
| os_token | [string](#string) |  | One Signal token. Required for sending app notifications |
| registered | [bool](#bool) |  | Required. Whether this User is registered or is added just as non-owner by some other user |
| exists | [bool](#bool) |  | Required. Eq. deleted |
| trust_factor | [int32](#int32) |  | Required. User&#39;s aggregated trust factor points |
| number_of_recommendations | [int32](#int32) |  | Required. Number of recommendations received by this user |
| number_of_authorisations | [int32](#int32) |  | Required. |
| number_of_ratings | [int32](#int32) |  | Required. |
| rating | [double](#double) |  | Required. |
| personal | [Personal](#user.Personal) |  | Required. Personal object |
| verifications | [Verifications](#user.Verifications) |  | Required. Verifications object |






<a name="user.UserAccountPart"></a>

### UserAccountPart
Represents part of User&#39;s Account which is aggregated from all of ratings and reviews


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| number_of_recommendations | [int32](#int32) |  | Required. |
| number_of_authorisations | [int32](#int32) |  | Required. |
| number_of_ratings | [int32](#int32) |  | Required. |
| rating | [double](#double) |  | Required. |






<a name="user.UserIdentification"></a>

### UserIdentification
Represents a userId


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| user_id | [string](#string) |  | Required. |






<a name="user.UserIdentifications"></a>

### UserIdentifications
Represents List of UserIds. See UserService.GetUsersOsTokens


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| user_ids | [string](#string) | repeated | Required. |






<a name="user.UsersMobileNumber"></a>

### UsersMobileNumber
Message to Create or Get a User. See UserService.CreateUser


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| mobile | [string](#string) |  | Required. User&#39;s mobile number. Ex: &#43;917081130173 |
| return_only_id | [bool](#bool) |  | Required. Whether to return only UserId or User Data |






<a name="user.Value"></a>

### Value
Represents a return value


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| user_account_part_value | [UserAccountPart](#user.UserAccountPart) |  | Account info of user from user&#39;s document |
| os_tokens_value | [OsTokensMessage](#user.OsTokensMessage) |  | List of One Signal tokens |
| user_value | [User](#user.User) |  | User value |
| string_value | [string](#string) |  | String value |
| bool_value | [bool](#bool) |  | Boolean value |
| error_value | [Error](#user.Error) |  | Error value |
| null_value | [NullValue](#user.NullValue) |  | NULL value |






<a name="user.Verifications"></a>

### Verifications
Represents user&#39;s verified/unverified fields


| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| aadhaar | [bool](#bool) |  |  |
| address | [bool](#bool) |  |  |
| email | [bool](#bool) |  |  |
| facebook | [bool](#bool) |  |  |
| gender | [bool](#bool) |  |  |
| linkedIn | [bool](#bool) |  |  |
| name | [bool](#bool) |  |  |
| year_of_birth | [bool](#bool) |  |  |
| mobile | [bool](#bool) |  |  |





 


<a name="user.NullValue"></a>

### NullValue
Represents a NULL value

| Name | Number | Description |
| ---- | ------ | ----------- |
| NULL_VALUE | 0 |  |



<a name="user.Personal.Gender"></a>

### Personal.Gender
Represents user&#39;s gender

| Name | Number | Description |
| ---- | ------ | ----------- |
| M | 0 | Male |
| F | 1 | Female |
| O | 3 | Other |
| NR | 4 | NotAvailable/NotRecognized |


 

 


<a name="user.UserService"></a>

### UserService
Service for handling User.

| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| CreateUser | [UsersMobileNumber](#user.UsersMobileNumber) | [Response](#user.Response) | Used to create a user. Also creates a document in Account to store RatingStructure and PersonalityStructure indexed against userId. If `return_only_id` is set `true`, it returns only `UserId` otherwise a Response with `User` as data. Returns a non-null error.message if user already exists. |
| UpdateUser | [UpdateUserFields](#user.UpdateUserFields) | [Response](#user.Response) | Used to update a user. `UpdateUserFields` every field is required. Returns a non-null error.message if user does not exists. |
| GetUserAccountPart | [UserIdentification](#user.UserIdentification) | [Response](#user.Response) | Returns `UserAccountPart` for a given User. Returns a non-null error.message if user does not exists. |
| GetUsersOsTokens | [UserIdentifications](#user.UserIdentifications) | [Response](#user.Response) | Returns list of One Signal tokens for a given list of User Ids. If One Signal token of a user is null, the it returns phone number (like &#43;917081130173) of that user so as to send MSG91 SMS. |
| AggregateRatingFeatures | [NewRatingFeatureMessage](#user.NewRatingFeatureMessage) | [Response](#user.Response) | Used to add a new rating to user&#39;s profile and account when a transaction completes. |

 



## Scalar Value Types

| .proto Type | Notes | C++ Type | Java Type | Python Type |
| ----------- | ----- | -------- | --------- | ----------- |
| <a name="double" /> double |  | double | double | float |
| <a name="float" /> float |  | float | float | float |
| <a name="int32" /> int32 | Uses variable-length encoding. Inefficient for encoding negative numbers – if your field is likely to have negative values, use sint32 instead. | int32 | int | int |
| <a name="int64" /> int64 | Uses variable-length encoding. Inefficient for encoding negative numbers – if your field is likely to have negative values, use sint64 instead. | int64 | long | int/long |
| <a name="uint32" /> uint32 | Uses variable-length encoding. | uint32 | int | int/long |
| <a name="uint64" /> uint64 | Uses variable-length encoding. | uint64 | long | int/long |
| <a name="sint32" /> sint32 | Uses variable-length encoding. Signed int value. These more efficiently encode negative numbers than regular int32s. | int32 | int | int |
| <a name="sint64" /> sint64 | Uses variable-length encoding. Signed int value. These more efficiently encode negative numbers than regular int64s. | int64 | long | int/long |
| <a name="fixed32" /> fixed32 | Always four bytes. More efficient than uint32 if values are often greater than 2^28. | uint32 | int | int |
| <a name="fixed64" /> fixed64 | Always eight bytes. More efficient than uint64 if values are often greater than 2^56. | uint64 | long | int/long |
| <a name="sfixed32" /> sfixed32 | Always four bytes. | int32 | int | int |
| <a name="sfixed64" /> sfixed64 | Always eight bytes. | int64 | long | int/long |
| <a name="bool" /> bool |  | bool | boolean | boolean |
| <a name="string" /> string | A string must always contain UTF-8 encoded or 7-bit ASCII text. | string | String | str/unicode |
| <a name="bytes" /> bytes | May contain any arbitrary sequence of bytes. | string | ByteString | str |
