## PreviewShell

> `/Applications/PreviewShell.app/PreviewShell`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30c9c` | `0x3181c` | **`+0xb80`** |
| `__DATA.__objc_const` | `0x3c60` | `0x3f38` | **`+0x2d8`** |
| `__TEXT.__eh_frame` | `0x1598` | `0x16dc` | **`+0x144`** |
| `__TEXT.__cstring` | `0x112b` | `0x11e4` | **`+0xb9`** |
| `__DATA_CONST.__const` | `0x1148` | `0x11c0` | **`+0x78`** |
| `__TEXT.__const` | `0x2384` | `0x23f4` | **`+0x70`** |
| `__TEXT.__objc_methtype` | `0x14e9` | `0x1482` | **`-0x67`** |
| `__TEXT.__swift5_capture` | `0x308` | `0x344` | **`+0x3c`** |
| `__TEXT.__unwind_info` | `0xd78` | `0xda8` | **`+0x30`** |
| `__DATA.__data` | `0x19b0` | `0x19d0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xd00` | `0xd1e` | **`+0x1e`** |
| `__DATA_CONST.__got` | `0x618` | `0x628` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2470` | `0x2480` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xf4` | `0x104` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x74` | `0x80` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x5c` | `0x68` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x1240` | `0x1248` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x9a8` | `0x9b0` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x784` | `0x782` | **`-0x2`** |
| `__TEXT.__swift5_reflstr` | `0x6d6` | `0x6d7` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-24.0.37.0.0
+24.0.41.0.0

-  Functions: 1035
-  Symbols:   1068
+  Functions: 1048
+  Symbols:   1071
Symbols:
+ _$s15PreviewShellKit06HostedA6CanvasC38confirmReadyForDisplayAfterAsyncResizeyyYaKF
+ _$s15PreviewShellKit06HostedA6CanvasC38confirmReadyForDisplayAfterAsyncResizeyyYaKFTu
+ _$s15PreviewShellKit5AgentC4killyyYaKF
+ _$s15PreviewShellKit5AgentC4killyyYaKFTu
+ _$s18PreviewsServicesUI21SceneMessageResponderV5reply7payloadySDySSypGSg_tF
+ _$s19PreviewsMessagingOS19PreviewVariantGroupV0D8ShellKitE014controlBorderseF0ACvgZ
+ _$s19PreviewsMessagingOS19PreviewVariantGroupV0D8ShellKitE019colorSchemeContrasteF0ACvgZ
- _$s15PreviewShellKit06HostedA6CanvasC38confirmReadyForDisplayAfterAsyncResize20PreviewsFoundationOS6FutureCyytGyF
- _$s15PreviewShellKit5AgentC4kill20PreviewsFoundationOS6FutureCyytGyF
- _$s18PreviewsServicesUI21SceneMessageResponderV5reply6resultys6ResultOyyts5Error_pG_tF
- _$s20PreviewsFoundationOS6FutureC17observeCompletion2on_yAA13ExecutionLaneV_ys6ResultOyxs5Error_pGctF
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/Content Providers/Built-in Providers/Canvas Providers/Remote/RemoteContentProvider.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/Display & Scene Host/LocalSceneHost.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/Display & Scene Host/SceneConfigurator.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/Preview Shell Scene/LocalStaticSceneRegistry.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/Preview Shell Scene/ShellScenes.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/Preview Shell Scene/SimDisplaySceneRegistry.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/Process Management/ApplicationLauncher.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/ApplicationLauncher.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/LocalSceneHost.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/LocalStaticSceneRegistry.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/RemoteContentProvider.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/SceneConfigurator.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/ShellScenes.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/OS/PreviewShell/Sources/PreviewShell/SimDisplaySceneRegistry.swift"
```
