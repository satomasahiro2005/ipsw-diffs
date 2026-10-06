## com.apple.CloudDocs.iCloudDriveFileProviderManaged

> `/System/Library/PrivateFrameworks/CloudDocs.framework/PlugIns/com.apple.CloudDocs.iCloudDriveFileProviderManaged.appex/com.apple.CloudDocs.iCloudDriveFileProviderManaged`

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
~ sub_100010310 : 968 -> 960
~ sub_100014834 -> sub_10001482c : 1252 -> 1312
~ sub_100014d30 -> sub_100014d64 : 248 -> 280
~ sub_10001b0d0 -> sub_10001b124 : 960 -> 952
~ sub_10001b4f0 -> sub_10001b53c : 972 -> 964
~ sub_10001c72c -> sub_10001c770 : 960 -> 952
~ sub_10001cb4c -> sub_10001cb88 : 972 -> 964
~ sub_10001f724 -> sub_10001f758 : 1096 -> 1088
~ sub_10001fbcc -> sub_10001fbf8 : 1084 -> 1076
CStrings:
- "processCanUseArbitraryPersonas"
```
