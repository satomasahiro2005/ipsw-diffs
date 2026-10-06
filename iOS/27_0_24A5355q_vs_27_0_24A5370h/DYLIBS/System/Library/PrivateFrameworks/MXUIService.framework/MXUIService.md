## MXUIService

> `/System/Library/PrivateFrameworks/MXUIService.framework/MXUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9dd0` | `0x94c8` | **`-0x908`** |
| `__AUTH_CONST.__cfstring` | `0x4a0` | `0x380` | **`-0x120`** |
| `__TEXT.__oslogstring` | `0x97b` | `0x87a` | **`-0x101`** |
| `__DATA_CONST.__objc_selrefs` | `0xa58` | `0x960` | **`-0xf8`** |
| `__TEXT.__cstring` | `0x9e8` | `0x917` | **`-0xd1`** |
| `__TEXT.__objc_methlist` | `0xb9c` | `0xb04` | **`-0x98`** |
| `__AUTH_CONST.__objc_const` | `0x1820` | `0x17a0` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x208` | `0x1d8` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x1d0` | `0x1a8` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0xb8` | `0xa8` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__const` | `0x148` | `0x140` | **`-0x8`** |

### Other Changes

```diff

-360.58.1.0.0
+360.63.1.11.2

-  Functions: 227
-  Symbols:   494
-  CStrings:  116
+  Functions: 209
+  Symbols:   464
+  CStrings:  100
Symbols:
+ -[MXUIServiceBanner presentationBehaviors]
+ _OBJC_IVAR_$_MXUIServiceBanner._showWhileLocked
- -[MXUIServiceBanner _createDeviceReplacementBannerTextLabel:]
- -[MXUIServiceBanner canRequestAlertingAssertion]
- -[MXUIServiceBanner checkifVideoAssetExists]
- -[MXUIServiceBanner configureAudioMovedBanner:]
- -[MXUIServiceBanner configureConnectBanner:]
- -[MXUIServiceBanner configureDisconnectedBanner:]
- -[MXUIServiceBanner configureUndoBanner:]
- -[MXUIServiceBanner createCustomView:WithCustomIconName:]
- -[MXUIServiceBanner createDisconnectedButton]
- -[MXUIServiceBanner createInUseConnectButton]
- -[MXUIServiceBanner createReverseButton]
- -[MXUIServiceBanner removedAccessoryColorCode:]
- -[MXUIServiceBanner setCanRequestAlertingAssertion:]
- -[MXUIServiceBanner showBannerWithTimeout]
- GCC_except_table34
- _OBJC_IVAR_$_MXUIService._banners
- _OBJC_IVAR_$_MXUIService._dispatchQueue
- _OBJC_IVAR_$_MXUIService._presentBanner
- _OBJC_IVAR_$_MXUIServiceBanner._bannerAssetTransaction
- _OBJC_IVAR_$_MXUIServiceBanner._canRequestAlertingAssertion
- _OUTLINED_FUNCTION_33
- _OUTLINED_FUNCTION_34
- _OUTLINED_FUNCTION_35
- _OUTLINED_FUNCTION_36
- _OUTLINED_FUNCTION_37
- __Block_object_dispose
- __Unwind_Resume
- ___42-[MXUIServiceBanner showBannerWithTimeout]_block_invoke
- ___52-[MXUIServiceBanner setCanRequestAlertingAssertion:]_block_invoke
- ___block_descriptor_40_e8_32r_e20_v20?0i8"NSError"12lr32l8
- ___objc_personality_v0
- _dispatch_after
CStrings:
- "-"
- "-MXUIServiceBanner- %s: MXUIServiceBanner: setCanRequestAlertingAssertion _canRequestAlertingAssertion: %{public}d "
- "-MXUIServiceBanner- %s: accessoryNameWithoutColorCode for Case: %{public}@"
- "-MXUIServiceBanner- %s: accessoryNameWithoutColorCode: %{public}@"
- "-[MXUIServiceBanner removedAccessoryColorCode:]"
- "-[MXUIServiceBanner setCanRequestAlertingAssertion:]"
- "6 seconds timer reached"
- "8195"
- "8197"
- "8205"
- "8208"
- "8218"
- "Case"
- "MXUIServiceAssetLoad"
- "default"
- "v20@?0i8@\"NSError\"12"
```
