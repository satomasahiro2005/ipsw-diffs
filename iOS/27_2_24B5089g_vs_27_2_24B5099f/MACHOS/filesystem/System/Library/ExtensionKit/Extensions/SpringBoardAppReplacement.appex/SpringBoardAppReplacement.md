## SpringBoardAppReplacement

> `/System/Library/ExtensionKit/Extensions/SpringBoardAppReplacement.appex/SpringBoardAppReplacement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14c` | `0x27c` | **`+0x130`** |
| `__TEXT.__objc_stubs` | `0xa0` | `0x140` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x1f3` | `0x26f` | **`+0x7c`** |
| `__DATA.__data` | `0xc0` | `0x120` | **`+0x60`** |
| `__TEXT.__oslogstring` | `—` | `0x4e` | **`+0x4e`** |
| `__DATA.__objc_selrefs` | `0xd8` | `0x108` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0xd0` | `0x100` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x13c` | `0x164` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0xf5` | `0x111` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0x70` | `0x88` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x3c` | `0x51` | **`+0x15`** |
| `__DATA.__objc_const` | `0x1f8` | `0x208` | **`+0x10`** |
| `__TEXT.__const` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x60` | `0x68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-4637.1.8.101.0
+4637.1.12.101.0

-  Functions: 2
-  Symbols:   22
-  CStrings:  50
+  Functions: 3
+  Symbols:   26
+  CStrings:  60
Symbols:
+ _OBJC_CLASS_$_NSXPCInterface
+ _SBLogCommon
+ __os_log_impl
+ _objc_release_x25
+ _objc_retain_x20
+ _os_log_type_enabled
- _objc_release
- _objc_retain_x19
CStrings:
+ "Accepting app replacement connection from pid %d"
+ "B24@0:8@\"NSXPCConnection\"16"
+ "Replace icons for %@ with %@"
+ "_EXConnectionHandler"
+ "interfaceWithProtocol:"
+ "processIdentifier"
+ "replaceApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:options:"
+ "resume"
+ "setExportedInterface:"
+ "setExportedObject:"
+ "shouldAcceptXPCConnection:"
- "replaceApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:"
```
