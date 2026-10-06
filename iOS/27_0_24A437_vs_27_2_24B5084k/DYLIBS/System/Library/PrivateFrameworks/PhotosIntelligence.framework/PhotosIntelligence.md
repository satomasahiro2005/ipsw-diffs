## PhotosIntelligence

> `/System/Library/PrivateFrameworks/PhotosIntelligence.framework/PhotosIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6461b8` | `0x64982c` | **`+0x3674`** |
| `__AUTH_CONST.__const` | `0x4e928` | `0x4f4e0` | **`+0xbb8`** |
| `__TEXT.__swift5_capture` | `0xd9b8` | `0xde70` | **`+0x4b8`** |
| `__DATA.__bss` | `0x3ecc0` | `0x3edc0` | **`+0x100`** |
| `__TEXT.__const` | `0x3c058` | `0x3c0d8` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x25c95` | `0x25d15` | **`+0x80`** |
| `__TEXT.__cstring` | `0x24f13` | `0x24f83` | **`+0x70`** |
| `__DATA.__data` | `0x8a50` | `0x8ab0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x18278` | `0x182b8` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x12730` | `0x12760` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1fa8` | `0x1fd8` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x110a3` | `0x110d3` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x372fc` | `0x3731c` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xe440` | `0xe460` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x31e8` | `0x3200` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x18d0` | `0x18e8` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x11220` | `0x11238` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x49a8` | `0x49b8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x5b34` | `0x5b44` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x2d8c` | `0x2d94` | **`+0x8`** |

### Other Changes

```diff

-912.0.235.0.0
+916.40.110.0.0

-  Functions: 42063
-  Symbols:   9895
-  CStrings:  6138
+  Functions: 42175
+  Symbols:   9899
+  CStrings:  6143
Symbols:
+ ___swift_closure_destructor.816Tm
+ _symbolic Say_____G 10Foundation11JSONEncoderC16OutputFormattingV
+ _symbolic _____Sg 29GenerativeFunctionsFoundation6SchemaV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation11JSONEncoderC16OutputFormattingV
CStrings:
+ "%s: could not build exclusive operand"
+ "%s: failed to build cardinality operand"
+ "%s: failed to build exclusive operand"
+ "%s: failed to build people operands"
+ "%s: fetch found %ld matching assets"
+ "%s: fetch returned %ld assets pre-dedupe, %ld post-dedupe (dedupe=%{bool}d)"
+ "%s: no assets matched curation properties"
+ "%s: no curation operand available"
+ ", includeSubgroups="
+ "Failed to format JSON schema"
+ "LEO-based fetch initiated: %s, dedupe=%{bool}d, limit=%s"
+ "PNIncludeSchemaInStorytellerPrompt"
+ "Unsupported scene curation property: %lu"
+ "You must produce a JSON object matching exactly this schema:\n"
+ "[DebugAlbum] '%s' has %ld assets. Only using first %ld assets."
+ "type=group, peopleCount="
- " includeSubgroups="
- "%s: Before processing: %ld, after: %ld (dedupe=%{bool}d)"
- "Could not build exclusive operand for person %s"
- "Group: failed to build cardinality operand"
- "Group: failed to build exclusive operand"
- "Group: failed to build people operands"
- "Person %s (%s): no assets matched curation properties"
- "Person %s (%s): query failed: %@"
- "Scene curation properties "
- "Scene curation properties %lu: no matching assets"
- "Scene query failed for curation properties %lu: %@"
```
