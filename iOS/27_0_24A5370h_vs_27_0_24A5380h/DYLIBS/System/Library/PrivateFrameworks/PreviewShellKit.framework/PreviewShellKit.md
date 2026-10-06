## PreviewShellKit

> `/System/Library/PrivateFrameworks/PreviewShellKit.framework/PreviewShellKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeecc0` | `0xf7908` | **`+0x8c48`** |
| `__TEXT.__eh_frame` | `0x843c` | `0x8f54` | **`+0xb18`** |
| `__TEXT.__unwind_info` | `0x3b98` | `0x3d90` | **`+0x1f8`** |
| `__TEXT.__cstring` | `0x47f4` | `0x46d4` | **`-0x120`** |
| `__TEXT.__const` | `0xb3a4` | `0xb484` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0x6f18` | `0x6e78` | **`-0xa0`** |
| `__TEXT.__swift_as_cont` | `0x5d8` | `0x678` | **`+0xa0`** |
| `__AUTH.__data` | `0x2350` | `0x23e0` | **`+0x90`** |
| `__TEXT.__swift_as_ret` | `0x2a4` | `0x2f8` | **`+0x54`** |
| `__TEXT.__swift5_typeref` | `0x5012` | `0x5062` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x22dc` | `0x2310` | **`+0x34`** |
| `__DATA.__data` | `0x3660` | `0x3690` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x278` | `0x2a8` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x2f40` | `0x2f68` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x18f4` | `0x18cc` | **`-0x28`** |
| `__AUTH_CONST.__objc_const` | `0x31f0` | `0x31d0` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1859` | `0x1879` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2060` | `0x2078` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x2c37` | `0x2c47` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x30c` | `0x310` | **`+0x4`** |

### Other Changes

```diff

-24.0.35.0.0
+24.0.37.0.0

-  Functions: 4559
+  Functions: 4618

-  CStrings:  493
+  CStrings:  484
Symbols:
+ _symbolic SDy_____ScCy___________pGG 18PreviewsServicesUI15SceneUpdateSeedV AA0dE6TimingO s5ErrorP
+ _symbolic SDyxSayScCy______p______pGGG 15PreviewShellKit0A6CanvasP s5ErrorP
+ _symbolic SayScCy______p______pGG 15PreviewShellKit0A6CanvasP s5ErrorP
+ _symbolic ScCy___________pG 18PreviewsServicesUI17SceneUpdateTimingO s5ErrorP
+ _symbolic ScCy___________pG 19PreviewsOSSupportUI20SceneUpdateHandshakeV s5ErrorP
+ _symbolic ScCy___________pGSg 18PreviewsServicesUI17SceneUpdateTimingO s5ErrorP
+ _symbolic ScCy______p______pG 15PreviewShellKit0A6CanvasP s5ErrorP
+ _symbolic _____ 15PreviewShellKit13CanvasUpdaterC14UpdateDelegate33_7E3362FB272E6D09F95AB9294BB7F00ELLC14HandshakeStateO
+ _symbolic _____ 19PreviewsOSSupportUI20SceneUpdateHandshakeV
+ _symbolic ______ScCy___________pGt 18PreviewsServicesUI15SceneUpdateSeedV AA0dE6TimingO s5ErrorP
+ _symbolic _____yScCy______p______pGG s23_ContiguousArrayStorageC 15PreviewShellKit0D6CanvasP s5ErrorP
+ _symbolic _____y_____G 20PreviewsFoundationOS6FutureC 0a9MessagingC011SceneLayoutO
+ _symbolic _____y_____ScCy___________pGG s18_DictionaryStorageC 18PreviewsServicesUI15SceneUpdateSeedV AC0fG6TimingO s5ErrorP
+ _symbolic _____y____________ptG 20PreviewsFoundationOS6FutureC 0A11OSSupportUI11AgentUpdateV7ContextV 15PreviewShellKit0J6CanvasP
+ _symbolic _____z_Xx 19PreviewsMessagingOS13LaunchPayloadV
- ___swift_closure_destructor.19Tm
- _symbolic SDy__________y_____GG 18PreviewsServicesUI15SceneUpdateSeedV 0A12FoundationOS7PromiseC AA0dE6TimingO
- _symbolic SDyxSay_____y______pGGG 20PreviewsFoundationOS7PromiseC 15PreviewShellKit0E6CanvasP
- _symbolic Say_____y______pGG 20PreviewsFoundationOS7PromiseC 15PreviewShellKit0E6CanvasP
- _symbolic _____ 18PreviewsServicesUI17SceneUpdateTimingO
- _symbolic _____ 19PreviewsMessagingOS19CancelUpdatePayloadV
- _symbolic _____Ieghr_ 18PreviewsServicesUI17SceneUpdateTimingO
- _symbolic _____Ieghr_ 19PreviewsMessagingOS11SceneLayoutO
- _symbolic ___________y_____Gt 18PreviewsServicesUI15SceneUpdateSeedV 0A12FoundationOS7PromiseC AA0dE6TimingO
- _symbolic _____y_____G 20PreviewsFoundationOS17FutureTerminationO AA12PropertyListV
- _symbolic _____y_____G 20PreviewsFoundationOS6FutureC 0A10ServicesUI17SceneUpdateTimingO
- _symbolic _____y_____G 20PreviewsFoundationOS6FutureC 0A11OSSupportUI20SceneUpdateHandshakeV
- _symbolic _____y_____G 20PreviewsFoundationOS7PromiseC 0A11OSSupportUI20SceneUpdateHandshakeV
- _symbolic _____y__________y_____GG s18_DictionaryStorageC 18PreviewsServicesUI15SceneUpdateSeedV 0C12FoundationOS7PromiseC AC0fG6TimingO
- _symbolic _____y______pG 20PreviewsFoundationOS6FutureC 15PreviewShellKit0E6CanvasP
CStrings:
+ "PreviewShellService sending reply for %{public}s: Cancelled - %{public}@"
+ "awaitHandshake()"
+ "multiple awaiters for handshake"
- "PreviewShellService sending reply for %{public}s: Cancelled"
- "canvas(for:)"
- "handleCancelUpdateMessage(_:)"
- "handleCapabilitiesMessage()"
- "handleContentOverrideMessage(_:)"
- "handleKill(_:)"
- "handlePingMessage()"
- "handlePurgeMessage(_:)"
- "handleVariantsMessage(_:)"
- "init(providerBox:scene:didUpdate:)"
- "performHandshake(for:with:)"
- "resolveHandshake(_:with:)"
```
