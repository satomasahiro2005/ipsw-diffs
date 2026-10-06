## notification_proxy

> `/usr/libexec/notification_proxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b0c` | `0x3bd8` | **`+0x10cc`** |
| `__TEXT.__oslogstring` | `0x6b9` | `0xb02` | **`+0x449`** |
| `__TEXT.__auth_stubs` | `0x500` | `0x5e0` | **`+0xe0`** |
| `__DATA_CONST.__cfstring` | `0x280` | `0x320` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x340` | `0x3c0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x3e4` | `0x458` | **`+0x74`** |
| `__DATA_CONST.__auth_got` | `0x290` | `0x300` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x3c4` | `0x415` | **`+0x51`** |
| `__TEXT.__objc_methtype` | `0x199` | `0x1dc` | **`+0x43`** |
| `__TEXT.__objc_methlist` | `0x284` | `0x2b4` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x200` | `0x228` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x1a8` | `0x1c8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x130` | `0x148` | **`+0x18`** |
| `__DATA.__bss` | `0x38` | `0x48` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x90` | `0xa0` | **`+0x10`** |
| `__DATA.__objc_const` | `0x440` | `0x448` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-40.0.0.0.0
+41.0.0.0.0

-  Functions: 62
-  Symbols:   108
-  CStrings:  169
+  Functions: 71
+  Symbols:   124
+  CStrings:  202
Symbols:
+ __xpc_type_int64
+ __xpc_type_uint64
+ _notify_get_state
+ _notify_register_check
+ _notify_set_state
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _objc_release_x24
+ _objc_retain_x23
+ _xpc_dictionary_apply
+ _xpc_dictionary_create_reply
+ _xpc_dictionary_get_int64
+ _xpc_dictionary_get_uint64
+ _xpc_dictionary_get_value
+ _xpc_dictionary_send_reply
+ _xpc_dictionary_set_value
CStrings:
+ "%@ - Failed to cancel the state token with status: %u"
+ "%@ - Failed to get notification state (%u)"
+ "%@ - Failed to register a state token for \"%@\" (%u)"
+ "%@ - Failed to set notification state (%u)"
+ "%@ - GET_NOTIFICATION_STATE is only supported over RemoteXPC"
+ "%@ - Got GET_NOTIFICATION_STATE command for notification: %@"
+ "%@ - Got SET_NOTIFICATION_STATE command for notification: %@"
+ "%@ - Holding state for %@"
+ "%@ - Insecure notification service cannot get state for \"%@\""
+ "%@ - Insecure notification service cannot set state for \"%@\""
+ "%@ - No name in get notification state command"
+ "%@ - No name in set notification state command"
+ "%@ - No state in set notification state command for \"%@\""
+ "%@ - no more state setters for \"%@\", releasing the state token"
+ "B24@?0r*8@\"NSObject<OS_xpc_object>\"16"
+ "Cannot send a response over lockdown, message: %@, connection: %@"
+ "Failed to cancel the check token for \"%@\" (%u)"
+ "Failed to convert dictionary to XPC reply."
+ "Failed to read the state of \"%@\" to relay with it (%u)"
+ "Failed to register a check token for \"%@\" (%u)"
+ "GetNotificationState"
+ "No reply context for request, message: %@, connection: %@"
+ "RelayNotificationState"
+ "SetNotificationState"
+ "State"
+ "State is not a 64-bit integer, ignoring it."
+ "Status"
+ "longLongValue"
+ "numberWithLongLong:"
+ "numberWithUnsignedInt:"
+ "sendResponse:inReplyTo:"
+ "v32@0:8@\"NSDictionary\"16@\"NSObject<OS_xpc_object>\"24"
+ "v32@0:8@16@24"
```
