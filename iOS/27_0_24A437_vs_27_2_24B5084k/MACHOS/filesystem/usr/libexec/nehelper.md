## nehelper

> `/usr/libexec/nehelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x255fc` | `0x2588c` | **`+0x290`** |
| `__TEXT.__cstring` | `0x5f44` | `0x5ff2` | **`+0xae`** |
| `__TEXT.__objc_methname` | `0x1f9c` | `0x1fc7` | **`+0x2b`** |
| `__TEXT.__oslogstring` | `0x4a97` | `0x4ac1` | **`+0x2a`** |
| `__DATA_CONST.__cfstring` | `0x51a0` | `0x51c0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xd10` | `0xcf0` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x2a60` | `0x2a80` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x10b0` | `0x10c0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xb38` | `0xb40` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x868` | `0x870` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3b8` | `0x3c0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3e8` | `0x3f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2340.0.0.0.4
+2365.40.1.0.0

-  Functions: 247
-  Symbols:   382
-  CStrings:  1700
+  Functions: 248
+  Symbols:   384
+  CStrings:  1707
Symbols:
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _xpc_copy
CStrings:
+ "Error deserializing trusted user info: %@"
+ "LaunchServices"
+ "PreserveExistingConnections"
+ "com.apple.distnoted.matching.trusted"
+ "com.apple.networkextension.preserve-existing-connections"
+ "propertyListWithData:options:format:error:"
+ "restricted_distributed_notifications"
```
