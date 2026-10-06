## SESUIServiceApp

> `/Applications/SESUIServiceApp.app/SESUIServiceApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf424` | `0xf26c` | **`-0x1b8`** |
| `__TEXT.__objc_stubs` | `0x920` | `0x980` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x9d0` | `0x980` | **`-0x50`** |
| `__TEXT.__objc_methname` | `0x16c7` | `0x1717` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0xc40` | `0xc60` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xf9b` | `0xf7b` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0x564` | `0x584` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x5b8` | `0x5d0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x1e8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x332` | `0x31a` | **`-0x18`** |
| `__TEXT.__swift5_capture` | `0x280` | `0x26c` | **`-0x14`** |
| `__DATA.__data` | `0x640` | `0x630` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x630` | `0x640` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x100` | `0xf0` | **`-0x10`** |
| `__TEXT.__const` | `0x398` | `0x388` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x430` | `0x420` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x74` | `0x78` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x5c` | `0x58` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-70.35.1.0.0
+70.37.0.0.0

+  - /System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore

-  Functions: 296
-  Symbols:   320
-  CStrings:  398
+  Functions: 292
+  Symbols:   323
+  CStrings:  400
Symbols:
+ _$sSa10FoundationE36_unconditionallyBridgeFromObjectiveCySayxGSo7NSArrayCSgFZ
+ _$sScM6sharedScMvgZ
+ _$sScMMa
+ _$sScMScAsWP
+ _OBJC_CLASS_$_PKPass
+ _OBJC_CLASS_$_PKPassLibrary
+ _OBJC_CLASS_$_PKPassView
+ _OBJC_CLASS_$_PKSecureElementPass
+ _PKPassViewRequiredContentSuppressionForImageSnapshot
+ _objc_retain_x26
- _$s16SESUIServiceCore28SEStorageManagementViewModelV16WalletUsageGroupV9PassEntryVMn
- _$sScC12continuation8functionScCyxq_GSccyxq_G_SStcfC
- _$sScC6resume9returningyxn_tF
- _$ss5NeverOMn
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _OBJC_CLASS_$_PKPassSnapshotter
CStrings:
+ "No library pass for %s, rendering without artwork"
+ "Snapshot for pass %s is nil"
+ "initWithPass:content:suppressedContent:"
+ "passes"
+ "remoteSecureElementPasses"
+ "snapshotOfFrontFaceWithRequestedSize:"
+ "uniqueID"
- "Found image for pass %s"
- "Image for pass %s is nil"
- "sharedInstance"
- "snapshotWithUniqueID:size:completion:"
- "v16@?0@\"UIImage\"8"
```
