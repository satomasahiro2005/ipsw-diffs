## NanoTimeKit

> `/System/Library/PrivateFrameworks/NanoTimeKit.framework/NanoTimeKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fd958` | `0x2ff8cc` | **`+0x1f74`** |
| `__AUTH_CONST.__const` | `0x5dc8` | `0x5fd0` | **`+0x208`** |
| `__TEXT.__cstring` | `0x1dc8e` | `0x1de4e` | **`+0x1c0`** |
| `__TEXT.__eh_frame` | `0x1d70` | `0x1f00` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x1548e` | `0x1561e` | **`+0x190`** |
| `__TEXT.__unwind_info` | `0xd4a0` | `0xd538` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0x20b80` | `0x20c00` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x5e4` | `0x654` | **`+0x70`** |
| `__DATA_DIRTY.__data` | `0x1348` | `0x13a8` | **`+0x60`** |
| `__TEXT.__const` | `0x5e34` | `0x5e74` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x100` | `0x13c` | **`+0x3c`** |
| `__TEXT.__objc_methlist` | `0x30008` | `0x30030` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x53a20` | `0x53a40` | **`+0x20`** |
| `__DATA.__data` | `0x5080` | `0x50a0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xbe18` | `0xbe38` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x14d20` | `0x14d40` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x158e` | `0x15ac` | **`+0x1e`** |
| `__AUTH_CONST.__auth_got` | `0x20d0` | `0x20e0` | **`+0x10`** |
| `__DATA.__bss` | `0x5b50` | `0x5b60` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3288` | `0x3298` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x865` | `0x855` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x94` | `0xa4` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x88` | `0x94` | **`+0xc`** |

### Other Changes

```diff

-2483.523.0.4.0
+2483.543.0.0.0

-  Functions: 20318
-  Symbols:   34030
-  CStrings:  6398
+  Functions: 20356
+  Symbols:   34047
+  CStrings:  6413
Symbols:
+ -[NTKFaceColorPalette _adoptConfigurationWithoutBecomingDelegate:]
+ -[NTKFaceView(Siri) siriWillDismiss]
+ -[NTKFaceView(Siri) siriWillPresent]
+ _NTKDebugDumpViewHierarchyDarwinNotification_block_invoke.clearOverrideToken
+ _NTKDebugDumpViewHierarchyDarwinNotification_block_invoke.overrideOffToken
+ _NTKDebugDumpViewHierarchyDarwinNotification_block_invoke.overrideOnToken
+ _NTKDebugEnhancedSiriOverrideDidChangeNotification
+ _NTKDebugEnhancedSiriOverrideKey
+ _NTKDebugRegisterForEnhancedSiriChangesDarwinNotifications
+ _NTKDebugRegisterForEnhancedSiriChangesDarwinNotifications.onceToken
+ _NTKSiriWillDismissNotification
+ _NTKSiriWillPresentNotification
+ ___NTKDebugRegisterForEnhancedSiriChangesDarwinNotifications_block_invoke
+ ___NTKDebugRegisterForEnhancedSiriChangesDarwinNotifications_block_invoke_2
+ ___swift_closure_destructor.105Tm
+ ___swift_closure_destructor.200Tm
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ _swift_retain_x28
+ _swift_task_future_wait_throwing
+ _symbolic ScTyyt______pGSg s5ErrorP
+ _symbolic _____XDXMT 11NanoTimeKit13ClientService33_AE83D9433EE81C01A115B3EC259ECD22LLC
- ___swift_closure_destructor.132Tm
- ___swift_closure_destructor.168Tm
- ___swift_destroy_boxed_opaque_existential_1Tm
- _swift_release_n
CStrings:
+ "%s EnhancedSiriDebug: clearing enhanced Siri override"
+ "%s EnhancedSiriDebug: overriding enhanced Siri OFF"
+ "%s EnhancedSiriDebug: overriding enhanced Siri ON"
+ "Gallery refresh message attempt %ld failed %@"
+ "Gallery refresh message giving up after %ld attempt(s)…"
+ "Gallery refresh message succeeded on attempt %ld…"
+ "NTKDebugEnhancedSiriOverrideDidChangeNotification"
+ "NTKDebugEnhancedSiriOverrideKey"
+ "NTKSiriWillDismissNotification"
+ "NTKSiriWillPresentNotification"
+ "Retrying gallery refresh message in %s (attempt %ld)…"
+ "com.apple.nanotimekit.debug.clearEnhancedSiriOverride"
+ "com.apple.nanotimekit.debug.overrideEnhancedSiriOff"
+ "com.apple.nanotimekit.debug.overrideEnhancedSiriOn"
+ "description=NanoTimeKit-2483.543"
+ "sendGalleryUpdateMessageToSourceOnce()"
+ "void NTKDebugRegisterForEnhancedSiriChangesDarwinNotifications(void)_block_invoke"
+ "void NTKDebugRegisterForEnhancedSiriChangesDarwinNotifications(void)_block_invoke_2"
- "description=NanoTimeKit-2483.523.0.4"
- "face_skeletons"
- "sendGalleryUpdateMessageToSource()"
```
