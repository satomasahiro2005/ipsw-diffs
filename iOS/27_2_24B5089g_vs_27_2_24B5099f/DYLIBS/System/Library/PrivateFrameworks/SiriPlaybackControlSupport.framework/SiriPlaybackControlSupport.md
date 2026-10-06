## SiriPlaybackControlSupport

> `/System/Library/PrivateFrameworks/SiriPlaybackControlSupport.framework/SiriPlaybackControlSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83764` | `0x85674` | **`+0x1f10`** |
| `__TEXT.__oslogstring` | `0x5fac` | `0x616c` | **`+0x1c0`** |
| `__AUTH_CONST.__const` | `0x8078` | `0x8150` | **`+0xd8`** |
| `__TEXT.__const` | `0x4bf2` | `0x4ca2` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x1a2e` | `0x1ad4` | **`+0xa6`** |
| `__TEXT.__constg_swiftt` | `0x1dc0` | `0x1e18` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0x157c` | `0x15d0` | **`+0x54`** |
| `__DATA.__data` | `0x1100` | `0x1138` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1e60` | `0x1e90` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a0` | `0x4c0` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x10f0` | `0x1110` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x21e0` | `0x2200` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xf68` | `0xf80` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x314` | `0x31c` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x54` | `0x5c` | **`+0x8`** |

### Other Changes

```diff

-3605.13.1.0.0
+3605.16.2.1.1

-  Functions: 4284
-  Symbols:   1116
-  CStrings:  691
+  Functions: 4340
+  Symbols:   1130
+  CStrings:  695
Symbols:
+ _HMAccessoryCategoryTypeTelevisionSetTopBox
+ _HMAccessoryCategoryTypeTelevisionStreamingStick
+ _NSSelectorFromString
+ _OBJC_CLASS_$_HMMediaGroup
+ ___swift_closure_destructor.241Tm
+ _objc_retainAutorelease
+ _objc_retain_x28
+ _symbolic $s26SiriPlaybackControlSupport14AudioGroupTypeP
+ _symbolic $s26SiriPlaybackControlSupport15MediaSystemTypeP
+ _symbolic ______p 26SiriPlaybackControlSupport14AudioGroupTypeP
+ _symbolic ______p 26SiriPlaybackControlSupport15MediaSystemTypeP
+ _symbolic ______pSg 26SiriPlaybackControlSupport14AudioGroupTypeP
+ _symbolic ______pSg 26SiriPlaybackControlSupport15MediaSystemTypeP
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 26SiriPlaybackControlSupport14AudioGroupTypeP
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 26SiriPlaybackControlSupport15MediaSystemTypeP
- ___swift_closure_destructor.251Tm
CStrings:
+ "Accessory %s is a speaker in surround system %s"
+ "Accessory %s is in no media system and has no audio destination identifier"
+ "Accessory %s matched none of the %ld audio group(s)"
+ "HomeEntityMatchingService#accessories %s has deviceType %{public}s, which the predicate's %{public}s does not ask for, skipping..."
+ "HomeEntityMatchingService#accessories %s has no DeviceCategory for homekitType %{public}s, so it is untargetable by any predicate. Add the type to DeviceCategory.homekitToCategoryMap. Skipping..."
- "HomeEntityMatchingService#accessories deviceType doesn't match predicate, skipping..."
```
