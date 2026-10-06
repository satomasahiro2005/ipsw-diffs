## PreviewShellKit

> `/System/Library/PrivateFrameworks/PreviewShellKit.framework/PreviewShellKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf7908` | `0xfd520` | **`+0x5c18`** |
| `__TEXT.__eh_frame` | `0x8f54` | `0x9948` | **`+0x9f4`** |
| `__TEXT.__cstring` | `0x46d4` | `0x4a6c` | **`+0x398`** |
| `__TEXT.__unwind_info` | `0x3d90` | `0x3f58` | **`+0x1c8`** |
| `__AUTH.__data` | `0x23e0` | `0x2538` | **`+0x158`** |
| `__DATA.__data` | `0x3690` | `0x3760` | **`+0xd0`** |
| `__TEXT.__swift_as_cont` | `0x678` | `0x720` | **`+0xa8`** |
| `__TEXT.__swift5_typeref` | `0x5062` | `0x50ce` | **`+0x6c`** |
| `__TEXT.__swift_as_entry` | `0x2a8` | `0x314` | **`+0x6c`** |
| `__AUTH_CONST.__const` | `0x6e78` | `0x6e10` | **`-0x68`** |
| `__TEXT.__swift5_capture` | `0x18cc` | `0x1928` | **`+0x5c`** |
| `__TEXT.__swift_as_ret` | `0x2f8` | `0x348` | **`+0x50`** |
| `__TEXT.__swift5_mpenum` | `0x5c` | `0x2c` | **`-0x30`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0x8c` | **`-0x28`** |
| `__TEXT.__const` | `0xb484` | `0xb464` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1879` | `0x1892` | **`+0x19`** |
| `__AUTH_CONST.__auth_got` | `0x2078` | `0x2060` | **`-0x18`** |
| `__DATA_CONST.__got` | `0xc80` | `0xc98` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x2f68` | `0x2f80` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x2310` | `0x231c` | **`+0xc`** |
| `__TEXT.__oslogstring` | `0x2c47` | `0x2c4b` | **`+0x4`** |

### Other Changes

