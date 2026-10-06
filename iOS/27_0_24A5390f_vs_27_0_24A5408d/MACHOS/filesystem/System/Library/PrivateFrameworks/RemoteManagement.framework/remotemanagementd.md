## remotemanagementd

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/remotemanagementd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b2b8` | `0x8b1dc` | **`-0xdc`** |
| `__TEXT.__objc_methname` | `0xf0f9` | `0xf15e` | **`+0x65`** |
| `__TEXT.__objc_stubs` | `0xc360` | `0xc3a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3019` | `0x3044` | **`+0x2b`** |
| `__DATA.__objc_selrefs` | `0x3518` | `0x3538` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x3460` | `0x3480` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x9f8` | `0x9e8` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x860` | `0x870` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x440` | `0x448` | **`+0x8`** |
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
- `__TEXT.__unwind_info`

### Other Changes

```diff

-624.0.10.0.0
+624.2.3.0.0

-  Symbols:   434
-  CStrings:  3880
+  Symbols:   433
+  CStrings:  3885
Symbols:
+ _notify_post
- _OBJC_CLASS_$_RMModelStatusManagementPushToken
- _RMModelStatusItemManagementPushToken
Functions:
~ sub_10000dd88 : 312 -> 284
~ sub_10000f180 -> sub_10000f164 : 684 -> 668
~ sub_10001a278 -> sub_10001a24c : 20 -> 68
~ sub_10002b6d4 -> sub_10002b6d8 : 204 -> 188
~ sub_10002ed10 -> sub_10002ed04 : 204 -> 188
~ sub_100054b34 -> sub_100054b18 : 836 -> 800
~ sub_100055048 -> sub_100055008 : 176 -> 48
~ sub_1000550f8 -> sub_100055038 : 348 -> 68
~ sub_100063f34 -> sub_100063d5c : 272 -> 324
~ sub_100064044 -> sub_100063ea0 : 3040 -> 3176
~ sub_100065544 -> sub_100065428 : 836 -> 936
~ sub_100089d5c -> sub_100089ca4 : 88 -> 52
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
