# ![LOGO](logo.png) HanaManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the HanaManagementClient API (version 2017-11-03-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/hanaonazure/2017-11-03-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:11+03:00

## API Description

The SAP HANA on Azure Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets a list of SAP HANA management operations.

*Tags:* `HanaOnAzure`

#### Input Parameters
* `api-version` - _required_ - Client API version.

### Gets a list of SAP HANA instances in the specified subscription.

> Gets a list of SAP HANA instances in the specified subscription. The operations returns various properties of each SAP HANA on Azure instance.

*Tags:* `HanaOnAzure`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription ID which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a list of SAP HANA instances in the specified subscription and the resource group.

> Gets a list of SAP HANA instances in the specified subscription and the resource group. The operations returns various properties of each SAP HANA on Azure instance.

*Tags:* `HanaOnAzure`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription ID which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.

### Gets properties of a SAP HANA instance.

> Gets properties of a SAP HANA instance for the specified subscription, resource group, and instance name.

*Tags:* `HanaOnAzure`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription ID which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `hanaInstanceName` - _required_ - Name of the SAP HANA on Azure instance.

### Patches the Tags field of a SAP HANA instance.

> Patches the Tags field of a SAP HANA instance for the specified subscription, resource group, and instance name.

*Tags:* `HanaOnAzure`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription ID which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `hanaInstanceName` - _required_ - Name of the SAP HANA on Azure instance.

### The operation to restart a SAP HANA instance.

*Tags:* `HanaOnAzure`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription ID which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `hanaInstanceName` - _required_ - Name of the SAP HANA on Azure instance.

## License

**flow**ground :- Telekom iPaaS / azure-com-hanaonazure-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
