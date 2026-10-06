## MessagesDataclassOwner

> `/System/Library/Accounts/DataclassOwners/MessagesDataclassOwner.bundle/MessagesDataclassOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2008` | `0x2108` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x6fa` | `0x79f` | **`+0xa5`** |
| `__TEXT.__objc_methname` | `0x808` | `0x84a` | **`+0x42`** |
| `__TEXT.__objc_stubs` | `0x5c0` | `0x600` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x2c8` | `0x2e8` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x280` | `0x290` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x280` | `0x290` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x294` | `0x2a4` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x150` | `0x158` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x138` | `0x140` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

-  Functions: 25
-  Symbols:   73
-  CStrings:  167
+  Functions: 27
+  Symbols:   74
+  CStrings:  171
Symbols:
+ __os_log_error_impl
+ _objc_retain_x25
- _objc_retain_x24
CStrings:
+ "Skip showing the disablement alert; device has no user-facing MiC toggle."
+ "Timed out waiting for user to interact with the MiC disablement alert; treating as cancel."
+ "_canPromptForDisablement"
+ "removeNotificationsForServiceIdentifier:"
```
