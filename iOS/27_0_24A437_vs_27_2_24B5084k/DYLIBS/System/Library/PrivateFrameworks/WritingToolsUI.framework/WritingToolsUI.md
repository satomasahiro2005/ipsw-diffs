## WritingToolsUI

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/WritingToolsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x1f2d` | `0x212d` | **`+0x200`** |
| `__TEXT.__text` | `0x6cf40` | `0x6ce0c` | **`-0x134`** |
| `__TEXT.__swift5_typeref` | `0xdf52` | `0xde2c` | **`-0x126`** |
| `__TEXT.__objc_methlist` | `0x4ccc` | `0x4d34` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x69c8` | `0x6968` | **`-0x60`** |
| `__TEXT.__gcc_except_tab` | `0xd6c` | `0xdc8` | **`+0x5c`** |
| `__AUTH_CONST.__const` | `0x2140` | `0x20f0` | **`-0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x30d8` | `0x3118` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1cc0` | `0x1cf8` | **`+0x38`** |
| `__DATA_CONST.__const` | `0xe10` | `0xe38` | **`+0x28`** |
| `__TEXT.__const` | `0x30c4` | `0x30a4` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x47c` | `0x45c` | **`-0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x570` | `0x588` | **`+0x18`** |
| `__DATA.__data` | `0x1f08` | `0x1ef0` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x38c` | `0x384` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xa40` | `0xa48` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-149.104.0.0.0
+151.1.4.0.0

-  Functions: 3011
-  Symbols:   3210
-  CStrings:  553
+  Functions: 3014
+  Symbols:   3215
+  CStrings:  560
Symbols:
+ +[WTFeedbackProxy sendComposeFeedback:range:finished:compositionSessionType:]
+ +[WTUIActionHostToClient actionForPerformRequestedTool:precomputedData:]
+ -[WTFullScreenContainerViewController performRequestedTool:precomputedData:]
+ -[WTMainPopoverViewController performRequestedTool:precomputedData:]
+ -[WTSceneHostedInputDashboardViewController performRequestedTool:precomputedData:]
+ -[WTWritingToolsController performRequestedTool:precomputedData:]
+ -[WTWritingToolsController performRequestedToolOnCurrentSession]
+ -[WTWritingToolsController precomputedData]
+ -[WTWritingToolsController rewriteResultApplied]
+ -[WTWritingToolsController setPrecomputedData:]
+ -[WTWritingToolsController setRewriteResultApplied:]
+ GCC_except_table119
+ GCC_except_table125
+ GCC_except_table162
+ GCC_except_table178
+ GCC_except_table181
+ GCC_except_table222
+ GCC_except_table229
+ GCC_except_table231
+ GCC_except_table233
+ GCC_except_table62
+ GCC_except_table64
+ GCC_except_table68
+ GCC_except_table74
+ GCC_except_table81
+ _OBJC_CLASS_$_WTPrecomputedData
+ _OBJC_IVAR_$_WTWritingToolsController._precomputedData
+ _OBJC_IVAR_$_WTWritingToolsController._rewriteResultApplied
+ ___block_descriptor_64_e8_32s40s48bs56w_e5_v8?0lw56l8s32l8s48l8s40l8
- +[WTFeedbackProxy sendComposeFeedback:range:finished:]
- +[WTFeedbackProxy sendRewriteFeedback:range:finished:]
- GCC_except_table109
- GCC_except_table115
- GCC_except_table152
- GCC_except_table168
- GCC_except_table171
- GCC_except_table212
- GCC_except_table219
- GCC_except_table221
- GCC_except_table223
- GCC_except_table34
- GCC_except_table72
- _OBJC_IVAR_$_WTWritingToolsController._precomputedCitationsJSON
- _OBJC_IVAR_$_WTWritingToolsController._precomputedContentAdvisoriesJSON
- _OBJC_IVAR_$_WTWritingToolsController._precomputedResultReplacesExisting
- _OBJC_IVAR_$_WTWritingToolsController._precomputedResultText
- _OUTLINED_FUNCTION_4
- ___62-[WTMainPopoverViewController setFeedbackHiddenDetentEnabled:]_block_invoke
- ___76-[WTWritingToolsController _presentMainPopoverViewControllerWithCompletion:]_block_invoke_2
- _symbolic ___________y_____yABy_____y_____y_____y__________GG______Qo______G_AIQo______y_____GGAAt 7SwiftUI6SpacerV AA15ModifiedContentV AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonH0Rd__lFQO AgAEAHyQrqd__AaIRd__lFQO AA0J0V AA5LabelV AA4TextV AA5ImageV AA010BorderlessjH0V 012WritingToolsB0011ContextMenukH8Modifier33_307A59342D234FEA7D5506526C741E19LLV AA011_ForegroundhS0V AA5ColorV
- _symbolic _____y_____G 7SwiftUI6ButtonV AA5ImageV
- _symbolic _____y___________y___________y_____yAEy_____y_____y_____y__________GG______Qo______G_ALQo______y_____GGADQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA6SpacerV AA08ModifiedI0V AA0D0PAAE11buttonStyleyQrqd__AA015PrimitiveButtonM0Rd__lFQO AoAEAPyQrqd__AaQRd__lFQO AA0O0V AA5LabelV AA4TextV AA5ImageV AA010BorderlessoM0V 012WritingToolsB0011ContextMenupM8Modifier33_307A59342D234FEA7D5506526C741E19LLV AA011_ForegroundmX0V AA5ColorV
- _symbolic _____y_____yAAy_____y_____y_____y__________GG______Qo______G_AHQo______y_____GG 7SwiftUI15ModifiedContentV AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonG0Rd__lFQO AeAEAFyQrqd__AaGRd__lFQO AA0I0V AA5LabelV AA4TextV AA5ImageV AA010BorderlessiG0V 012WritingToolsB0011ContextMenujG8Modifier33_307A59342D234FEA7D5506526C741E19LLV AA011_ForegroundgR0V AA5ColorV
CStrings:
+ "Skipping stale main popover presentation (current=%@, expected=%@)"
+ "didEndWritingToolsSession:accepted: threw: %{public}@"
+ "endWritingToolsWithError: rewriting active → accepted=%d (resultApplied=%d error=%d)"
+ "performRequestedTool: %ld (delegate: %@)"
+ "performRequestedToolOnCurrentSession: delegate did not handle performRequestedTool:precomputedData:"
+ "performRequestedToolOnCurrentSession: not performing on current session (session:%s sessionIsRewrite:%s)"
+ "writingToolsSession:didReceiveAction: threw: %{public}@"
```
