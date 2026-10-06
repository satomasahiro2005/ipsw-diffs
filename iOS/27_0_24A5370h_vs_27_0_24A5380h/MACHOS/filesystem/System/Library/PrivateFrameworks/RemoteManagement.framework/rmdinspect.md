## rmdinspect

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/rmdinspect`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x2d60` | `0x2ce0` | **`-0x80`** |
| `__TEXT.__objc_methname` | `0x2f0a` | `0x2e8c` | **`-0x7e`** |
| `__TEXT.__cstring` | `0x12e1` | `0x1284` | **`-0x5d`** |
| `__DATA.__objc_selrefs` | `0xdc0` | `0xda0` | **`-0x20`** |
| `__DATA_CONST.__cfstring` | `0x1ca0` | `0x1c80` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x208` | **`+0x18`** |
| `__TEXT.__text` | `0xfa54` | `0xfa40` | **`-0x14`** |
| `__TEXT.__auth_stubs` | `0x540` | `0x550` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xea4` | `0xe94` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x3da` | `0x3cc` | **`-0xe`** |
| `__DATA_CONST.__auth_got` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__const` | `0x68` | `0x70` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x478` | `0x470` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-624.0.3.0.0
+624.0.8.0.0

-  Functions: 336
-  Symbols:   162
-  CStrings:  872
+  Functions: 334
+  Symbols:   163
+  CStrings:  866
Symbols:
+ _RMSwitchToDaemonUserIfNeeded
CStrings:
+ "_reportInScope:"
- "@32@0:8q16@24"
- "Library/Application Support/com.apple.RemoteManagementAgent/Database/RemoteManagement.sqlite"
- "_reportInScope:overrideUserScopeHomePath:"
- "_switchToRMDUserIfNeeded"
- "fileURLWithPath:"
- "stringByAppendingPathComponent:"
- "stringByStandardizingPath"
```
