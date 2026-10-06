## VisionCore

> `/System/Library/PrivateFrameworks/VisionCore.framework/VisionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40d70` | `0x41488` | **`+0x718`** |
| `__AUTH.__objc_data` | `0x500` | `0x1e0` | **`-0x320`** |
| `__DATA_DIRTY.__objc_data` | `0x14f0` | `0x1810` | **`+0x320`** |
| `__TEXT.__const` | `0x420` | `0x560` | **`+0x140`** |
| `__DATA.__bss` | `0x2a0` | `0x3a0` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x580` | `0x640` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0xbb8` | `0xc48` | **`+0x90`** |
| `__TEXT.__cstring` | `0x5865` | `0x58ee` | **`+0x89`** |
| `__TEXT.__constg_swiftt` | `0x184` | `0x1d0` | **`+0x4c`** |
| `__TEXT.__swift5_reflstr` | `0x51` | `0x84` | **`+0x33`** |
| `__TEXT.__swift5_fieldmd` | `0xac` | `0xd4` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x9a` | `0xc0` | **`+0x26`** |
| `__DATA.__data` | `0x400` | `0x420` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x5e0` | `0x5f8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x1720` | `0x1730` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x78` | `0x80` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xc` | `0x14` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x4060` | `0x405c` | **`-0x4`** |

### Other Changes

```diff

-10.0.34.0.0
+10.0.37.0.0

-  Functions: 1281
-  Symbols:   3162
-  CStrings:  711
+  Functions: 1300
+  Symbols:   3178
+  CStrings:  714
Symbols:
+ _CVBufferPropagateAttachments
+ _CVPixelBufferGetHeightOfPlane
+ _CVPixelBufferGetPlaneCount
+ ___swift_memcpy17_8
+ _associated conformance 10VisionCore0aB5ErrorO10Foundation09LocalizedC0AAs0C0
+ _get_enum_tag_for_layout_string 10VisionCore0aB5ErrorO
+ _swift_allocError
+ _swift_allocObject
+ _swift_bridgeObjectRetain
+ _swift_cvw_enumFn_getEnumTag
+ _swift_getWitnessTable
+ _symbolic SS
+ _symbolic _____ 10VisionCore0aB5ErrorO
+ _symbolic _____ s5Int32V
+ _symbolic _____yyp_yptG s23_ContiguousArrayStorageC
+ _type_layout_string 10VisionCore0aB5ErrorO
CStrings:
+ "Failed to lock destination pixel buffer: "
+ "Failed to lock source pixel buffer: "
+ "PixelBuffer creation failed with code "
```
