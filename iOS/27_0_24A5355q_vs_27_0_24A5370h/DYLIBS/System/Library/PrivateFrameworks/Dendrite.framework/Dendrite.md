## Dendrite

> `/System/Library/PrivateFrameworks/Dendrite.framework/Dendrite`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c420` | `0x701d4` | **`+0x3db4`** |
| `__TEXT.__eh_frame` | `0x5088` | `0x5238` | **`+0x1b0`** |
| `__AUTH_CONST.__objc_const` | `0x2058` | `0x2170` | **`+0x118`** |
| `__TEXT.__cstring` | `0x29f2` | `0x2ae8` | **`+0xf6`** |
| `__AUTH.__data` | `0x4a0` | `0x558` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x1e68` | `0x1ed8` | **`+0x70`** |
| `__TEXT.__const` | `0x5312` | `0x5370` | **`+0x5e`** |
| `__TEXT.__swift5_fieldmd` | `0x17e8` | `0x1828` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0xd00` | `0xd38` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x1075` | `0x10ac` | **`+0x37`** |
| `__TEXT.__swift5_typeref` | `0x15a0` | `0x15cd` | **`+0x2d`** |
| `__TEXT.__constg_swiftt` | `0x248c` | `0x24b8` | **`+0x2c`** |
| `__DATA_CONST.__objc_selrefs` | `0x280` | `0x2a8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x4420` | `0x4440` | **`+0x20`** |
| `__DATA.__data` | `0x1038` | `0x1028` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x1cb8` | `0x1cc8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2bc` | `0x2c0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1fc` | `0x200` | **`+0x4`** |

### Other Changes

```diff

-6.4.0.0.0
+6.7.0.0.0

-  Functions: 2377
-  Symbols:   893
-  CStrings:  190
+  Functions: 2406
+  Symbols:   897
+  CStrings:  196
Symbols:
+ _NSURLCreationDateKey
+ __DATA__TtC8Dendrite19CachedStreamStorage
+ __IVARS__TtC8Dendrite19CachedStreamStorage
+ __METACLASS_DATA__TtC8Dendrite19CachedStreamStorage
+ _swift_release_x11
+ _symbolic Si6offset______7elementt 10Foundation3URLV
+ _symbolic _____ 8Dendrite19CachedStreamStorageC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s6UInt64V
- _CFAbsoluteTimeGetCurrent
- __swift_stdlib_strtod_clocale
- _swift_bridgeObjectRelease_n
- _swift_release_x12
CStrings:
+ " — no birthtime available at "
+ "Deleting orphan renumber staging file "
+ "Failed to delete orphan staging file "
+ "Skipping missing segment "
+ "dendrite: counter exhausted; renumbering "
+ "nextSegmentName()"
+ "renumberAllSegments()"
- " did not parse as a date"
```
