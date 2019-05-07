# ![LOGO](logo.png) NetworkAdminManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the NetworkAdminManagementClient API (version 2015-06-15).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-VirtualNetworks/2015-06-15/swagger.json<br/>
Generated at: 2019-05-07T17:37:36+03:00

## API Description

Virtual Network admin operation endpoints and objects.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get a list of all virtual networks.

*Tags:* `VirtualNetworks`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `$filter` - _optional_ - OData filter parameter.
* `$orderBy` - _optional_ - OData orderBy parameter.
* `$top` - _optional_ - OData top parameter.
* `$skip` - _optional_ - OData skip parameter.
* `$inlineCount` - _optional_ - OData inline count parameter.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-virtual-networks-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
