## SiriKitRuntime

> `/System/Library/PrivateFrameworks/SiriKitRuntime.framework/SiriKitRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x473f98` | `0x4740ec` | **`+0x154`** |
| `__TEXT.__oslogstring` | `0x2330d` | `0x2334d` | **`+0x40`** |

### Other Changes

```diff

-3600.28.3.0.0
+3600.28.5.1.1

-  CStrings:  3417
+  CStrings:  3418
Functions:
~ _$s14SiriKitRuntime37ConversationBridgeInstrumentationUtilC22logFlowOutputSubmitted18outputSubmissionId19flowCommandReceived0oP13ResponseError07requestN0011rootRequestN009executionJ0ys5Int32V_S2bS2SSgAA09ExecutionJ0CtF : 3148 -> 3168
~ _$s14SiriKitRuntime0aB16ExecutorRunUtilsO17getInputAndRRData4from18requestContextData0aB4Flow0H0V_10Foundation0N0VSgtSgSo013SAIntentGroupeabD0C_AA07RequestmN0CtFZ : 2552 -> 2872
CStrings:
+ "RunSiriKitExecutor command has no parse; cannot build Input"
```
