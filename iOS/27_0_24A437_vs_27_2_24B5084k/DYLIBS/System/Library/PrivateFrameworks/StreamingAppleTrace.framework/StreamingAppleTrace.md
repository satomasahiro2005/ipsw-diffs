## StreamingAppleTrace

> `/System/Library/PrivateFrameworks/StreamingAppleTrace.framework/StreamingAppleTrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29024` | `0x2ba58` | **`+0x2a34`** |
| `__DATA.__bss` | `0x2590` | `0x2810` | **`+0x280`** |
| `__AUTH_CONST.__const` | `0x1838` | `0x1a88` | **`+0x250`** |
| `__TEXT.__const` | `0x1ce0` | `0x1f10` | **`+0x230`** |
| `__TEXT.__swift5_fieldmd` | `0x8a8` | `0xa00` | **`+0x158`** |
| `__TEXT.__cstring` | `0x5bd` | `0x6fb` | **`+0x13e`** |
| `__TEXT.__eh_frame` | `0x1898` | `0x19b8` | **`+0x120`** |
| `__TEXT.__swift5_reflstr` | `0x4c0` | `0x59a` | **`+0xda`** |
| `__AUTH_CONST.__objc_const` | `0xcd8` | `0xdb0` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x40` | `0xfb` | **`+0xbb`** |
| `__TEXT.__constg_swiftt` | `0xac0` | `0xb6c` | **`+0xac`** |
| `__AUTH.__data` | `0xbd8` | `0xc80` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0xa28` | `0xac0` | **`+0x98`** |
| `__AUTH_CONST.__auth_got` | `0x8f0` | `0x950` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x7be` | `0x810` | **`+0x52`** |
| `__DATA.__data` | `0x5f0` | `0x628` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0xc0` | `0xd8` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x14c` | `0x160` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0xa0` | `0xb4` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x22c` | `0x238` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x68` | `0x70` | **`+0x8`** |

### Other Changes

```diff

-113.0.0.0.0
+120.0.0.502.1

-  Functions: 788
-  Symbols:   441
-  CStrings:  74
+  Functions: 854
+  Symbols:   459
+  CStrings:  84
Symbols:
+ __DATA__TtC19StreamingAppleTrace14FrameAssembler
+ __IVARS__TtC19StreamingAppleTrace14FrameAssembler
+ __METACLASS_DATA__TtC19StreamingAppleTrace14FrameAssembler
+ ___swift_closure_destructor.106Tm
+ _associated conformance 19StreamingAppleTrace0abC5ErrorO10Foundation09LocalizedD0AAs0D0
+ _associated conformance 19StreamingAppleTrace13TimeSyncChunkO6SourceOSHAASQ
+ _ktrace_file_align_next
+ _objc_release_x26
+ _swift_arrayDestroy
+ _swift_retain_x25
+ _symbolic _____ 19StreamingAppleTrace13TimeSyncChunkO
+ _symbolic _____ 19StreamingAppleTrace13TimeSyncChunkO5EntryV
+ _symbolic _____ 19StreamingAppleTrace13TimeSyncChunkO6HeaderV
+ _symbolic _____ 19StreamingAppleTrace13TimeSyncChunkO6SourceO
+ _symbolic _____ 19StreamingAppleTrace14FrameAssemblerC
+ _symbolic _____ s6UInt16V
+ _symbolic _____y_____ABG s18_DictionaryStorageC s6UInt32V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4DataV
+ _type_layout_string 19StreamingAppleTrace13TimeSyncChunkO5EntryV
+ _type_layout_string 19StreamingAppleTrace13TimeSyncChunkO6HeaderV
- ___swift_closure_destructor.101Tm
- _swift_retain_x8
CStrings:
+ "Configuration error: "
+ "Implausible frame size in header: frameSize="
+ "Insufficient data for frame: data.count="
+ "Invalid platform: "
+ "Invalid source: "
+ "Metadata unavailable"
+ "Multiple errors: "
+ "StreamingAppleTrace Time Sync Data"
+ "[onClose callback] discarding %ld byte(s) of an incomplete trailing frame"
+ "[onData callback] failed to parse chunk, finishing stream: %s [platform=%s, chunkLength=%ld, heldOver=%ld]"
+ "ktrace_file_append_chunk failed for tag 0x"
- "Insufficient data for frame"
```
