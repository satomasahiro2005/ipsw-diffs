## Maps

> `/private/var/staged_system_apps/Maps.app/Maps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x126653c` | `0x1268340` | **`+0x1e04`** |
| `__TEXT.__ustring` | `0x16b2` | `0x1a7e` | **`+0x3cc`** |
| `__TEXT.__oslogstring` | `0x74f73` | `0x7515d` | **`+0x1ea`** |
| `__TEXT.__eh_frame` | `0x188e8` | `0x189e0` | **`+0xf8`** |
| `__DATA_CONST.__cfstring` | `0x72be0` | `0x72cc0` | **`+0xe0`** |
| `__TEXT.__objc_stubs` | `0xf7c60` | `0xf7d00` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x75270` | `0x75308` | **`+0x98`** |
| `__TEXT.__objc_methname` | `0x18899f` | `0x188a2f` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x53ae2` | `0x53b70` | **`+0x8e`** |
| `__TEXT.__cstring` | `0x9dec6` | `0x9df52` | **`+0x8c`** |
| `__TEXT.__objc_methlist` | `0xbe2a0` | `0xbe300` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x40b78` | `0x40bc8` | **`+0x50`** |
| `__DATA.__data` | `0x446f0` | `0x44730` | **`+0x40`** |
| `__DATA.__objc_const` | `0x165a18` | `0x165a48` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x3ee05` | `0x3ee35` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x4b010` | `0x4b038` | **`+0x28`** |
| `__TEXT.__const` | `0x46578` | `0x46598` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xeb80` | `0xeb70` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x11f4` | `0x1200` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x7f4` | `0x7fc` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xd63c` | `0xd640` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x714` | `0x718` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2972.30.6.12.54
+2972.30.6.12.58

-  Functions: 97214
+  Functions: 97235

-  CStrings:  94039
+  CStrings:  94056
CStrings:
+ "Close Button Safety Check"
+ "ContaineeViewControllerReconcilePresentationOnDismiss"
+ "Open a place card first, then force the model↔UIKit orphan. Both reproduce real field states with the card's delegate intact/nil as it would be in the field: “context lingers” empties the owning context's card stack; “context popped” removes the context. With the safety check ON the x button closes the card and restores a clean state (selection cleared, contexts tidied); with it OFF the card is force-quit-only."
+ "Orphan place card — context lingers"
+ "Orphan place card — context popped"
+ "Reconcile presentation on dismiss"
+ "[%{public}@] debug orphan: collapsed internal stack to root. internal=%@ uikit=%@"
+ "[%{public}@] debug orphan: need a card on top of the root containee (open a place card first); nothing to orphan"
+ "[%{public}@] presentation state (%{public}@): contexts=%{public}@ internal=%{public}@ uikit=%{public}@"
+ "_closeButtonTapped"
+ "_debug_collapseInternalStackToRoot"
+ "_debug_emptyCardStack"
+ "_debug_removeTopContextWithoutTeardown"
+ "_internal_logPresentationStateForReason:"
+ "_internal_presentationStackAppearsCorrect"
+ "anyLaunchAlertNeedsAcknowledgement: YES (notification prewarm, shouldPrompt=%{bool}d, shouldRepeat=%{bool}d, authorizationStatus=%ld)"
+ "anyLaunchAlertNeedsAcknowledgement: notification prewarm due but will not present (shouldPrompt=%{bool}d, shouldRepeat=%{bool}d, authorizationStatus=%ld)"
+ "orphaned place card close"
- "anyLaunchAlertNeedsAcknowledgement: YES (notification prewarm, shouldPrompt=%{bool}d, shouldRepeat=%{bool}d)"
```
