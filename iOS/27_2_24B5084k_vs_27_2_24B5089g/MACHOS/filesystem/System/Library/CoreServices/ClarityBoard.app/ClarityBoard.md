## ClarityBoard

> `/System/Library/CoreServices/ClarityBoard.app/ClarityBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x299d90` | `0x29ad70` | **`+0xfe0`** |
| `__TEXT.__const` | `0x282b8` | `0x28368` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x19768` | `0x19808` | **`+0xa0`** |
| `__DATA.__bss` | `0x65c0` | `0x6650` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x106f0` | `0x1076a` | **`+0x7a`** |
| `__TEXT.__swift5_reflstr` | `0x3753` | `0x37a3` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x3fa8` | `0x3ff0` | **`+0x48`** |
| `__TEXT.__cstring` | `0x3618` | `0x3658` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0xc540` | `0xc580` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x289c` | `0x28d0` | **`+0x34`** |
| `__TEXT.__constg_swiftt` | `0x3f58` | `0x3f84` | **`+0x2c`** |
| `__TEXT.__eh_frame` | `0x3164` | `0x318c` | **`+0x28`** |
| `__DATA.__data` | `0x8568` | `0x8588` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x12e75` | `0x12e95` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x1884` | `0x18a4` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x1208` | `0x1220` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x4450` | `0x4460` | **`+0x10`** |
| `__DATA.__objc_data` | `0x4bf8` | `0x4c00` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x4260` | `0x4268` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2238` | `0x2240` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1680` | `0x1688` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x300` | `0x304` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x320` | `0x324` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-170.3.0.0.0
+170.3.1.0.0

-  Functions: 5856
-  Symbols:   2203
-  CStrings:  4395
+  Functions: 5883
+  Symbols:   2207
+  CStrings:  4398
Symbols:
+ _$s22ClarityBoardFoundation15ForceQuitActionO7perform3app15clearCurrentApp7dismissSbAA0D20QuittableApplication_pSg_yyXEyyXEtFZ
+ _$s22ClarityBoardFoundation25ForceQuittableApplicationMp
+ _$s22ClarityBoardFoundation25ForceQuittableApplicationP16bundleIdentifierSSvgTq
+ _$s22ClarityBoardFoundation25ForceQuittableApplicationP9terminate10withReason10completionySS_ySbctFTq
CStrings:
+ "FORCE_QUIT_MESSAGE"
+ "FORCE_QUIT_TITLE"
+ "setCornerRadiusConfiguration:"
```
