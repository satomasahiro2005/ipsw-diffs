## WritingToolsUI

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/WritingToolsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e178` | `0x6f0e8` | **`+0xf70`** |
| `__TEXT.__swift5_typeref` | `0xde2c` | `0xdf52` | **`+0x126`** |
| `__AUTH_CONST.__const` | `0x2148` | `0x2198` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0xde0` | `0xe24` | **`+0x44`** |
| `__DATA_CONST.__objc_selrefs` | `0x31a8` | `0x31e0` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x6a68` | `0x6a98` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x23cd` | `0x23fd` | **`+0x30`** |
| `__DATA.__data` | `0x1f38` | `0x1f60` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x4df4` | `0x4e1c` | **`+0x28`** |
| `__TEXT.__const` | `0x30b4` | `0x30d4` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x45c` | `0x47c` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1d50` | `0x1d68` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xf60` | `0xf70` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xa68` | `0xa70` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x390` | `0x394` | **`+0x4`** |

### Other Changes

```diff

-151.1.11.0.0
+151.1.11.100.0

-  Functions: 3051
-  Symbols:   3239
-  CStrings:  571
+  Functions: 3064
+  Symbols:   3253
+  CStrings:  572
Symbols:
+ -[NSUndoManager(WTTurnTracking) wt_registerUndoIfPossibleWithTarget:handler:]
+ -[WTWritingToolsController _reconcileCountsForTurnUndone:]
+ -[WTWritingToolsController setUndoTrackingUnavailable:]
+ -[WTWritingToolsController undoTrackingUnavailable]
+ GCC_except_table125
+ GCC_except_table131
+ GCC_except_table168
+ GCC_except_table184
+ GCC_except_table187
+ GCC_except_table231
+ GCC_except_table238
+ GCC_except_table240
+ GCC_except_table242
+ GCC_except_table50
+ GCC_except_table86
+ _NSInternalInconsistencyException
+ _OBJC_IVAR_$_WTWritingToolsController._undoTrackingUnavailable
+ ___62-[WTMainPopoverViewController setFeedbackHiddenDetentEnabled:]_block_invoke
+ _objc_exception_rethrow
+ _swift_retain_x27
+ _symbolic ___________y_____yABy_____y_____y_____y__________GG______Qo______G_AIQo______y_____GGAAt 7SwiftUI6SpacerV AA15ModifiedContentV AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonH0Rd__lFQO AgAEAHyQrqd__AaIRd__lFQO AA0J0V AA5LabelV AA4TextV AA5ImageV AA010BorderlessjH0V 012WritingToolsB0011ContextMenukH8Modifier33_307A59342D234FEA7D5506526C741E19LLV AA011_ForegroundhS0V AA5ColorV
+ _symbolic _____y_____G 7SwiftUI6ButtonV AA5ImageV
+ _symbolic _____y___________y___________y_____yAEy_____y_____y_____y__________GG______Qo______G_ALQo______y_____GGADQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA6SpacerV AA08ModifiedI0V AA0D0PAAE11buttonStyleyQrqd__AA015PrimitiveButtonM0Rd__lFQO AoAEAPyQrqd__AaQRd__lFQO AA0O0V AA5LabelV AA4TextV AA5ImageV AA010BorderlessoM0V 012WritingToolsB0011ContextMenupM8Modifier33_307A59342D234FEA7D5506526C741E19LLV AA011_ForegroundmX0V AA5ColorV
+ _symbolic _____y_____yAAy_____y_____y_____y__________GG______Qo______G_AHQo______y_____GG 7SwiftUI15ModifiedContentV AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonG0Rd__lFQO AeAEAFyQrqd__AaGRd__lFQO AA0I0V AA5LabelV AA4TextV AA5ImageV AA010BorderlessiG0V 012WritingToolsB0011ContextMenujG8Modifier33_307A59342D234FEA7D5506526C741E19LLV AA011_ForegroundgR0V AA5ColorV
- GCC_except_table124
- GCC_except_table130
- GCC_except_table167
- GCC_except_table183
- GCC_except_table186
- GCC_except_table230
- GCC_except_table237
- GCC_except_table239
- GCC_except_table241
- GCC_except_table85
CStrings:
+ "undo manager rejected the turn marker; reconciling counts directly in -undo/-redo"
+ "undo tracking turn fired: isUndo=%s"
- "undo tracking turn fired: isUndo=%s remainingUndoCount=%lu remainingRedoCount=%lu"
```
