## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Sharing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38af08` | `0x391dd4` | **`+0x6ecc`** |
| `__AUTH_CONST.__const` | `0x1b688` | `0x1bbf8` | **`+0x570`** |
| `__TEXT.__cstring` | `0x3adb5` | `0x3b2f5` | **`+0x540`** |
| `__TEXT.__oslogstring` | `0xbc13` | `0xc093` | **`+0x480`** |
| `__TEXT.__constg_swiftt` | `0x7ef0` | `0x8008` | **`+0x118`** |
| `__TEXT.__unwind_info` | `0xed78` | `0xee78` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x787c` | `0x7928` | **`+0xac`** |
| `__TEXT.__const` | `0x24c44` | `0x24cc4` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x2b98` | `0x2bf8` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x95c2` | `0x9604` | **`+0x42`** |
| `__DATA.__data` | `0xd050` | `0xd090` | **`+0x40`** |
| `__TEXT.__swift5_types` | `0xa34` | `0xa5c` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x134a0` | `0x13480` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x7918` | `0x78f8` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x34b4` | `0x34cc` | **`+0x18`** |
| `__DATA.__bss` | `0x3e710` | `0x3e720` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x4302` | `0x4312` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x9b40` | `0x9b38` | **`-0x8`** |

### Other Changes

