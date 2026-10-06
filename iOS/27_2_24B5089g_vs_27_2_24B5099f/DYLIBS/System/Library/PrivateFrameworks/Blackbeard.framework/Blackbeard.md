## Blackbeard

> `/System/Library/PrivateFrameworks/Blackbeard.framework/Blackbeard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e9bf0` | `0x7ef150` | **`+0x5560`** |
| `__TEXT.__unwind_info` | `0x172f8` | `0x16f20` | **`-0x3d8`** |
| `__AUTH_CONST.__const` | `0x278e8` | `0x277d0` | **`-0x118`** |
| `__TEXT.__cstring` | `0x960b` | `0x955b` | **`-0xb0`** |
| `__TEXT.__eh_frame` | `0x40994` | `0x40a14` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x479b` | `0x481b` | **`+0x80`** |
| `__DATA.__data` | `0x8f78` | `0x8fe8` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x723c2` | `0x72418` | **`+0x56`** |
| `__TEXT.__swift5_capture` | `0xe668` | `0xe624` | **`-0x44`** |
| `__DATA_CONST.__objc_selrefs` | `0x1158` | `0x1190` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x4fb0` | `0x4f80` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x8b08` | `0x8b30` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x6a08` | `0x6a28` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x4f68` | `0x4f80` | **`+0x18`** |
| `__DATA.__bss` | `0x167e0` | `0x167f0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x9c18` | `0x9c08` | **`-0x10`** |
| `__TEXT.__const` | `0x27f24` | `0x27f34` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x7908` | `0x7914` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x1bf8` | `0x1bec` | **`-0xc`** |
| `__AUTH.__objc_data` | `0x8d0` | `0x8d8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-2027.1.54.0.0
+2027.1.63.0.0

-  Functions: 23640
-  Symbols:   7116
-  CStrings:  1104
+  Functions: 23650
+  Symbols:   7120
+  CStrings:  1100
Symbols:
+ _OBJC_CLASS_$_UIButton
+ ___swift_closure_destructor.107Tm
+ _get_witness_table 14FitnessAppRoot18TabBarItemProtocolRzl10Blackbeard0cF0OAaBHPyHC
+ _symbolic SaySo13UIMenuElementCG
+ _symbolic _____4item______7weekdayt 18FitnessWorkoutPlan0bC13ScheduledItemV AA0bC7WeekdayO
+ _symbolic _____Say_____G_SiyyScMYcctScMYcc 20FitnessPlayerService35ExerciseVideoCarouselViewControllerC 10Foundation3URLV
+ _symbolic _____Sg 10Foundation4DataV
+ _symbolic _____Sg15attributedTitle_AB0A4TextSSSg19localizedDoneStringAE0d4MoreF0t 10Foundation16AttributedStringV
+ _symbolic yyScMYcc
- ___swift_closure_destructor.30Tm
- ___swift_closure_destructor.72Tm
- _symbolic _____4item______7weekdaySi5indext 18FitnessWorkoutPlan0bC13ScheduledItemV AA0bC7WeekdayO
- _symbolic _____Say_____G_SitScMYcc 20FitnessPlayerService35ExerciseVideoCarouselViewControllerC 10Foundation3URLV
- _symbolic _____Sg15attributedTitle_AB0A4Textt 10Foundation16AttributedStringV
CStrings:
+ "Could not determine supported-watch availability (%{public}s); searching for the watch rather than starting standalone"
+ "Failed to observe Bluetooth heart rate devices: %{public}@"
+ "[SampleContentComposer] Failed constructing root url"
- "Failed to record heart rate device availability: %{public}s"
- "MenuBar Navigate to Explore"
- "MenuBar Navigate to For You"
- "MenuBar Navigate to Library"
- "MenuBar Navigate to Search"
- "MenuBar Navigate to Workout Plans"
- "[SampleContentComposer] Failed constructing explore url"
```
