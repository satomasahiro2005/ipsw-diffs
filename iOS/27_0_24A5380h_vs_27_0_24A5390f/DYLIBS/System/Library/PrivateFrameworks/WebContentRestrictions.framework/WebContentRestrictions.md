## WebContentRestrictions

> `/System/Library/PrivateFrameworks/WebContentRestrictions.framework/WebContentRestrictions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf8fc` | `0xfdcc` | **`+0x4d0`** |
| `__AUTH_CONST.__objc_const` | `0x1cf0` | `0x1d50` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x550` | `0x5a0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xf58` | `0xfa0` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xa60` | `0xa88` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x4b8` | `0x4d0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xe4` | `0xe8` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-67.0.0.0.0
+70.0.0.0.0

-  Functions: 443
-  Symbols:   1169
+  Functions: 452
+  Symbols:   1179
Symbols:
+ +[WCRBrowserEngineClient _askToBrowsePopoverSourceRectForBounds:safeAreaInsets:isPad:]
+ -[WCRBrowserEngineClient presentingViewController]
+ -[WCRBrowserEngineClient setPresentingViewController:]
+ -[WCRPopoverPresentationControllerDelegate popoverPresentationController:willRepositionPopoverToRect:inView:]
+ -[WCRRemoteAskToViewController hasPasscodeWithCompletion:]
+ GCC_except_table44
+ GCC_except_table50
+ GCC_except_table77
+ GCC_except_table79
+ GCC_except_table81
+ _CGRectGetMidX
+ _OBJC_IVAR_$_WCRBrowserEngineClient._presentingViewController
+ _WCROverridePolicyStringForValue
+ _WCROverridePolicyValueForString
+ ___85-[WCRBrowserEngineClient askToBrowseContextMenu:presentingView:state:withCompletion:]_block_invoke_3
+ ___block_descriptor_64_e8_32s40s48s56bs_e8_v12?0B8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e8_v12?0B8ls32l8s40l8s48l8s56l8s72l8s64l8
- GCC_except_table43
- GCC_except_table49
- GCC_except_table74
- GCC_except_table76
- GCC_except_table78
- _CGRectGetWidth
- ___block_descriptor_80_e8_32s40s48s56s64s72bs_e8_v12?0B8ls32l8s40l8s48l8s72l8s56l8s64l8
CStrings:
+ "%{sensitive}@ -> Not Allowed"
+ "Bloom filter: %{sensitive}@ -> Allowed"
+ "Transitive trust bloom filter: %{sensitive}@ -> Not Allowed"
+ "Transitive trust via authentication sites: %{sensitive}@ -> Allowed"
+ "overridePolicy from DC: %s"
- "overridePolicy from DC: askForPermission"
- "overridePolicy from DC: localApprovalOnly"
- "overridePolicy from DC: notAllowed"
- "overridePolicy from DC: unverifiedAdultLegacyScreenTime"
- "overridePolicy from DC: unverifiedAdultScreenTime"
```
