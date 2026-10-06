## GameCenterUI

> `/System/Library/PrivateFrameworks/GameCenterUI.framework/GameCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4cb8b8` | `0x4cc898` | **`+0xfe0`** |
| `__AUTH_CONST.__const` | `0x1ef78` | `0x1f0a8` | **`+0x130`** |
| `__TEXT.__objc_methlist` | `0x1d154` | `0x1d1f4` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x55320` | `0x553a0` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x58ec` | `0x595c` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x135a8` | `0x135f0` | **`+0x48`** |
| `__DATA.__data` | `0xfb50` | `0xfb70` | **`+0x20`** |
| `__TEXT.__const` | `0x28f14` | `0x28f34` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x1480` | `0x1468` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1a24` | `0x1a3c` | **`+0x18`** |
| `__AUTH.__data` | `0xfcd0` | `0xfce0` | **`+0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x118` | `0x128` | **`+0x10`** |
| `__TEXT.__cstring` | `0x17b6f` | `0x17b7f` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x29a1e` | `0x29a0e` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x107c` | `0x1080` | **`+0x4`** |

### Other Changes

```diff

-821.0.25.0.0
+821.1.8.0.0

-  Functions: 33708
-  Symbols:   20281
+  Functions: 33748
+  Symbols:   20304
Symbols:
+ +[GCFAchievement(GKChallenge) reportAchievements:withEligibleChallenges:withCompletionHandler:]
+ +[GCFAchievementDescription(UI) incompleteAchievementImage]
+ +[GCFAchievementDescription(UI) placeholderCompletedAchievementImage]
+ -[GCFAchievement(UIPrivate) imageURL]
+ -[GCFAchievement(UIPrivate) loadImageWithCompletionHandler:]
+ -[GCFAchievement(UIPrivate) showBanner]
+ -[GCFAchievementDescription(UI) loadImageWithCompletionHandler:]
+ -[GCFAchievementDescription(UI) loadImageWithTimeout:completionHandler:]
+ -[GCFAchievementDescription(UIPrivate) imageURL]
+ -[GCFAchievementDescription(UIPrivate) showBanner]
+ _OBJC_CLASS_$_GCFAchievement
+ _OBJC_CLASS_$_GCFAchievementDescription
+ __OBJC_$_CATEGORY_CLASS_METHODS_GCFAchievementDescription_$_UI
+ __OBJC_$_CATEGORY_GCFAchievementDescription_$_UI
+ __OBJC_$_CATEGORY_GCFAchievement_$_UIPrivate
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_GCFAchievement_$_UIPrivate
+ __OBJC_$_CLASS_METHODS_GCFAchievement(UIPrivate|GKChallenge)
+ __OBJC_$_INSTANCE_METHODS_GCFAchievementDescription(UI|UIPrivate)
+ ___50-[GCFAchievementDescription(UIPrivate) showBanner]_block_invoke
+ ___64-[GCFAchievementDescription(UI) loadImageWithCompletionHandler:]_block_invoke
+ ___72-[GCFAchievementDescription(UI) loadImageWithTimeout:completionHandler:]_block_invoke
+ ___72-[GCFAchievementDescription(UI) loadImageWithTimeout:completionHandler:]_block_invoke_2
+ ___72-[GCFAchievementDescription(UI) loadImageWithTimeout:completionHandler:]_block_invoke_3
+ ___block_descriptor_48_e8_32s40s_e36_v24?0"UIImage"8"GCFAchievement"16ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48s_e31_v32?0"GCFAchievement"8Q16^B24ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e36_v24?0"UIImage"8"GCFAchievement"16ls32l8s40l8s48l8s56l8
+ _symbolic SaySo14GCFAchievementCG
+ _symbolic SaySo14GCFAchievementCGIegr_
+ _symbolic So14GCFAchievementC
- ___block_descriptor_48_e8_32s40s_e35_v24?0"UIImage"8"GKAchievement"16ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48s_e30_v32?0"GKAchievement"8Q16^B24ls32l8s40l8s48l8
- ___block_descriptor_64_e8_32s40s48s56bs_e35_v24?0"UIImage"8"GKAchievement"16ls32l8s40l8s48l8s56l8
- _symbolic SaySo13GKAchievementCG
- _symbolic SaySo13GKAchievementCGIegr_
- _symbolic So13GKAchievementC
CStrings:
+ "v24@?0@\"UIImage\"8@\"GCFAchievement\"16"
+ "v32@?0@\"GCFAchievement\"8Q16^B24"
- "v24@?0@\"UIImage\"8@\"GKAchievement\"16"
- "v32@?0@\"GKAchievement\"8Q16^B24"
```
