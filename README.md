# ![LOGO](logo.png) Knowledge Graph Search **flow**ground Connector

## Description

A generated **flow**ground connector for the Knowledge Graph Search API (version v1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/kgsearch/v1/swagger.json<br/>
Generated at: 2019-05-07T17:41:45+03:00

## API Description

Searches the Google Knowledge Graph for entities.

## Authorization

This API does not require authorization.

## Actions

### Searches Knowledge Graph for entities that match the constraints.<br/>
> A list of matched entities will be returned in response, which will be in<br/>
> JSON-LD format and compatible with http://schema.org

*Tags:* `entities`

#### Input Parameters
* `ids` - _optional_ - The list of entity id to be used for search instead of query string.
To specify multiple ids in the HTTP request, repeat the parameter in the
URL as in ...?ids=A&ids=B
* `indent` - _optional_ - Enables indenting of json results.
* `languages` - _optional_ - The list of language codes (defined in ISO 693) to run the query with,
e.g. 'en'.
* `limit` - _optional_ - Limits the number of entities to be returned.
* `prefix` - _optional_ - Enables prefix match against names and aliases of entities
* `query` - _optional_ - The literal query string for search.
* `types` - _optional_ - Restricts returned entities with these types, e.g. Person
(as defined in http://schema.org/Person). If multiple types are specified,
returned entities will contain one or more of these types.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

## License

**flow**ground :- Telekom iPaaS / googleapis-com-kgsearch-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
