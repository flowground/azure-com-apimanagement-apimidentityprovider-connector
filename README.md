# ![LOGO](logo.png) ApiManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApiManagementClient API (version 2016-10-10).

Generated from: https://api.apis.guru/v2/specs/azure.com/apimanagement-apimidentityprovider/2016-10-10/swagger.json<br/>
Generated at: 2019-05-07T17:37:09+03:00

## API Description

Use these REST APIs for performing operations on Identity Provider entity associated with your Azure API Management deployment. Setting up an external Identity Provider for authentication can help you manage the developer portal logins using the OAuth2 flow.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists a collection of Identity Provider configured in the specified service instance.

*Tags:* `IdentityProvider`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Deletes the specified identity provider configuration.

*Tags:* `IdentityProvider`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `identityProviderName` - _required_ - Identity Provider Type identifier.
    Possible values: facebook, google, microsoft, twitter, aad, aadB2C.
* `If-Match` - _required_ - The entity state (Etag) version of the backend to delete. A value of "*" can be used for If-Match to unconditionally apply the operation.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the configuration details of the identity Provider configured in specified service instance.

*Tags:* `IdentityProvider`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `identityProviderName` - _required_ - Identity Provider Type identifier.
    Possible values: facebook, google, microsoft, twitter, aad, aadB2C.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Updates an existing IdentityProvider configuration.

*Tags:* `IdentityProviders`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `identityProviderName` - _required_ - Identity Provider Type identifier.
    Possible values: facebook, google, microsoft, twitter, aad, aadB2C.
* `If-Match` - _required_ - The entity state (Etag) version of the identity provider configuration to update. A value of "*" can be used for If-Match to unconditionally apply the operation.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or Updates the IdentityProvider configuration.

*Tags:* `IdentityProvider`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `identityProviderName` - _required_ - Identity Provider Type identifier.
    Possible values: facebook, google, microsoft, twitter, aad, aadB2C.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-apimanagement-apimidentityprovider-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
