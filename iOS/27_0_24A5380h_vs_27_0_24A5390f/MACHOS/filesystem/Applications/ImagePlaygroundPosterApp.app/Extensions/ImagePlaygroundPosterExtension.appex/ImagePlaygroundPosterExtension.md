## ImagePlaygroundPosterExtension

> `/Applications/ImagePlaygroundPosterApp.app/Extensions/ImagePlaygroundPosterExtension.appex/ImagePlaygroundPosterExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19838` | `0x1d594` | **`+0x3d5c`** |
| `__DATA.__bss` | `0x400` | `0x680` | **`+0x280`** |
| `__TEXT.__eh_frame` | `0x1020` | `0x12a0` | **`+0x280`** |
| `__TEXT.__const` | `0x5d4` | `0x7b4` | **`+0x1e0`** |
| `__TEXT.__auth_stubs` | `0x11e0` | `0x1370` | **`+0x190`** |
| `__DATA.__data` | `0x750` | `0x8b0` | **`+0x160`** |
| `__DATA_CONST.__const` | `0x6a0` | `0x7b8` | **`+0x118`** |
| `__TEXT.__swift5_reflstr` | `0x156` | `0x266` | **`+0x110`** |
| `__DATA.__objc_const` | `0xe38` | `0xf18` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x5d8` | `0x6b8` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x89a` | `0x96a` | **`+0xd0`** |
| `__DATA_CONST.__auth_got` | `0x8f8` | `0x9c0` | **`+0xc8`** |
| `__DATA.__objc_data` | `0x558` | `0x618` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x3d4` | `0x48c` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0x158` | `0x210` | **`+0xb8`** |
| `__TEXT.__objc_methname` | `0x1f11` | `0x1f79` | **`+0x68`** |
| `__TEXT.__swift5_capture` | `0x214` | `0x27c` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x56a` | `0x5c0` | **`+0x56`** |
| `__TEXT.__cstring` | `0x575` | `0x5c5` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x228` | `0x270` | **`+0x48`** |
| `__DATA_CONST.__auth_ptr` | `0x1c8` | `0x200` | **`+0x38`** |
| `__TEXT.__objc_stubs` | `0x940` | `0x960` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x68` | `0x80` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x20` | `0x34` | **`+0x14`** |
| `__DATA.__common` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x678` | `0x680` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x44` | `0x4c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x20` | `0x24` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-193.1.0.0.0
+194.1.0.0.0
+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

-  Functions: 312
-  Symbols:   198
-  CStrings:  463
+  Functions: 366
+  Symbols:   207
+  CStrings:  476
Symbols:
+ _OBJC_CLASS_$_LSApplicationRecord
+ __swift_stdlib_bridgeErrorToNSError
+ _objc_retain_x28
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_endAccess
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getSingletonMetadata
+ _swift_retain_x26
+ _swift_retain_x27
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_updateClassMetadata2
- _objc_retain_x27
- _swift_bridgeObjectRetain_n
- _swift_retain_x25
CStrings:
+ "$__lazy_storage_$_servicesFetcher"
+ "Couldn't emit engagement signal to SuggestedImage. Underlying error: %@"
+ "Failed to read AssetRequest from decoded poster recipe."
+ "Image Playground app is not installed, not updating descriptors"
+ "associatedAssetRequest"
+ "com.apple.GenerativePlaygroundApp"
+ "hasSentEditorAppeared"
+ "initWithBundleIdentifier:allowPlaceholder:error:"
+ "library"
+ "pregenerated"
+ "sourceType"
+ "suggestedImageProvider"
+ "userCreated"
```
