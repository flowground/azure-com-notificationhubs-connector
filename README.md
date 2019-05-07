# ![LOGO](logo.png) NotificationHubsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the NotificationHubsManagementClient API (version 2017-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/notificationhubs/2017-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:34+03:00

## API Description

Azure NotificationHub client

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available NotificationHubs REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Checks the availability of the given service namespace across all Azure subscriptions. This is useful because the domain name is created based on the service namespace name.

*Tags:* `Namespaces`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all the available namespaces within the subscription irrespective of the resourceGroups.

*Tags:* `Namespaces`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists the available namespaces within a resourceGroup.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group. If resourceGroupName value is null the method lists all the namespaces within subscription
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an existing namespace. This operation also removes all associated notificationHubs under the namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Returns the description for the specified namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Patches the existing namespace

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates/Updates a service namespace. Once created, this namespace's resource manifest is immutable. This operation is idempotent.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the authorization rules for a namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a namespace authorization rule

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `authorizationRuleName` - _required_ - Authorization Rule Name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an authorization rule for a namespace by name.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name
* `authorizationRuleName` - _required_ - Authorization rule name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates an authorization rule for a namespace

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `authorizationRuleName` - _required_ - Authorization Rule Name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the Primary and Secondary ConnectionStrings to the namespace

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `authorizationRuleName` - _required_ - The connection string of the namespace for the specified authorizationRule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates the Primary/Secondary Keys to the Namespace Authorization Rule

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `authorizationRuleName` - _required_ - The connection string of the namespace for the specified authorizationRule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Checks the availability of the given notificationHub in a namespace.

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists the notification hubs associated with a namespace.

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a notification hub associated with a namespace.

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `notificationHubName` - _required_ - The notification hub name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists the notification hubs associated with a namespace.

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `notificationHubName` - _required_ - The notification hub name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Patch a NotificationHub in a namespace.

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `notificationHubName` - _required_ - The notification hub name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates/Update a NotificationHub in a namespace.

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `notificationHubName` - _required_ - The notification hub name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the authorization rules for a NotificationHub.

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name
* `notificationHubName` - _required_ - The notification hub name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a notificationHub authorization rule

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `notificationHubName` - _required_ - The notification hub name.
* `authorizationRuleName` - _required_ - Authorization Rule Name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an authorization rule for a NotificationHub by name.

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name
* `notificationHubName` - _required_ - The notification hub name.
* `authorizationRuleName` - _required_ - authorization rule name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates/Updates an authorization rule for a NotificationHub

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `notificationHubName` - _required_ - The notification hub name.
* `authorizationRuleName` - _required_ - Authorization Rule Name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the Primary and Secondary ConnectionStrings to the NotificationHub

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `notificationHubName` - _required_ - The notification hub name.
* `authorizationRuleName` - _required_ - The connection string of the NotificationHub for the specified authorizationRule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates the Primary/Secondary Keys to the NotificationHub Authorization Rule

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `notificationHubName` - _required_ - The notification hub name.
* `authorizationRuleName` - _required_ - The connection string of the NotificationHub for the specified authorizationRule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### test send a push notification

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `notificationHubName` - _required_ - The notification hub name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists the PNS Credentials associated with a notification hub .

*Tags:* `NotificationHubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `namespaceName` - _required_ - The namespace name.
* `notificationHubName` - _required_ - The notification hub name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-notificationhubs-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
