## PreviewShell

> `/Applications/PreviewShell.app/PreviewShell`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2da68` | `0x30c9c` | **`+0x3234`** |
| `__TEXT.__eh_frame` | `0xb88` | `0x1598` | **`+0xa10`** |
| `__TEXT.__unwind_info` | `0xba8` | `0xd78` | **`+0x1d0`** |
| `__TEXT.__swift_as_cont` | `0x2c` | `0xf4` | **`+0xc8`** |
| `__TEXT.__const` | `0x22c4` | `0x2384` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0xd50` | `0xd00` | **`-0x50`** |
| `__TEXT.__swift_as_entry` | `0x28` | `0x74` | **`+0x4c`** |
| `__TEXT.__swift_as_ret` | `0x1c` | `0x5c` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0x9d0` | `0x9a8` | **`-0x28`** |
| `__DATA_CONST.__const` | `0x1120` | `0x1148` | **`+0x28`** |
| `__DATA.__data` | `0x19d0` | `0x19b0` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x2480` | `0x2470` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0xc20` | `0xc10` | **`-0x10`** |
| `__TEXT.__cstring` | `0x111b` | `0x112b` | **`+0x10`** |
| `__DATA.__objc_data` | `0x1100` | `0x10f8` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x1248` | `0x1240` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x610` | `0x618` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x300` | `0x308` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
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

-24.0.35.0.0
+24.0.37.0.0

-  Functions: 974
-  Symbols:   1073
-  CStrings:  720
+  Functions: 1035
+  Symbols:   1068
+  CStrings:  718
Symbols:
+ _$s15PreviewShellKit0aB15ServiceProtocolP11performKill7payloady19PreviewsMessagingOS9ProcessIDO_tYaKFTq
+ _$s15PreviewShellKit0aB15ServiceProtocolP13previewCanvas3for2inAA0aG0_p19PreviewsMessagingOS0A4TypeO_AA5AgentCtYaKFTq
+ _$s15PreviewShellKit0aB15ServiceProtocolP8relaunch4with3for19PreviewsMessagingOS9ProcessIDOAG13LaunchPayloadV_AG10DeviceTypeOtYaKFTq
+ _$s15PreviewShellKit18PreferenceResolverP16resolveHandshakey18PreviewsServicesUI17SceneUpdateTimingO0h9OSSupportJ00klG0VYaKFTq
+ _$s15PreviewShellKit27InjectedSceneCanvasRegistryC6canvas3forAA0aF0_p19PreviewsMessagingOS0A4TypeO12HostLocationO_tYaKF
+ _$s15PreviewShellKit27InjectedSceneCanvasRegistryC6canvas3forAA0aF0_p19PreviewsMessagingOS0A4TypeO12HostLocationO_tYaKFTu
+ _$s20PreviewsFoundationOS6FutureCAAs8SendableRzlE5valuexvg
+ _$s20PreviewsFoundationOS6FutureCAAs8SendableRzlE5valuexvgTu
+ _$s20PreviewsFoundationOS6FutureCAAs8SendableRzlE8callsite8priority9operation20cleanupOnCancelationACyxGAA8CallsiteV_ScPSgxyYaYbKcyxYbctcfC
+ _$sScC12continuation8functionScCyxq_GSccyxq_G_SStcfC
+ _$sScC6resume8throwingyq_n_tF
+ _$sScC6resume9returningyxn_tF
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get_throwing
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
- _$s15PreviewShellKit0A6CanvasMp
- _$s15PreviewShellKit0aB15ServiceProtocolP11performKill7payload20PreviewsFoundationOS6FutureCyytG0i9MessagingK09ProcessIDO_tKFTq
- _$s15PreviewShellKit0aB15ServiceProtocolP13previewCanvas3for2in20PreviewsFoundationOS6FutureCyAA0aG0_pG0j9MessagingL00A4TypeO_AA5AgentCtFTq
- _$s15PreviewShellKit0aB15ServiceProtocolP8relaunch4with3for20PreviewsFoundationOS6FutureCy0i9MessagingK09ProcessIDOGAJ13LaunchPayloadV_AJ10DeviceTypeOtFTq
- _$s15PreviewShellKit13BatchIdentityVMn
- _$s15PreviewShellKit18PreferenceResolverP16resolveHandshakey20PreviewsFoundationOS6FutureCy0H10ServicesUI17SceneUpdateTimingOG0h9OSSupportM00noG0VFTq
- _$s15PreviewShellKit27InjectedSceneCanvasRegistryC6canvas3for20PreviewsFoundationOS6FutureCyAA0aF0_pG0j9MessagingL00A4TypeO12HostLocationO_tF
- _$s18PreviewsServicesUI17SceneUpdateTimingOMn
- _$s19PreviewsMessagingOS9ProcessIDOMn
- _$s19PreviewsMessagingOS9ProcessIDON
- _$s20PreviewsFoundationOS6FutureC13ignoringValue8callsiteACyytGAA8CallsiteV_tF
- _$s20PreviewsFoundationOS6FutureC13observeFinishyyyAA0D11TerminationOyxGcF
- _$s20PreviewsFoundationOS6FutureC14observeFailure2on_yAA13ExecutionLaneV_ys5Error_pctF
- _$s20PreviewsFoundationOS6FutureC18observeCancelationyyyAA8CallsiteVcF
- _$s20PreviewsFoundationOS6FutureC4then8callsite2on9transformACyqd__GAA8CallsiteV_AA13ExecutionLaneVAHxctlF
- _$s20PreviewsFoundationOS6FutureC6failed8callsite_ACyxGAA8CallsiteV_s5Error_ptFZ
- _$s20PreviewsFoundationOS6FutureC7tryThen8callsite2on9transformACyqd__GAA8CallsiteV_AA13ExecutionLaneVAHxKctlF
- _$s20PreviewsFoundationOS6FutureC8callsite8callbackACyxGAA8CallsiteV_yAA7PromiseCyxGXEtcfC
- _$s20PreviewsFoundationOS6FutureC9completed8callsite_ACyxGAA8CallsiteV_xyKXEtFZ
- _$s20PreviewsFoundationOS6FutureC9inverting8callsite16accumulateErrors_ACySayxGGAA8CallsiteV_SbACyxGdtFZ
- _$s20PreviewsFoundationOS6FutureC9succeeded8callsite_ACyxGAA8CallsiteV_xtFZ
- _$s20PreviewsFoundationOS7PromiseC4fail4withys5Error_p_tF
- _$s20PreviewsFoundationOS7PromiseC7succeed4withyx_tF
- _$s20PreviewsFoundationOS7PromiseCMn
CStrings:
+ "_performActions(for:withUpdatedFBSScene:settingsDiff:from:transitionContext:lifecycleActionType:)"
+ "tryToReloadLastPreview()"
- "performKill(payload:)"
- "prepareDisplay(for:)"
- "previewCanvas(for:in:)"
- "resolveHandshake(_:)"
```
