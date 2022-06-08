# Making Calls with Postman

## What is Postman?

[Postman](https://www.postman.com) is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster.

## Calling the Rest API with Postman

To make testing of the API easier we have created a Postman collection. This can be downloaded from our Github repository [here](Mobius%20Engine%20API.postman\_collection.json). Import this collection into Postman to start making API calls to your **Mobius**Flow**® Engine** instance.

{% hint style="info" %}
All calls have been configured to use _**localhost**_ on port _**9081.**_** ** Adjust these and the call parameters and body to suit your setup.
{% endhint %}

### Authorization

The calls in the collection inherit their authorization credentials from the collection parent. You will need to get an access token using the **Login** call in the **Auth** folder and update the token in the collection parent before making any other calls.
