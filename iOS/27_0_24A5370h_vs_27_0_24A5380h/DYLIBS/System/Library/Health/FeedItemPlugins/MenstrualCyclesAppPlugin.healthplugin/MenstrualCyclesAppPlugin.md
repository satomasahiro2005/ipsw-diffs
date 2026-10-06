## MenstrualCyclesAppPlugin

> `/System/Library/Health/FeedItemPlugins/MenstrualCyclesAppPlugin.healthplugin/MenstrualCyclesAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x54833c` | `0x55014c` | **`+0x7e10`** |
| `__DATA_DIRTY.__bss` | `0x8280` | `0x8a00` | **`+0x780`** |
| `__DATA_DIRTY.__data` | `0x70d8` | `0x76a8` | **`+0x5d0`** |
| `__DATA.__bss` | `0x226e8` | `0x22178` | **`-0x570`** |
| `__AUTH_CONST.__objc_const` | `0x1b1b8` | `0x1b508` | **`+0x350`** |
| `__AUTH_CONST.__const` | `0x19b78` | `0x19e68` | **`+0x2f0`** |
| `__TEXT.__const` | `0x266f4` | `0x269b4` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x17f16` | `0x18196` | **`+0x280`** |
| `__TEXT.__eh_frame` | `0xd5e8` | `0xd830` | **`+0x248`** |
| `__TEXT.__swift5_reflstr` | `0x11406` | `0x115f6` | **`+0x1f0`** |
| `__TEXT.__oslogstring` | `0xc87c` | `0xca3c` | **`+0x1c0`** |
| `__TEXT.__swift5_fieldmd` | `0xe258` | `0xe3f8` | **`+0x1a0`** |
| `__TEXT.__constg_swiftt` | `0x11bc8` | `0x11d58` | **`+0x190`** |
| `__AUTH.__objc_data` | `0xeda0` | `0xef28` | **`+0x188`** |
| `__TEXT.__unwind_info` | `0xe470` | `0xe5d0` | **`+0x160`** |
| `__AUTH.__data` | `0xce08` | `0xccd8` | **`-0x130`** |
| `__TEXT.__swift5_capture` | `0x4e58` | `0x4f2c` | **`+0xd4`** |
| `__DATA.__data` | `0xb938` | `0xb868` | **`-0xd0`** |
| `__DATA_DIRTY.__objc_data` | `0x2dd8` | `0x2e70` | **`+0x98`** |
| `__TEXT.__swift5_typeref` | `0xb3e4` | `0xb45e` | **`+0x7a`** |
| `__TEXT.__objc_methlist` | `0x594c` | `0x58f4` | **`-0x58`** |
| `__DATA_DIRTY.__common` | `0x448` | `0x498` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x5600` | `0x5628` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x8b0` | `0x8d8` | **`+0x28`** |
| `__DATA.__objc_stublist` | `0xc0` | `0xd8` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x1828` | `0x183c` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0xec4` | `0xed8` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x410` | `0x420` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x328` | `0x334` | **`+0xc`** |
| `__DATA.__common` | `0xb50` | `0xb48` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x3190` | `0x3188` | **`-0x8`** |
| `__DATA_CONST.__objc_catlist2` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xc20` | `0xc28` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3578` | `0x3580` | **`+0x8`** |
| `__TEXT.__swift5_assocty` | `0x1e80` | `0x1e88` | **`+0x8`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 20343
-  Symbols:   767
-  CStrings:  2967
+  Functions: 20454
+  Symbols:   768
+  CStrings:  2982
Symbols:
+ _HKMCAddMenopauseStageOnboardingEligibilityDateKey
+ _HKMCPrivateMetadataKeyConfirmedDeviationUserDeclinedMenopauseStageAtConfirmation
+ _OBJC_METACLASS_$__TtC18HealthExperienceUI39OnboardingTopContentShortViewController
- _memset
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "Add Menopause Stage"
+ "AddMenopauseStageOnboardingEligibilityDateInputSignal"
+ "DeletePerimenopause"
+ "DeviationEscalation"
+ "Failed to apply pending conflict deletions after menopause save: "
+ "Failed to delete deferred conflict samples after menopause save: "
+ "Failed to delete superseded perimenopause sample after menopause save: "
+ "MenstrualCyclesAppPlugin.CycleFactorsLearnMoreHostingController"
+ "MenstrualCyclesAppPlugin.MenopauseStageSelectionViewController"
+ "MenstrualCyclesAppPlugin.StaticMenopauseModelProvider"
+ "MenstrualCyclesAppPlugin/LearnMoreView.swift"
+ "MenstrualCyclesAppPlugin/MenopauseStageSelectionViewController.swift"
+ "No eligible flagged deviations or onboarding eligibility"
+ "ONBOARDING_MENOPAUSE_SELECTION_TITLE"
+ "PerimenopauseAgeRange"
+ "PerimenopauseStartConfirm"
+ "PerimenopauseYear"
+ "Saved menopause + deferred perimenopause samples"
+ "[%s] Error submitting room analytics event: %s"
+ "[%s] Failed to submit menopause edit analytics event: %s"
+ "[%s] Failed to submit menopause onboarding analytics event: %s"
+ "[%{private}s] Couldn't get onboarding eligibility date, %{private}s"
+ "[%{public}s] Missing navigation controller for inline menopause onboarding"
+ "[%{public}s] Refresh fetch failed: %{public}s"
+ "[ContentStateManager] Failed to clear key %{private}s: %@"
+ "init(title:detailText:heroImage:heroMaxHeight:linkButtonText:linkButtonAccessibilityIdentifier:)"
- "Add Bleeding After Menopause"
- "Add Perimenopause"
- "Confirm End Perimenopause"
- "Delete Bleeding After Menopause"
- "Edit Bleeding After Menopause"
- "End Perimenopause"
- "EndPerimenopause"
- "MenstrualCyclesAppPlugin.DeviationsMenopauseSelectionViewController"
- "MenstrualCyclesAppPlugin/DeviationsMenopauseSelectionViewController.swift"
- "No eligible flagged deviations"
- "moonphase.waning.gibbous.inverse"
```
