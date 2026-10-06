## Accessory Updater Service

> `/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/Accessory Updater Service.xpc/Accessory Updater Service`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77ec0` | `0x77fbc` | **`+0xfc`** |
| `__DATA_CONST.__got` | `0x3b8` | `0x3e0` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x1890` | `0x1870` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0xc58` | `0xc48` | **`-0x10`** |
| `__TEXT.__cstring` | `0x178bb` | `0x178bf` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_imageinfo`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3695.0.0.0.0
+3696.0.3.0.1

-  Symbols:   1876
+  Symbols:   1874
Symbols:
- _CFDataDeleteBytes
- _objc_release_x9
Functions:
~ sub_10000521c : 312 -> 188
~ _AMAuthInstallApImg4GetTypeForEntryName : 120 -> 128
~ _AMAuthInstallMonetMeasureDbl : 428 -> 420
~ _AMAuthInstallMonetMeasureMav20ElfMBN : 944 -> 932
~ _AMAuthInstallMonetMeasureElfMBN : 972 -> 960
~ _b64_ntop : 364 -> 352
~ sub_10001c8a8 -> sub_10001c808 : 1040 -> 1044
~ sub_10001cd64 -> sub_10001ccc8 : 568 -> 576
~ __AMRUSBDeviceGetFirmwareInfo : 320 -> 328
~ __createDFUDataFromFile : 640 -> 636
~ sub_10003194c -> sub_1000318bc : 184 -> 200
~ sub_100031a0c -> sub_10003198c : 840 -> 960
~ sub_100031d54 -> sub_100031d4c : 832 -> 948
~ sub_100032094 -> sub_100032100 : 256 -> 272
~ sub_100032224 -> sub_1000322a0 : 96 -> 104
~ sub_100032284 -> sub_100032308 : 228 -> 256
~ sub_100032368 -> sub_100032408 : 164 -> 160
~ sub_100032474 -> sub_100032510 : 204 -> 232
~ sub_100036218 -> sub_1000362d0 : 844 -> 832
~ sub_10004c9d8 -> sub_10004ca84 : 812 -> 800
~ sub_100050798 -> sub_100050838 : 104 -> 72
~ _AMAuthInstallApFtabStitchTicketData : 388 -> 384
~ sub_10005608c -> sub_100056108 : 44 -> 192
~ _AMAuthInstallMonetMeasureElf : 784 -> 772
~ _AMAuthInstallMonetMeasureBootSbl : 436 -> 428
CStrings:
+ "libauthinstall_device-1155.0.3"
- "libauthinstall_device-1155"
```