```diff

-2124.10.2.2.2
+2126.10.4.0.0

-  - /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices

-  Functions: 24543
-  Symbols:   20417
-  CStrings:  8859
+  Functions: 24670
+  Symbols:   20428
+  CStrings:  8935
Symbols:
+ GCC_except_table169
+ _NSLocalizedFailureReasonErrorKey
+ ___getCKUnderlyingErrorDomainSymbolLoc_block_invoke
+ _getCKUnderlyingErrorDomainSymbolLoc.ptr
+ _symbolic _____ 2os23OSSignpostIntervalStateC
+ _symbolic _____ 7Sharing16AirDropSignpostsO
+ _symbolic _____ 7Sharing16AirDropSignpostsO13IntervalTokenV
+ _symbolic _____ 7Sharing16AirDropSignpostsO2UIO
+ _symbolic _____ 7Sharing16AirDropSignpostsO3HUDO
+ _symbolic _____ 7Sharing16AirDropSignpostsO3XPCO
+ _symbolic _____ 7Sharing16AirDropSignpostsO4SendO
+ _symbolic _____ 7Sharing16AirDropSignpostsO6BrowseO
+ _symbolic _____ 7Sharing16AirDropSignpostsO6NoticeO
+ _symbolic _____ 7Sharing16AirDropSignpostsO7ReceiveO
+ _symbolic _____ 7Sharing16AirDropSignpostsO8TransferO
+ _type_layout_string 7Sharing16AirDropSignpostsO13IntervalTokenV
- _FBSOpenApplicationOptionKeyUnlockDevice
- _OBJC_CLASS_$_FBSOpenApplicationOptions
- _OBJC_CLASS_$_FBSOpenApplicationService
- ___63-[SFDeviceSetupQuickSwitchEnrollPresenter requestDeviceUnlock:]_block_invoke_2
- ___block_descriptor_32_e37_v24?0"BSProcessHandle"8"NSError"16l
CStrings:
+ "-[SFDeviceSetupQuickSwitchEnrollPresenter launchQuickSwitchSetup:completion:]_block_invoke_2"
+ "Browse.End"
+ "Browse.Start"
+ "CKUnderlyingErrorDomain"
+ "HUD.Animation.Dismiss"
+ "HUD.Animation.Expand"
+ "HUD.Intervention.Decision"
+ "HUD.Intervention.Show"
+ "HUD.SceneSetup"
+ "HUD.Show"
+ "NSString *getCKUnderlyingErrorDomain(void)"
+ "Notice.Configure"
+ "Notice.Lifetime"
+ "Receive.AnalyzeContent"
+ "Receive.Ask"
+ "Receive.AwaitRequest"
+ "Receive.Cancel"
+ "Receive.Error"
+ "Receive.HandlerInit"
+ "Receive.Import"
+ "Receive.Open"
+ "Receive.PostAccept"
+ "Receive.PostTransferEnded"
+ "Receive.PreAccept"
+ "Receive.PreChecks"
+ "Receive.SensitivePreviewCheck"
+ "Receive.Server.Start"
+ "Receive.Success"
+ "Receive.Transfer"
+ "Receive.WriteFiles"
+ "Send.Archive"
+ "Send.Ask"
+ "Send.AskPrep"
+ "Send.Connection.Setup"
+ "Send.ContentPrep"
+ "Send.CoordinateRead"
+ "Send.Exchange"
+ "Send.HandshakeHello"
+ "Send.ItemPrep"
+ "Send.LoadURLs"
+ "Send.MediaConvert"
+ "Send.ResolveEndpoints"
+ "Send.SensitiveAnalysis"
+ "Send.SensitiveIntervention"
+ "Send.SensitiveIntervention.Accept"
+ "Send.SensitiveIntervention.Reject"
+ "Send.Transfer"
+ "Send.Upload"
+ "Send.UploadAck"
+ "Showing compliance alert: domain=%{public}@ code=%ld"
+ "Transfer.Cancel"
+ "Transfer.Error"
+ "Transfer.Success"
+ "UI.PresentTransferAlert"
+ "UI.SceneConnect"
+ "UI.SessionLaunch"
+ "XPC.BecomeTransferPresenter"
+ "XPC.Cancel"
+ "XPC.FetchMetadata"
+ "XPC.Send"
+ "[Error] Interval already ended"
+ "activityID=%{public}s sceneRole=%{public}s"
+ "clientID=%{public}s bundleID=%{public}s pid=%{public}d"
+ "clientID=%{public}s bundleID=%{public}s pid=%{public}d applicationServiceOnly=%{bool,public}d deviceFilters=%{public}s"
+ "endpointUUID=%{public}s transferID=%{public}s"
+ "endpointUUID=%{public}s transferID=%{public}s attempt=%{public}ld"
+ "endpointUUID=%{public}s transferID=%{public}s fileCount=%{public}ld"
+ "endpointUUID=%{public}s transferID=%{public}s totalBytesRead=%{public}ld"
+ "launchQuickSwitchSetup: delivering VC %p via _fCallback\n"
+ "launchQuickSwitchSetup: initialViewController is nil!\n"
+ "phase=configure"
+ "requestDeviceUnlock: SBSRequestPasscodeUnlockUI result=%d\n"
+ "requestDeviceUnlock: requesting passcode unlock\n"
+ "senderBundleID=%{public}s"
+ "transferID=%{public}s"
+ "transferID=%{public}s accepted=%{public}ld"
+ "transferID=%{public}s endpointUUID=%{public}s"
+ "transferID=%{public}s endpointUUID=%{public}s fileCount=%{public}ld"
+ "transferID=%{public}s endpointUUID=%{public}s fileCount=%{public}ld archive=%{public}s"
+ "transferID=%{public}s endpointUUID=%{public}s transferType=%{public}s"
+ "transferID=%{public}s failure=%{public}s"
+ "transferID=%{public}s fileCount=%{public}ld"
+ "transferID=%{public}s transferType=%{public}s"
- "-[SFDeviceSetupQuickSwitchEnrollPresenter requestDeviceUnlock:]_block_invoke_2"
- "com.apple.springboard"
- "requestDeviceUnlock: FBSOpenApplicationService error: %@\n"
- "requestDeviceUnlock: presenting passcode unlock UI\n"
- "requestDeviceUnlock: unlock canceled or failed\n"
- "requestDeviceUnlock: unlock succeeded, dismissing coversheet\n"
- "v24@?0@\"BSProcessHandle\"8@\"NSError\"16"
```
