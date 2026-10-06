## com.apple.accessoryd.matching

> `/System/Library/UserEventPlugins/com.apple.accessoryd.matching.plugin/com.apple.accessoryd.matching`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37ca4` | `0x37d60` | **`+0xbc`** |
| `__TEXT.__objc_stubs` | `0x5080` | `0x50c0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x3f4f` | `0x3f71` | **`+0x22`** |
| `__DATA.__cfstring` | `0x39a0` | `0x39c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4f8e` | `0x4faa` | **`+0x1c`** |
| `__TEXT.__objc_methname` | `0x6ebf` | `0x6ed9` | **`+0x1a`** |
| `__DATA.__const` | `0x10e0` | `0x10f0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1a20` | `0x1a30` | **`+0x10`** |
| `__DATA.__got` | `0x380` | `0x388` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__auth_ptr`
- `__DATA.__data`
- `__DATA.__objc_arraydata`
- `__DATA.__objc_arrayobj`
- `__DATA.__objc_catlist`
- `__DATA.__objc_classlist`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_dictobj`
- `__DATA.__objc_intobj`
- `__DATA.__objc_protolist`
- `__DATA.__objc_protorefs`
- `__DATA.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1210.0.0.502.1
+1216.0.0.0.0

-  Symbols:   3144
-  CStrings:  2503
+  Symbols:   3149
+  CStrings:  2507
Symbols:
+ _ACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
+ _OBJC_CLASS_$_ACCTransportClient
+ _kCFACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
+ _objc_msgSend$launchServer
+ _objc_msgSend$sharedClient
Functions:
~ _OUTLINED_FUNCTION_16 : 20 -> 16
~ _OUTLINED_FUNCTION_17 : 16 -> 20
~ _OUTLINED_FUNCTION_19 : 24 -> 12
~ _OUTLINED_FUNCTION_20 : 12 -> 24
~ _OUTLINED_FUNCTION_25 : 20 -> 12
~ _OUTLINED_FUNCTION_26 : 12 -> 20
~ _OUTLINED_FUNCTION_8 : 8 -> 12
~ _OUTLINED_FUNCTION_9 : 12 -> 28
~ _OUTLINED_FUNCTION_10 : 16 -> 8
~ _OUTLINED_FUNCTION_11 : 28 -> 16
~ _OUTLINED_FUNCTION_20 : 12 -> 20
~ _OUTLINED_FUNCTION_21 : 20 -> 12
~ -[accessorydMatchingPlugin initWithModule:] : 2248 -> 2372
~ _LibSer_SEPControl_Deserialize : 160 -> 200
~ _LibSer_SEPControlResponse_Deserialize : 64 -> 88
CStrings:
+ "BLEPairingAuthTimeoutValueS"
+ "initWithModule: call launchServer"
+ "launchServer"
+ "sharedClient"
```
