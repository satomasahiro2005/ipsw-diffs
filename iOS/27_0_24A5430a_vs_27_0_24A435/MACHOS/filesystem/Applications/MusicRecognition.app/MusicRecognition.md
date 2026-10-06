## MusicRecognition

> `/Applications/MusicRecognition.app/MusicRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc850` | `0xdd880` | **`+0x1030`** |
| `__TEXT.__eh_frame` | `0x6aa0` | `0x6bd8` | **`+0x138`** |
| `__TEXT.__oslogstring` | `0x15a4` | `0x1674` | **`+0xd0`** |
| `__TEXT.__objc_methname` | `0x36e5` | `0x3765` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x25a0` | `0x2620` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x4590` | `0x45d0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x1378` | `0x13b0` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x38a8` | `0x38e0` | **`+0x38`** |
| `__DATA.__objc_const` | `0x2b78` | `0x2b98` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xc60` | `0xc80` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x22d0` | `0x22f0` | **`+0x20`** |
| `__TEXT.__const` | `0xa424` | `0xa444` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x2aef` | `0x2b0f` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x4db8` | `0x4da0` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0x669a` | `0x66aa` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x22dc` | `0x22e8` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x2dc` | `0x2e8` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x1c48` | `0x1c50` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x5b8` | `0x5c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-  Functions: 4225
-  Symbols:   2409
-  CStrings:  1093
+  Functions: 4233
+  Symbols:   2418
+  CStrings:  1102
Symbols:
+ _$s11ShazamKitUI24AnalyticsRecognitionTypeO7instantyA2CmFWC
+ _$s9ShazamKit16SHManagedSessionC7catalogACSo9SHCatalogC_tcfc
+ _$s9ShazamKit16SHManagedSessionC7prepareyyYaF
+ _$s9ShazamKit16SHManagedSessionC7prepareyyYaFTu
+ _OBJC_CLASS_$_SHDeviceFeatures
+ _OBJC_CLASS_$_SHShazamCatalog
+ _OBJC_CLASS_$_SHShazamCatalogConfiguration
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
CStrings:
+ "Attempting an instant shazam match."
+ "Failed to initialize instant shazam managed session. Error: %@"
+ "No instant shazam match. Defaulting to classic shazam."
+ "Returning instant shazam match."
+ "initWithConfiguration:error:"
+ "instantShazamSession"
+ "setEnableInstant:"
+ "setStoreSignatureOnNoMatch:"
+ "supportsInstantShazam"
```
