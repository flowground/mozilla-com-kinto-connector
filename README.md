# ![LOGO](logo.png) Remote Settings **flow**ground Connector

## Description

A generated **flow**ground connector for the Remote Settings API (version 1.21).

Generated from: https://api.apis.guru/v2/specs/mozilla.com/kinto/1.21/swagger.json<br/>
Generated at: 2019-05-07T17:43:05+03:00

## API Description



## Authorization

This API does not require authorization.

## Actions

### server_info

*Tags:* `Utilities`

### get_openapi_spec

*Tags:* `Utilities`

### action___heartbeat__

*Tags:* `Utilities`

### action___lbheartbeat__

*Tags:* `Utilities`

### get_user_datas

*Tags:* `User-datas`

#### Input Parameters
* `_limit` - _optional_
* `_sort` - _optional_
* `_token` - _optional_
* `_since` - _optional_
* `_to` - _optional_
* `_before` - _optional_
* `id` - _optional_
* `last_modified` - _optional_
* `_fields` - _optional_
* `If-Match` - _optional_
* `If-None-Match` - _optional_

### action___version__

*Tags:* `Utilities`

### batch

*Tags:* `Batch`

### get_buckets

*Tags:* `Buckets`

#### Input Parameters
* `_limit` - _optional_
* `_sort` - _optional_
* `_token` - _optional_
* `_since` - _optional_
* `_to` - _optional_
* `_before` - _optional_
* `id` - _optional_
* `last_modified` - _optional_
* `_fields` - _optional_
* `If-Match` - _optional_
* `If-None-Match` - _optional_

### get_changess

*Tags:* `Changess`

#### Input Parameters
* `_limit` - _optional_
* `_sort` - _optional_
* `_token` - _optional_
* `_since` - _optional_
* `_to` - _optional_
* `_before` - _optional_
* `id` - _optional_
* `last_modified` - _optional_
* `_fields` - _optional_
* `If-Match` - _optional_
* `If-None-Match` - _optional_

### get_collections

*Tags:* `Collections`

#### Input Parameters
* `_limit` - _optional_
* `_sort` - _optional_
* `_token` - _optional_
* `_since` - _optional_
* `_to` - _optional_
* `_before` - _optional_
* `id` - _optional_
* `last_modified` - _optional_
* `_fields` - _optional_
* `If-Match` - _optional_
* `If-None-Match` - _optional_

### get_records

*Tags:* `Records`

#### Input Parameters
* `_limit` - _optional_
* `_sort` - _optional_
* `_token` - _optional_
* `_since` - _optional_
* `_to` - _optional_
* `_before` - _optional_
* `id` - _optional_
* `last_modified` - _optional_
* `_fields` - _optional_
* `If-Match` - _optional_
* `If-None-Match` - _optional_

### get_record

*Tags:* `Records`

#### Input Parameters
* `_fields` - _optional_
* `If-Match` - _optional_
* `If-None-Match` - _optional_

### delete_attachment

*Tags:* `Attachment`

#### Input Parameters
* `bucket_id` - _required_
* `collection_id` - _required_
* `id` - _required_

### create_attachment

*Tags:* `Attachment`

#### Input Parameters
* `bucket_id` - _required_
* `collection_id` - _required_
* `id` - _required_

### get_collection

*Tags:* `Collections`

#### Input Parameters
* `_fields` - _optional_
* `If-Match` - _optional_
* `If-None-Match` - _optional_

### get_groups

*Tags:* `Groups`

#### Input Parameters
* `_limit` - _optional_
* `_sort` - _optional_
* `_token` - _optional_
* `_since` - _optional_
* `_to` - _optional_
* `_before` - _optional_
* `id` - _optional_
* `last_modified` - _optional_
* `_fields` - _optional_
* `If-Match` - _optional_
* `If-None-Match` - _optional_

### get_group

*Tags:* `Groups`

#### Input Parameters
* `_fields` - _optional_
* `If-Match` - _optional_
* `If-None-Match` - _optional_

### get_bucket

*Tags:* `Buckets`

#### Input Parameters
* `_fields` - _optional_
* `If-Match` - _optional_
* `If-None-Match` - _optional_

### contribute

*Tags:* `Utilities`

### get_blocklist

*Tags:* `Blocklist`

#### Input Parameters
* `api_ver:\d+` - _required_
* `metrics:.*` - _required_
* `application_ver` - _required_

## License

**flow**ground :- Telekom iPaaS / mozilla-com-kinto-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
