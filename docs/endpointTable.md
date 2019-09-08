---
layout: default
title: Home
nav_order: 2
description: "Endpoint definitions."
---


| Source | Sestination | Owner | Format | Description | Decoder             | 
| ------ | ----------- | ----- | ------ | ----------- | ------------------- |
| 11     | 11          | WP    | tlv    | Ru          | [11_11_decoder][]   |
| ------ | ----------- | ----- | ------ | ----------- | ------------------- |
| 238    | 238         | WP    | tlv    | Pos         | [238_238_decoder][] |
| ------ | ----------- | ----- | ------ | ----------- | ------------------- |
| 247    | 247         | WP    | cbor   | Dv2         | [247_247_decoder][] |
| ------ | ----------- | ----- | ------ | ----------- | ------------------- |
| 251    | 255         | WP    | struct | Dia         |                     |
| ------ | ----------- | ----- | ------ | ----------- | ------------------- |
| 252    | 255         | WP    | struct | Dia         |                     |
| ------ | ----------- | ----- | ------ | ----------- | ------------------- |
| 253    | 255         | WP    | struct | Dia         |                     |
| ------ | ----------- | ----- | ------ | ----------- | ------------------- |
| 254    | 255         | WP    | struct | Dia         |                     |

<!--- Link for the decoders --->

[11_11_decoder]: https://github.com/wirepas/backend-client/blob/master/wirepas_backend_client/messages/ruuvi.py
[238_238_decoder]: https://github.com/wirepas/backend-client/blob/master/wirepas_backend_client/messages/positioning.py
[247_247_decoder]: https://github.com/wirepas/backend-client/blob/master/wirepas_backend_client/messages/diagnostics.py

[251_255_decoder]: https://github.com/wirepas/backend-client/blob/master/wirepas_backend_client/messages/trafficdiagnostics.py
[252_255_decoder]: https://github.com/wirepas/backend-client/blob/master/wirepas_backend_client/messages/neighbordiagnostics.py
[253_255_decoder]: https://github.com/wirepas/backend-client/blob/master/wirepas_backend_client/messages/nodediagnostics.py
[254_255_decoder]: https://github.com/wirepas/backend-client/blob/master/wirepas_backend_client/messages/bootdiagnostics.py
