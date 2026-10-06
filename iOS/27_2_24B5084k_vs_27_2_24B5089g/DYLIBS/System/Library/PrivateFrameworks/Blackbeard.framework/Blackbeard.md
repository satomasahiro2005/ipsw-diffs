## Blackbeard

> `/System/Library/PrivateFrameworks/Blackbeard.framework/Blackbeard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e8288` | `0x7e9bf0` | **`+0x1968`** |
| `__DATA_DIRTY.__bss` | `0x11430` | `0x116b0` | **`+0x280`** |
| `__DATA.__bss` | `0x16a50` | `0x167e0` | **`-0x270`** |
| `__TEXT.__oslogstring` | `0x46eb` | `0x479b` | **`+0xb0`** |
| `__TEXT.__const` | `0x27eb4` | `0x27f24` | **`+0x70`** |
| `__DATA_DIRTY.__data` | `0x9bb8` | `0x9c18` | **`+0x60`** |
| `__AUTH.__data` | `0x26d0` | `0x2678` | **`-0x58`** |
| `__TEXT.__eh_frame` | `0x409e4` | `0x40994` | **`-0x50`** |
| `__TEXT.__swift5_typeref` | `0x7238c` | `0x723c2` | **`+0x36`** |
| `__DATA.__data` | `0x8f98` | `0x8f78` | **`-0x20`** |
| `__TEXT.__cstring` | `0x95eb` | `0x960b` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x17308` | `0x172f8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x8b10` | `0x8b08` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x4f70` | `0x4f68` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0xe664` | `0xe668` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x4fb4` | `0x4fb0` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x1a24` | `0x1a20` | **`-0x4`** |

### Other Changes

```diff

-2027.1.50.0.1
+2027.1.54.0.0

-  Functions: 23636
-  Symbols:   7118
-  CStrings:  1102
+  Functions: 23640
+  Symbols:   7116
+  CStrings:  1104
Symbols:
+ _symbolic _____6layout______7artwork_____5style_____Sg5titleAH8subtitleAH7captionSb11isCompletedSSSg27completedAccessibilityLabel_____Sg19primaryActionButtonAP09secondarymN0_____Sg10customViewt 15FitnessCanvasUI24FullWidthStageViewLayoutV 10Blackbeard17ArtworkDescriptorV AA0defG5StyleO 10Foundation16AttributedStringV AD012ActionButtonK0V AD0gK0O
+ _symbolic _____Sg15attributedTitle_AB0A4Textt 10Foundation16AttributedStringV
+ _symbolic y___________SbSgtYaKc 9SeymourUI27WorkoutSessionConfigurationV 0A4Core010StructuredC0V
- _symbolic Say_____G 10Blackbeard11ItemContextO
- _symbolic _____6layout______7artwork_____5style_____Sg5titleAH8subtitleAH7caption_____Sg19primaryActionButtonAM09secondaryhI0_____Sg10customViewt 15FitnessCanvasUI24FullWidthStageViewLayoutV 10Blackbeard17ArtworkDescriptorV AA0defG5StyleO 10Foundation16AttributedStringV AD012ActionButtonK0V AD0gK0O
- _symbolic _____Sg15attributedTitle_AB0A4TextSS19localizedDoneStringSS0d4MoreF0t 10Foundation16AttributedStringV
- _symbolic _____ySay_____GG s23_ContiguousArrayStorageC 10Blackbeard11ItemContextO
- _symbolic y___________tYaKc 9SeymourUI27WorkoutSessionConfigurationV 0A4Core010StructuredC0V
CStrings:
+ "Dropping route to %{public}s, which this platform's navigation does not offer"
+ "Ignoring selection of %{public}s, which this platform's navigation does not offer"
+ "layout artwork style title subtitle caption isCompleted completedAccessibilityLabel primaryActionButton secondaryActionButton customView "
- "layout artwork style title subtitle caption primaryActionButton secondaryActionButton customView "
```
