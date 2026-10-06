## ndoagent

> `/System/Library/PrivateFrameworks/NewDeviceOutreach.framework/ndoagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x79628` | `0x798d4` | **`+0x2ac`** |
| `__TEXT.__auth_stubs` | `0x2d80` | `0x2d10` | **`-0x70`** |
| `__TEXT.__cstring` | `0x20c0` | `0x2070` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0x16d0` | `0x1698` | **`-0x38`** |
| `__TEXT.__oslogstring` | `0x2e5b` | `0x2e8b` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0xe4` | `0xc0` | **`-0x24`** |
| `__DATA.__bss` | `0xb560` | `0xb540` | **`-0x20`** |
| `__DATA_CONST.__cfstring` | `0xfe0` | `0xfc0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xbc0` | `0xba8` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0xba4` | `0xb8c` | **`-0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x88` | `0x78` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x2a5f` | `0x2a4f` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1cf8` | `0x1cf0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-624.0.13.0.0
+624.40.14.0.0

-  - /System/Library/PrivateFrameworks/GraphicsServices.framework/GraphicsServices

-  Symbols:   1235
-  CStrings:  1056
+  Symbols:   1225
+  CStrings:  1052
Symbols:
- __dispatch_main_q
- __dispatch_source_type_timer
- _dispatch_activate
- _dispatch_source_cancel
- _dispatch_source_create
- _dispatch_source_set_event_handler
- _dispatch_source_set_timer
- _dispatch_time
- _kGSEventHardwareKeyboardAvailabilityChangedNotification
- _notify_register_dispatch
CStrings:
+ "%s Profile expired."
+ "Override Serial Number: %{private}@ found for accessory SN: %{private}@"
+ "Override Serial Number: %{private}@ found for default device SN: %{private}@"
+ "Removing every %{public}s user default because we are %{public}s. Any environment or serial number override is being discarded. Set the development flag to true alongside an environment override to prevent this. Discarding keys: [%{private}s]"
+ "Smart Connector keyboard event: %s"
+ "com.apple.iokit.matching"
+ "performing first launch cleanup"
+ "persistentDomainForName:"
+ "resetting to production environment"
- "%s Profile expired. Resetting to production environment."
- "%{private}s resolved %{private}@ to %{private}@"
- "Hardware keyboard availability changed — scheduling debounced check-in"
- "Keyboard debounce timer fired — triggering check-in"
- "NSString *_ResolvedSerialNumber(NSString * _Nullable __strong)"
- "Override Serial Number: %@ found for SN: %@"
- "Smart Connector keyboard monitoring started"
- "com.apple.backboard.keyboard.attached"
- "com.apple.ndoagent.keyboardChanged"
- "com.apple.ndoagent.keyboardDebounce"
- "notify_register_dispatch(kGSEventHardwareKeyboardAvailabilityChangedNotification) failed: %u"
- "startMonitoringWithCheckInHandler:"
- "v12@?0i8"
```
