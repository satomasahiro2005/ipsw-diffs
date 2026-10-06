## ExpressiveEmbedded

> `/System/ExclaveKit/System/Library/Frameworks/ExpressiveEmbedded.framework/ExpressiveEmbedded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c98` | `0x3b10` | **`-0x188`** |
| `__TEXT.__eh_frame` | `0xb48` | `0xbb0` | **`+0x68`** |
| `__TEXT.__cstring` | `0x4cd` | `0x4ed` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2b0` | `0x2c8` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__TEXT.__const`

### Other Changes

```diff

-27.0.0.0.0
+28.0.0.0.0

-  Functions: 76
-  Symbols:   96
-  CStrings:  31
+  Functions: 79
+  Symbols:   99
+  CStrings:  32
Symbols:
+ _$es12MetadataKindO21__derived_enum_equalsySbAB_ABtFZ
+ _$es12MetadataKindO8metadataABSgSV_tcfC
+ _$es17_errorBoxContentsySV4type_SV11conformanceSV5valuetSVF
+ _$es29ExistentialTypeRepresentationO18projectOpaqueValue33_8BFEAB69C69C8B87ED137407D82370D4LL_14storedMetadataS2V_SVtF
+ _$es29ExistentialTypeRepresentationO7projectySV8metadata_SV5valuetSVF
+ _$es7tryCast33_8BFEAB69C69C8B87ED137407D82370D4LL3dst0J8Metadata3src0lK013takeOnSuccesss07DynamicB6ResultABLLOSv_S3VSbtF
+ __swift_embedded_metadata_get_vwt_flags
- _$es17_errorBoxContentsySV4type_SV11conformanceSv5valuetSVF
- __swift_embedded_existential_destroy
- __swift_embedded_existential_init_with_copy
- __swift_embedded_existential_init_with_take
CStrings:
+ "Swift/EmbeddedCasting.swift"
```