```diff

-24.0.37.0.0
+24.0.41.0.0

-  Functions: 4618
-  Symbols:   1838
-  CStrings:  484
+  Functions: 4676
+  Symbols:   1836
+  CStrings:  492
Symbols:
+ ___swift_closure_destructor.39Tm
+ ___swift_closure_destructor.62Tm
+ ___swift_closure_destructor.75Tm
+ _symbolic IeghH_
+ _symbolic ScSyytG
+ _symbolic ScTy___________pG 15PreviewShellKit14JITXPCListener33_1C89A0595A9F44E3FEB21A13643147FFLLC23SendableNSXPCConnectionV s5ErrorP
+ _symbolic ScTy___________pG 15PreviewShellKit17PreviewsJITLinkerC s5ErrorP
+ _symbolic So12BSAuditTokenC______y___________p_Gt ScT20PreviewsFoundationOSE7PromiseV 15PreviewShellKit14JITXPCListener33_1C89A0595A9F44E3FEB21A13643147FFLLC23SendableNSXPCConnectionV s5ErrorP
+ _symbolic _____Sg 20PreviewsFoundationOS7TimeoutV
+ _symbolic ___________Sgt 15PreviewShellKit17NonUIUpdateOutputV3Key33_FD3E376ACDB517873399794B4E189AD2LLO 20PreviewsFoundationOS12PropertyListV
+ _symbolic ___________t 15PreviewShellKit17NonUIUpdateOutputV3Key33_FD3E376ACDB517873399794B4E189AD2LLO 20PreviewsFoundationOS12PropertyListV
+ _symbolic _____y___________p_G ScT20PreviewsFoundationOSE7PromiseV 15PreviewShellKit0A9JITLinkerC s5ErrorP
+ _symbolic _____y___________p_G ScT20PreviewsFoundationOSE7PromiseV 15PreviewShellKit14JITXPCListener33_1C89A0595A9F44E3FEB21A13643147FFLLC23SendableNSXPCConnectionV s5ErrorP
+ _symbolic _____y___________p_G7promise______8listenert ScT20PreviewsFoundationOSE7PromiseV 15PreviewShellKit0A9JITLinkerC s5ErrorP AD14JITXPCListener33_1C89A0595A9F44E3FEB21A13643147FFLLC
+ _symbolic _____y___________p_G7promise_t ScT20PreviewsFoundationOSE7PromiseV 15PreviewShellKit0A9JITLinkerC s5ErrorP
+ _symbolic _____yyt_G ScS8IteratorV
+ _symbolic _____yyt______G ScT20PreviewsFoundationOSE7PromiseV s5NeverO
+ _symbolic _____yyyYaYbKcG s23_ContiguousArrayStorageC
+ _symbolic xSgXwz_x______RzlXX 15PreviewShellKit27RemoteCanvasContentProviderP
- ___swift_closure_destructor.38Tm
- ___swift_closure_destructor.59Tm
- ___swift_closure_destructor.5Tm
- ___swift_closure_destructor.74Tm
- ___swift_closure_destructor.85Tm
- _get_enum_tag_for_layout_string 15PreviewShellKit14JITXPCListener33_1C89A0595A9F44E3FEB21A13643147FFLLC5StateO
- _get_enum_tag_for_layout_string 15PreviewShellKit23PreviewsJITConfigurator33_1C89A0595A9F44E3FEB21A13643147FFLLC5StateO
- _symbolic So12BSAuditTokenC______y_____Gt 20PreviewsFoundationOS7PromiseC 15PreviewShellKit14JITXPCListener33_1C89A0595A9F44E3FEB21A13643147FFLLC23SendableNSXPCConnectionV
- _symbolic _____Sg 20PreviewsFoundationOS17CancellationTokenV
- _symbolic _____Sgz_Xx 20PreviewsFoundationOS17CancellationTokenV
- _symbolic _____y_____G 20PreviewsFoundationOS6FutureC 15PreviewShellKit0A9JITLinkerC
- _symbolic _____y_____G 20PreviewsFoundationOS6FutureC 15PreviewShellKit14JITXPCListener33_1C89A0595A9F44E3FEB21A13643147FFLLC23SendableNSXPCConnectionV
- _symbolic _____y_____G 20PreviewsFoundationOS7PromiseC 15PreviewShellKit0A9JITLinkerC
- _symbolic _____y_____G 20PreviewsFoundationOS7PromiseC 15PreviewShellKit14JITXPCListener33_1C89A0595A9F44E3FEB21A13643147FFLLC23SendableNSXPCConnectionV
- _symbolic _____y_____G7promise______8listenert 20PreviewsFoundationOS7PromiseC 15PreviewShellKit0A9JITLinkerC AD14JITXPCListener33_1C89A0595A9F44E3FEB21A13643147FFLLC
- _symbolic _____y_____G7promise_t 20PreviewsFoundationOS7PromiseC 15PreviewShellKit0A9JITLinkerC
- _symbolic _____yytG 20PreviewsFoundationOS17FutureTerminationO
- _symbolic _____yytG 20PreviewsFoundationOS7PromiseC
- _symbolic _____yyt______pG s6ResultOsRi_zRi0_zrlE s5ErrorP
- _type_layout_string 15PreviewShellKit14JITXPCListener33_1C89A0595A9F44E3FEB21A13643147FFLLC5StateO
- _type_layout_string 15PreviewShellKit23PreviewsJITConfigurator33_1C89A0595A9F44E3FEB21A13643147FFLLC5StateO
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Canvas Controls/ThumbnailHost.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Extensions & Utilities/FBS+Additions.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Plugin/CanvasContentProvider.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Plugin/NonUIContentProvider.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Plugin/PreviewAgentLauncher.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Plugin/Utilities/LocalContentProvider.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewAgentProxy/PreviewAgent+Deprecated.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewAgentProxy/PreviewAgentConnector.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewAgentProxy/PreviewNonUIAgentProxy.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewAgentProxy/PreviewSceneAgentProxy.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewShellScene/HostPreferenceResolver.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Content Providers/PassThroughProvider.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Content Providers/RemoteCanvasContentProvider.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/JIT/JITManager.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/JIT/PreviewsJITLinker.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Preview Canvas/CanvasUpdater.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Preview Canvas/HostedPreviewCanvas.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Preview Canvas/StaticPreviewCanvas.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Preview Shell Scene/InjectedSceneCanvasRegistry.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Preview Shell Scene/InjectedShellScene.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Preview Shell Scene/ShellThumbnailFactory.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/PreviewShellServiceProtocol.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Process Management/Process.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Process Management/ProcessUtilities.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Servers/Agent-Side/AgentServer.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Servers/Agent-Side/JITBootstrapAgentService.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Servers/Agent-Side/PreviewAgentService.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Servers/Pipe System/HostAgentMessageStreamHub.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Servers/Pipe System/HostShellMessageStreamHub.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Shell/Servers/Pipe System/ShellAgentMessageStreamHub.swift"
+ "Increased Contrast"
+ "Standard Contrast"
+ "Ultraviolet.ColorSchemeContrast"
+ "Ultraviolet.ColorSchemeContrast.increased"
+ "Ultraviolet.ColorSchemeContrast.standard"
+ "Ultraviolet.ControlBorders"
+ "Ultraviolet.ControlBorders.hidden"
+ "Ultraviolet.ControlBorders.shown"
+ "contentPayload"
+ "promise listener "
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/AgentServer.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/CanvasContentProvider.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/CanvasUpdater.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/FBS+Additions.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/HostAgentMessageStreamHub.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/HostPreferenceResolver.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/HostShellMessageStreamHub.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/HostedPreviewCanvas.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/InjectedSceneCanvasRegistry.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/InjectedShellScene.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/JITBootstrapAgentService.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/JITManager.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/LocalContentProvider.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/NonUIContentProvider.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PassThroughProvider.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewAgent+Deprecated.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewAgentConnector.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewAgentLauncher.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewAgentService.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewNonUIAgentProxy.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewSceneAgentProxy.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewShellServiceProtocol.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/PreviewsJITLinker.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/Process.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/ProcessUtilities.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/RemoteCanvasContentProvider.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/ShellAgentMessageStreamHub.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/ShellThumbnailFactory.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/StaticPreviewCanvas.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShellKit/ThumbnailHost.swift"
- "kill()"
- "stop(pid:)"
```
