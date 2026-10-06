## AgeVerificationExtension

> `/System/Library/ExtensionKit/Extensions/AgeVerificationExtension.appex/AgeVerificationExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a2c` | `0x1ed8` | **`+0x4ac`** |
| `__TEXT.__objc_methtype` | `0x144` | `0x1e4` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x200` | `0x278` | **`+0x78`** |
| `__DATA_CONST.__const` | `0x1e0` | `0x258` | **`+0x78`** |
| `__TEXT.__eh_frame` | `0xe0` | `0x158` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0x111` | `0x169` | **`+0x58`** |
| `__TEXT.__objc_methname` | `0xf5` | `0x146` | **`+0x51`** |
| `__TEXT.__objc_classname` | `0xab` | `0xe9` | **`+0x3e`** |
| `__TEXT.__swift5_capture` | `0x38` | `0x70` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x5c` | `0x90` | **`+0x34`** |
| `__TEXT.__auth_stubs` | `0x320` | `0x350` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x128` | `0x150` | **`+0x28`** |
| `__TEXT.__const` | `0x1fa` | `0x21a` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x38` | `0x50` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x198` | `0x1b0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x38` | `0x50` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0xc` | `0x18` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x8` | `0xc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-8.0.52.2.8
+8.1.12.2.1

+  - /System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices

-  Functions: 57
-  Symbols:   66
-  CStrings:  20
+  Functions: 80
+  Symbols:   67
+  CStrings:  27
Symbols:
+ _swift_retain_x23
CStrings:
+ "_TtP18AppleMediaServices29AgeEstimationServiceInterface_"
+ "_TtP18AppleMediaServices32AgeModelDownloadServiceInterface_"
+ "_TtP18AppleMediaServices32AgeVerificationExtensionProtocol_"
+ "ageModelDownloadServiceWithReply:"
+ "downloadModelsWithReply:"
+ "modelsReadyWithReply:"
+ "v24@0:8@?<v@?@\"<_TtP18AppleMediaServices29AgeEstimationServiceInterface_>\">16"
+ "v24@0:8@?<v@?@\"<_TtP18AppleMediaServices32AgeModelDownloadServiceInterface_>\">16"
+ "v24@0:8@?<v@?@\"NSError\">16"
+ "v24@0:8@?<v@?B>16"
- "_TtP20AppleMediaServicesUI29AgeEstimationServiceInterface_"
- "_TtP20AppleMediaServicesUI32AgeVerificationExtensionProtocol_"
- "v24@0:8@?<v@?@\"<_TtP20AppleMediaServicesUI29AgeEstimationServiceInterface_>\">16"
```
