# ![LOGO](logo.png) Azure SQL Database **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure SQL Database API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-checkNameAvailability/2014-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:01+03:00

## API Description

Provides create, read, update and delete functionality for Azure SQL Database resources including servers, databases, elastic pools, recommendations, and operations.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Determines whether a resource can be created with the specified name.

*Tags:* `Servers`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-check-name-availability-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
