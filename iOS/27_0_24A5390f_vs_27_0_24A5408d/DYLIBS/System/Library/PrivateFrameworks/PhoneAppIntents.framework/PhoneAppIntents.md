## PhoneAppIntents

> `/System/Library/PrivateFrameworks/PhoneAppIntents.framework/PhoneAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3707c` | `0x38084` | **`+0x1008`** |
| `__TEXT.__oslogstring` | `0x375` | `0x465` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x418` | `0x460` | **`+0x48`** |
| `__DATA_DIRTY.__data` | `0x4e0` | `0x508` | **`+0x28`** |
| `__TEXT.__const` | `0x5a94` | `0x5ab4` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xbd8` | `0xbf0` | **`+0x18`** |
| `__DATA.__data` | `0x10a8` | `0x10c0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x4b0` | `0x4c8` | **`+0x18`** |
| `__TEXT.__eh_frame` | `0x14c4` | `0x14cc` | **`+0x8`** |

### Other Changes

```diff

-1616.100.2.2.1
+1620.100.1.2.3

-  Functions: 1753
-  Symbols:   989
-  CStrings:  114
+  Functions: 1757
+  Symbols:   993
+  CStrings:  118
Symbols:
+ _OBJC_CLASS_$_CNContact
+ _OBJC_CLASS_$_CNGeminiManager
+ _OBJC_CLASS_$_TUSenderIdentity
+ _swift_getErrorValue
CStrings:
+ "Contact preferred accountUUIDData %s"
+ "Could not resolve preferred sender identity for contact: %s"
+ "Device holds %ld sender identities"
+ "No contact found for identifier while resolving preferred sender identity"
```
