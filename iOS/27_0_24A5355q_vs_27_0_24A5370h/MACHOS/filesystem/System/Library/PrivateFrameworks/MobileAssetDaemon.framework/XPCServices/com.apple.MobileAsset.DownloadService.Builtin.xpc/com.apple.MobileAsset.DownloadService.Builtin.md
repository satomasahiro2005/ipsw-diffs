## com.apple.MobileAsset.DownloadService.Builtin

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/XPCServices/com.apple.MobileAsset.DownloadService.Builtin.xpc/com.apple.MobileAsset.DownloadService.Builtin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x216bc` | `0x2182c` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x6051` | `0x60e5` | **`+0x94`** |
| `__TEXT.__auth_stubs` | `0xd70` | `0xda0` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x2d60` | `0x2d80` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x6c8` | `0x6e0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x43d9` | `0x43e9` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2215.0.0.502.1
+2215.0.4.0.0

-  Symbols:   349
-  CStrings:  1985
+  Symbols:   352
+  CStrings:  1988
Symbols:
+ _CFPreferencesAppSynchronize
+ _MAPreferencesCopyValue
+ _MAPreferencesIsInternalAllowed
Functions:
~ sub_100002e44 : 1248 -> 1244
~ sub_100004154 -> sub_100004150 : 392 -> 388
~ sub_100004e24 -> sub_100004e1c : 1896 -> 1892
~ sub_100006704 -> sub_1000066f8 : 1216 -> 1212
~ sub_10000a790 -> sub_10000a780 : 640 -> 632
~ sub_10000cfbc -> sub_10000cfa4 : 396 -> 392
~ sub_10000f55c -> sub_10000f540 : 184 -> 180
~ sub_100013130 -> sub_100013110 : 532 -> 528
~ sub_100013ab8 -> sub_100013a94 : 524 -> 520
~ sub_100013f34 -> sub_100013f0c : 1128 -> 1124
~ sub_100014518 -> sub_1000144ec : 424 -> 420
~ sub_1000146c0 -> sub_100014690 : 952 -> 948
~ sub_100015128 -> sub_1000150f4 : 1068 -> 1064
~ sub_100019020 -> sub_100018fe8 : 516 -> 512
~ sub_100019268 -> sub_10001922c : 648 -> 644
~ sub_10001aa74 -> sub_10001aa34 : 1496 -> 1492
~ sub_10001d068 -> sub_10001d024 : 1336 -> 1332
~ sub_10001e514 -> sub_10001e4cc : 1584 -> 2032
~ sub_10001eb44 -> sub_10001ecbc : 1852 -> 1848
~ sub_100020920 -> sub_100020a94 : 1544 -> 1540
CStrings:
+ "WKMSURLOverride"
+ "[MADownloadServiceBuiltin]: Attempting to start up builtin service built Jun 16 2026 00:18:01"
+ "[WKMSURLOverride]: Ignoring malformed override (class=%{public}@, length=%lu)"
+ "[WKMSURLOverride]: Using override %{public}@ (catalog was %{public}@)"
- "[MADownloadServiceBuiltin]: Attempting to start up builtin service built Jun  1 2026 21:29:50"
```
