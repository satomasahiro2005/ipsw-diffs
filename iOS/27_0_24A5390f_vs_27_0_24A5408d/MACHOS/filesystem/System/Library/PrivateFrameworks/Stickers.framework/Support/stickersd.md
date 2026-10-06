## stickersd

> `/System/Library/PrivateFrameworks/Stickers.framework/Support/stickersd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ec10` | `0x21670` | **`+0x2a60`** |
| `__TEXT.__eh_frame` | `0xedc` | `0x108c` | **`+0x1b0`** |
| `__DATA_CONST.__const` | `0xc50` | `0xdb0` | **`+0x160`** |
| `__TEXT.__const` | `0xd10` | `0xdf0` | **`+0xe0`** |
| `__DATA.__objc_const` | `0x8b8` | `0x990` | **`+0xd8`** |
| `__DATA.__data` | `0x898` | `0x950` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x588` | `0x618` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x700` | `0x790` | **`+0x90`** |
| `__DATA.__bss` | `0xa90` | `0xb10` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x270` | `0x2e4` | **`+0x74`** |
| `__TEXT.__oslogstring` | `0x10bc` | `0x111c` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x276` | `0x2b6` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x530` | `0x56c` | **`+0x3c`** |
| `__DATA_CONST.__auth_ptr` | `0x1f0` | `0x210` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x965` | `0x945` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x364` | `0x380` | **`+0x1c`** |
| `__TEXT.__swift_as_cont` | `0xb0` | `0xc4` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0x250` | `0x260` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x84` | `0x94` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x58` | `0x64` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x434` | `0x42a` | **`-0xa`** |
| `__DATA.__objc_data` | `0x708` | `0x710` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x310` | `0x318` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x54` | `0x58` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x58` | `0x5c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-87.0.0.0.0
+88.0.0.0.0

-  Functions: 468
-  Symbols:   489
-  CStrings:  274
+  Functions: 512
+  Symbols:   490
+  CStrings:  280
Symbols:
+ _$s8Stickers16StickerReindexerV35repairSpotlightSearchTextAttributesyyYaKF
+ _$s8Stickers16StickerReindexerV35repairSpotlightSearchTextAttributesyyYaKFTu
+ _objc_retain_x26
+ _swift_release_x24
- _swift_release_x22
- _swift_retain_x25
- _swift_retain_x27
CStrings:
+ "Running Spotlight searchText repair task"
+ "Spotlight searchText repair task failed: %@"
+ "_TtC9stickersd32SpotlightSearchTextRepairService"
+ "com.apple.stickersd.SpotlightSearchTextRepair"
+ "com.apple.stickersd.spotlightSearchTextRepairQueue"
+ "spotlight-searchtext-repair"
```
