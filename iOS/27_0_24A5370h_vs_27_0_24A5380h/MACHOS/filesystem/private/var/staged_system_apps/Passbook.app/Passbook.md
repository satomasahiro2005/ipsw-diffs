## Passbook

> `/private/var/staged_system_apps/Passbook.app/Passbook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfd10` | `0x10008` | **`+0x2f8`** |
| `__TEXT.__objc_stubs` | `0x2da0` | `0x2f00` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0x463d` | `0x4725` | **`+0xe8`** |
| `__DATA_CONST.__cfstring` | `0x420` | `0x500` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x6e4` | `0x74b` | **`+0x67`** |
| `__DATA.__objc_selrefs` | `0xf78` | `0xfd0` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x908` | `0x918` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x9d4` | `0x9e4` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1682.1.0.0.0
+1686.3.0.0.0

-  Functions: 197
-  Symbols:   400
-  CStrings:  766
+  Functions: 198
+  Symbols:   401
+  CStrings:  783
Symbols:
+ _OBJC_CLASS_$_NSURLQueryItem
Functions:
~ sub_100003620 : 14044 -> 14276
+ sub_10000dad0
CStrings:
+ "DETAILS"
+ "_openRemotePassInBridge:action:"
+ "_remoteLibrary"
+ "action"
+ "bridge:%@"
+ "com.apple.NanoPassbookBridgeSettings"
+ "isRemotePass"
+ "openSensitiveURL:withOptions:"
+ "passSerialNumber"
+ "passTypeIdentifier"
+ "passWithUniqueID:"
+ "percentEncodedQuery"
+ "queryItemWithName:value:"
+ "root"
+ "serialNumber"
+ "setQueryItems:"
+ "sharedInstanceWithRemoteLibrary"
```
