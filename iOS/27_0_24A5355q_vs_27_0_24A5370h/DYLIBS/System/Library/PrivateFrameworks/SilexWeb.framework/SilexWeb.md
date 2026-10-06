## SilexWeb

> `/System/Library/PrivateFrameworks/SilexWeb.framework/SilexWeb`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18710` | `0x186bc` | **`-0x54`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0
Functions:
~ -[SWActionProvider didReceiveMessage:securityOrigin:] : 680 -> 676
~ -[SWProcessTerminationManager webContentProcessTerminated] : 428 -> 424
~ ___56-[SWDocumentStateManager initWithUserContentController:]_block_invoke : 268 -> 264
~ ___56-[SWDocumentStateManager initWithUserContentController:]_block_invoke_2 : 268 -> 264
~ ___56-[SWDocumentStateManager initWithUserContentController:]_block_invoke_3 : 268 -> 264
~ -[SWInspection initWithObject:] : 700 -> 692
~ -[SWNavigationManager actionForRequest:] : 684 -> 676
~ -[SWNavigationManager shouldPreviewRequest:] : 780 -> 776
~ -[SWNavigationManager commitViewController:] : 440 -> 436
~ -[SWNavigationBarConfigurationManager shareItemsFromDictionary:] : 504 -> 500
~ -[SWSetupManager performTasks] : 496 -> 492
~ -[SWDatastoreManager updateDatastore:originatingSession:options:completion:] : 636 -> 632
~ -[SWLogger constructLogWithMessage:] : 416 -> 412
~ -[SWWebView buildMenuWithBuilder:] : 296 -> 292
~ -[SWMessageHandlerManager userContentController:didReceiveScriptMessage:] : 716 -> 712
~ -[SWScriptsManager queueExecutableScript:scriptExecutionCompletion:] : 512 -> 508
~ -[SWScriptsManager executeQueuedScripts] : 352 -> 348
~ -[SWInteractionProvider didReceiveMessage:securityOrigin:] : 824 -> 820
~ ___80-[SWTimeoutManager initWithTimeout:messageHandlerManager:documentStateProvider:]_block_invoke_4 : 252 -> 248
```
