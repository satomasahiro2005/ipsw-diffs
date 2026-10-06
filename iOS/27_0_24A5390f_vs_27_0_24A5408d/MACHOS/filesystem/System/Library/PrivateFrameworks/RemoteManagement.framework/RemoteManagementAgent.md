## RemoteManagementAgent

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/RemoteManagementAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b53c` | `0x8b460` | **`-0xdc`** |
| `__TEXT.__objc_methname` | `0xf106` | `0xf16b` | **`+0x65`** |
| `__TEXT.__objc_stubs` | `0xc380` | `0xc3c0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x301d` | `0x3048` | **`+0x2b`** |
| `__DATA.__objc_selrefs` | `0x3520` | `0x3540` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x3460` | `0x3480` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x9f0` | `0x9e0` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x860` | `0x870` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x440` | `0x448` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2070` | `0x2068` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x265b` | `0x265e` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-624.0.10.0.0
+624.2.3.0.0

-  Symbols:   434
-  CStrings:  3882
+  Symbols:   433
+  CStrings:  3887
Symbols:
+ _notify_post
- _OBJC_CLASS_$_RMModelStatusManagementPushToken
- _RMModelStatusItemManagementPushToken
Functions:
~ sub_10000bc14 : 312 -> 284
~ sub_10000d050 -> sub_10000d034 : 684 -> 668
~ sub_100018988 -> sub_10001895c : 20 -> 68
~ sub_10002a5b0 -> sub_10002a5b4 : 204 -> 188
~ sub_10002dbec -> sub_10002dbe0 : 204 -> 188
~ sub_100054c7c -> sub_100054c60 : 836 -> 800
~ sub_100055190 -> sub_100055150 : 176 -> 48
~ sub_100055240 -> sub_100055180 : 348 -> 68
~ sub_1000640d8 -> sub_100063f00 : 272 -> 324
~ sub_1000641e8 -> sub_100064044 : 3040 -> 3176
~ sub_1000656e8 -> sub_1000655cc : 836 -> 936
~ sub_100089f60 -> sub_100089ea8 : 88 -> 52
CStrings:
+ "B64@0:8@16@24@32@40q48^@56"
+ "UTF8String"
+ "_storeAssetData:asset:assetKey:serverContentType:enrollmentType:error:"
+ "com.apple.remotemanagement.device.unlocked"
+ "lowercaseString"
+ "serverReportedContentType"
+ "setServerReportedContentType:"
- "B56@0:8@16@24@32q40^@48"
- "_storeAssetData:asset:assetKey:enrollmentType:error:"
```
