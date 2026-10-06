## com.apple.CloudDocs.iCloudDriveFileProvider

> `/System/Library/PrivateFrameworks/CloudDocs.framework/PlugIns/com.apple.CloudDocs.iCloudDriveFileProvider.appex/com.apple.CloudDocs.iCloudDriveFileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x610` | `0x640` | **`+0x30`** |
| `__TEXT.__text` | `0x23e98` | `0x23ebc` | **`+0x24`** |
| `__TEXT.__objc_stubs` | `0x2c80` | `0x2c60` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x5385` | `0x5366` | **`-0x1f`** |
| `__DATA_CONST.__auth_got` | `0x318` | `0x330` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1280` | `0x1278` | **`-0x8`** |
| `__TEXT.__const` | `0xb0` | `0xb8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5168.0.5.0.2
+5168.0.55.0.0

-  Symbols:   186
-  CStrings:  1439
+  Symbols:   189
+  CStrings:  1438
Symbols:
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _voucher_process_can_use_arbitrary_personas
Functions:
~ sub_100008f9c : 1096 -> 1088
~ sub_100009444 -> sub_10000943c : 1084 -> 1076
~ sub_1000136c8 -> sub_1000136b8 : 1252 -> 1312
~ sub_100013bc4 -> sub_100013bf0 : 248 -> 280
~ sub_10001819c -> sub_1000181e8 : 960 -> 952
~ sub_1000185bc -> sub_100018600 : 972 -> 964
~ sub_1000192b0 -> sub_1000192ec : 960 -> 952
~ sub_1000196d0 -> sub_100019704 : 972 -> 964
~ sub_100020038 -> sub_100020064 : 968 -> 960
CStrings:
- "processCanUseArbitraryPersonas"
```
