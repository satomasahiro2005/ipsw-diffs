## gamed

> `/usr/libexec/gamed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a5604` | `0x2a559c` | **`-0x68`** |
| `__TEXT.__oslogstring` | `0x19209` | `0x19239` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x4ab0` | `0x4ac0` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0xc7b0` | `0xc7a0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x2570` | `0x2578` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-821.0.20.0.0
+821.0.25.0.0

-  Functions: 12482
-  Symbols:   2578
-  CStrings:  10606
+  Functions: 12483
+  Symbols:   2579
+  CStrings:  10607
Symbols:
+ _$s16GameServicesCore18AchievementServiceC20resetAllAchievements5games11belongingToySay0aB03RefVyAG0A0_pGG_SayAIyAG6Player_pGGtYaKFTE
+ _$s16GameServicesCore18AchievementServiceC20resetAllAchievements5games11belongingToySay0aB03RefVyAG0A0_pGG_SayAIyAG6Player_pGGtYaKFTETu
+ _GKPathInsideImageCache
- _$s16GameServicesCore18AchievementServiceC13resetProgress12achievements11belongingToySay0aB03RefVyAG0D0_pGG_SayAIyAG6Player_pGGtYaKFTE
- _$s16GameServicesCore18AchievementServiceC13resetProgress12achievements11belongingToySay0aB03RefVyAG0D0_pGG_SayAIyAG6Player_pGGtYaKFTETu
CStrings:
+ "Refusing to cache image at path outside the image cache: %@"
```
