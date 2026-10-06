## RemoteHID

> `/System/Library/PrivateFrameworks/RemoteHID.framework/RemoteHID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae0c` | `0xae34` | **`+0x28`** |

### Other Changes

```diff

-223.0.0.0.0
+224.0.0.0.0
Functions:
~ -[HIDRemoteDeviceServer endpointMessageHandler:data:size:] : 448 -> 456
~ _load_descriptor_values : 368 -> 408
~ _advance_iterator : 116 -> 112
~ _OUTLINED_FUNCTION_0 : 24 -> 20
~ _buf_write : 40 -> 48
~ _pb_encode_varint : 240 -> 228
~ _pb_encode_tag_for_field : 72 -> 68
~ _pb_check_proto3_default_value : 424 -> 432
~ _OUTLINED_FUNCTION_5 : 20 -> 12
~ _OUTLINED_FUNCTION_6 : 12 -> 20
~ _buf_read : 44 -> 52
~ _pb_decode_inner : 864 -> 860
~ _decode_field : 1000 -> 1008
~ _decode_basic_field : 1184 -> 1180
~ _encode : 628 -> 620
```
