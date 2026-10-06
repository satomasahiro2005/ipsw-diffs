## CarPlay

> `/System/Library/Frameworks/CarPlay.framework/CarPlay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ff70` | `0x70ed0` | **`+0xf60`** |
| `__AUTH_CONST.__objc_const` | `0x21650` | `0x218a0` | **`+0x250`** |
| `__TEXT.__objc_methlist` | `0x9a30` | `0x9b48` | **`+0x118`** |
| `__TEXT.__cstring` | `0x5ae6` | `0x5be6` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x57a0` | `0x5840` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x43e0` | `0x4448` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x3726` | `0x3786` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x48` | `0x98` | **`+0x50`** |
| `__DATA.__bss` | `0x590` | `0x5e0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x1f00` | `0x1f50` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1f78` | `0x1fa8` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0xa34` | `0xa44` | **`+0x10`** |
| `__TEXT.__const` | `0x552` | `0x562` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x160` | `0x168` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x348` | `0x350` | **`+0x8`** |

### Other Changes

```diff

-552.3.0.0.0
+552.6.2.0.0

-  Functions: 3380
-  Symbols:   6354
-  CStrings:  1111
+  Functions: 3401
+  Symbols:   6397
+  CStrings:  1120
Symbols:
+ +[CPListImageRowItemCardElement _setImageSizeForAspectRatioWide:portrait:square:]
+ +[CPListImageRowItemCardElement _setMaximumImageSize:maximumFullHeightImageSize:]
+ +[CPPlaybackItemIdentifier supportsSecureCoding]
+ -[CPListTemplate _playableItemForMatchingIdentifier:]
+ -[CPListTemplate listTemplateWithIdentifier:requestPlaybackConfirmationForMatchingIdentifier:completionHandler:]
+ -[CPPlaybackConfiguration .cxx_destruct]
+ -[CPPlaybackConfiguration initWithPreferredPresentation:playbackAction:elapsedTime:duration:requiresPlaybackConfirmation:]
+ -[CPPlaybackConfiguration playbackConfirmationBlock]
+ -[CPPlaybackConfiguration requiresPlaybackConfirmation]
+ -[CPPlaybackConfiguration setPlaybackConfirmationBlock:]
+ -[CPPlaybackItemIdentifier .cxx_destruct]
+ -[CPPlaybackItemIdentifier elementIndex]
+ -[CPPlaybackItemIdentifier encodeWithCoder:]
+ -[CPPlaybackItemIdentifier identifier]
+ -[CPPlaybackItemIdentifier initWithCoder:]
+ -[CPPlaybackItemIdentifier initWithIdentifier:]
+ -[CPPlaybackItemIdentifier initWithIdentifier:elementIndex:]
+ GCC_except_table135
+ _CPBarButtonMaximumImageSize
+ _CPBarButtonSanitizedImage
+ _OBJC_CLASS_$_CPPlaybackItemIdentifier
+ _OBJC_IVAR_$_CPPlaybackConfiguration._playbackConfirmationBlock
+ _OBJC_IVAR_$_CPPlaybackConfiguration._requiresPlaybackConfirmation
+ _OBJC_IVAR_$_CPPlaybackItemIdentifier._elementIndex
+ _OBJC_IVAR_$_CPPlaybackItemIdentifier._identifier
+ _OBJC_METACLASS_$_CPPlaybackItemIdentifier
+ __OBJC_$_CLASS_METHODS_CPPlaybackItemIdentifier
+ __OBJC_$_CLASS_PROP_LIST_CPPlaybackItemIdentifier
+ __OBJC_$_INSTANCE_METHODS_CPPlaybackItemIdentifier
+ __OBJC_$_INSTANCE_VARIABLES_CPPlaybackItemIdentifier
+ __OBJC_$_PROP_LIST_CPPlaybackItemIdentifier
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CPListClientTemplateDelegate
+ __OBJC_CLASS_PROTOCOLS_$_CPPlaybackItemIdentifier
+ __OBJC_CLASS_RO_$_CPPlaybackItemIdentifier
+ __OBJC_METACLASS_RO_$_CPPlaybackItemIdentifier
+ __OBJC_PROTOCOL_REFERENCE_$_CPPlayableItem
+ ___112-[CPListTemplate listTemplateWithIdentifier:requestPlaybackConfirmationForMatchingIdentifier:completionHandler:]_block_invoke
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_10
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_9
+ ___block_descriptor_40_e8_32s_e29_v24?0"NSValue"8"NSValue"16ls32l8
+ ___block_descriptor_40_e8_32s_e41_v32?0"NSValue"8"NSValue"16"NSValue"24ls32l8
+ __maximumFullHeightImageSize
+ __maximumImageSizeForAspectRatioPortrait
+ __maximumImageSizeForAspectRatioSquare
+ __maximumImageSizeForAspectRatioWide
- GCC_except_table133
- GCC_except_table74
CStrings:
+ "%@ requesting playback confirmation for %{public}@"
+ "Failed to identify a local playable item for %@ %lu"
+ "kCPDarkContentImageKey"
+ "kCPLightContentImageKey"
+ "kCPPlaybackConfigurationRequiresPlaybackConfirmationKey"
+ "kCPPlaybackItemIdentifierElementIndexKey"
+ "kCPPlaybackItemIdentifierIdentifierKey"
+ "v24@?0@\"NSValue\"8@\"NSValue\"16"
+ "v32@?0@\"NSValue\"8@\"NSValue\"16@\"NSValue\"24"
```
