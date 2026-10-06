## ScreenTimeUI

> `/System/Library/PrivateFrameworks/ScreenTimeUI.framework/ScreenTimeUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68a48` | `0x69aa4` | **`+0x105c`** |
| `__TEXT.__swift5_typeref` | `0x60e0` | `0x623a` | **`+0x15a`** |
| `__DATA.__data` | `0x1560` | `0x15b0` | **`+0x50`** |
| `__TEXT.__const` | `0x3064` | `0x3014` | **`-0x50`** |
| `__TEXT.__cstring` | `0x2e8a` | `0x2eba` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1700` | `0x1728` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x1750` | `0x1778` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1678` | `0x16a0` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x2bc8` | `0x2be8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xb88` | `0xba8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1920` | `0x1940` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x8fd` | `0x91d` | **`+0x20`** |
| `__DATA.__bss` | `0x1950` | `0x1940` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x474` | `0x484` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x970` | `0x97c` | **`+0xc`** |
| `__AUTH.__data` | `0xb20` | `0xb28` | **`+0x8`** |

### Other Changes

```diff

-655.1.6.1.0
+655.1.9.1.0

-  Functions: 2020
-  Symbols:   1969
-  CStrings:  528
+  Functions: 2030
+  Symbols:   1976
+  CStrings:  529
Symbols:
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$_NSUserDefaults
+ ___swift_closure_destructor.13Tm
+ ___swift_closure_destructor.89Tm
+ _get_witness_table 7SwiftUI6HStackVyAA12TupleContentVyAA08ModifiedE0VyAGyAGyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA016_ForegroundStyleK0VyAA017HierarchicalShapeN0VGGAA023AccessibilityAttachmentK0VG_AA6VStackVyAA012_ConditionalE0VyAEyAA4TextV_AGyA3_AA14_PaddingLayoutVGQPGAEyA3__A1_yA6_AA12ProgressViewVyAA05EmptyY0VA11_GGQPGGGAA6SpacerVAGyAA0Y0PAAE06buttonN0yQrqd__AA015PrimitiveButtonN0Rd__lFQOyAA6ButtonVyAGyAiUGG_AA011PlainButtonN0VQo_AXGSgQPGGAAA19_HPyHC
+ _keypath_set.55Tm
+ _symbolic _____yAAyAAy__________y_____SgGG_____y_____GG_____G______y_____y_____y______AAyAQ_____GQPGAPyAQ_AOyAS_____y_____AVGGQPGGG_____AAy_____y_____yAAyAbJGG______Qo_ALGSgt 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleI0V AA017HierarchicalShapeL0V AA023AccessibilityAttachmentI0V AA6VStackV AA012_ConditionalD0V AA05TupleD0V AA4TextV AA14_PaddingLayoutV AA12ProgressViewV AA05EmptyX0V AA6SpacerV AA0X0PAAE06buttonL0yQrqd__AA015PrimitiveButtonL0Rd__lFQO AA6ButtonV AA011PlainButtonL0V
+ _symbolic _____y___________y_____yADyADy__________y_____SgGG_____y_____GG_____G______y_____yACy______ADyAS_____GQPGACyAS_ARyAU_____y_____AXGGQPGGG_____ADy_____y_____yADyAeMGG______Qo_AOGSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA08ModifiedI0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleO0V AA017HierarchicalShapeR0V AA023AccessibilityAttachmentO0V AA6VStackV AA012_ConditionalI0V AA4TextV AA08_PaddingG0V AA08ProgressD0V AA05EmptyD0V AA6SpacerV AA0D0PAAE06buttonR0yQrqd__AA015PrimitiveButtonR0Rd__lFQO AA6ButtonV AA011PlainButtonR0V
+ _symbolic _____y__________y_____GG 7SwiftUI15ModifiedContentV AA5ImageV AA24_ForegroundStyleModifierV AA017HierarchicalShapeG0V
+ _symbolic _____y_____y__________y_____GGG 7SwiftUI6ButtonV AA15ModifiedContentV AA5ImageV AA24_ForegroundStyleModifierV AA017HierarchicalShapeH0V
+ _symbolic _____y_____y_____yAAy__________y_____GGG______Qo______G 7SwiftUI15ModifiedContentV AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonG0Rd__lFQO AA0I0V AA5ImageV AA011_ForegroundG8ModifierV AA017HierarchicalShapeG0V AA05PlainiG0V AA023AccessibilityAttachmentL0V
+ _symbolic _____y_____y_____yAAy__________y_____GGG______Qo______GSg 7SwiftUI15ModifiedContentV AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonG0Rd__lFQO AA0I0V AA5ImageV AA011_ForegroundG8ModifierV AA017HierarchicalShapeG0V AA05PlainiG0V AA023AccessibilityAttachmentL0V
+ _symbolic _____y_____y_____yACyACy__________y_____SgGG_____y_____GG_____G______y_____yABy______ACyAR_____GQPGAByAR_AQyAT_____y_____AWGGQPGGG_____ACy_____y_____yACyAdLGG______Qo_ANGSgQPGG 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleK0V AA017HierarchicalShapeN0V AA023AccessibilityAttachmentK0V AA6VStackV AA012_ConditionalE0V AA4TextV AA14_PaddingLayoutV AA12ProgressViewV AA05EmptyY0V AA6SpacerV AA0Y0PAAE06buttonN0yQrqd__AA015PrimitiveButtonN0Rd__lFQO AA6ButtonV AA011PlainButtonN0V
+ _symbolic _____y_____y_____y__________y_____GGG______Qo_ 7SwiftUI4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonE0Rd__lFQO AA0G0V AA15ModifiedContentV AA5ImageV AA011_ForegroundE8ModifierV AA017HierarchicalShapeE0V AA05PlaingE0V
- ___swift_closure_destructor.17Tm
- ___swift_closure_destructor.84Tm
- _get_witness_table 7SwiftUI6HStackVyAA12TupleContentVyAA08ModifiedE0VyAGyAGyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA016_ForegroundStyleK0VyAA017HierarchicalShapeN0VGGAA023AccessibilityAttachmentK0VG_AA6VStackVyAA012_ConditionalE0VyAEyAA4TextV_AGyA3_AA14_PaddingLayoutVGQPGAEyA3__A1_yA6_AA12ProgressViewVyAA05EmptyY0VA11_GGQPGGGQPGGAA0Y0HPyHC
- _keypath_set.50Tm
- _symbolic _____yAAyAAy__________y_____SgGG_____y_____GG_____G______y_____y_____y______AAyAQ_____GQPGAPyAQ_AOyAS_____y_____AVGGQPGGGt 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleI0V AA017HierarchicalShapeL0V AA023AccessibilityAttachmentI0V AA6VStackV AA012_ConditionalD0V AA05TupleD0V AA4TextV AA14_PaddingLayoutV AA12ProgressViewV AA05EmptyX0V
- _symbolic _____y___________y_____yADyADy__________y_____SgGG_____y_____GG_____G______y_____yACy______ADyAS_____GQPGACyAS_ARyAU_____y_____AXGGQPGGGQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA08ModifiedI0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleO0V AA017HierarchicalShapeR0V AA023AccessibilityAttachmentO0V AA6VStackV AA012_ConditionalI0V AA4TextV AA08_PaddingG0V AA08ProgressD0V AA05EmptyD0V
- _symbolic _____y_____y_____yACyACy__________y_____SgGG_____y_____GG_____G______y_____yABy______ACyAR_____GQPGAByAR_AQyAT_____y_____AWGGQPGGGQPGG 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleK0V AA017HierarchicalShapeN0V AA023AccessibilityAttachmentK0V AA6VStackV AA012_ConditionalE0V AA4TextV AA14_PaddingLayoutV AA12ProgressViewV AA05EmptyY0V
CStrings:
+ "RequestPendingMessage"
+ "RequestPendingMessageNoPasscode"
+ "RequestPendingTitle"
+ "xmark.circle.fill"
- "RequestSentMessage"
- "RequestSentMessageNoPasscode"
- "RequestSentTitle"
```
