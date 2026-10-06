## ChronoServices

> `/System/Library/PrivateFrameworks/ChronoServices.framework/ChronoServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xff318` | `0x100f60` | **`+0x1c48`** |
| `__AUTH.__objc_data` | `0x3fd8` | `0x3e20` | **`-0x1b8`** |
| `__DATA_DIRTY.__objc_data` | `0x398` | `0x550` | **`+0x1b8`** |
| `__AUTH_CONST.__objc_const` | `0x20120` | `0x20210` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x81ac` | `0x8244` | **`+0x98`** |
| `__TEXT.__gcc_except_tab` | `0xaa84` | `0xab18` | **`+0x94`** |
| `__DATA_DIRTY.__bss` | `0x7d0` | `0x860` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x32c8` | `0x3348` | **`+0x80`** |
| `__DATA.__bss` | `0x99c0` | `0x9950` | **`-0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x3118` | `0x3160` | **`+0x48`** |
| `__DATA_DIRTY.__data` | `0x1e0` | `0x228` | **`+0x48`** |
| `__AUTH.__data` | `0x3598` | `0x3558` | **`-0x40`** |
| `__AUTH_CONST.__cfstring` | `0x51c0` | `0x5200` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x25ea` | `0x2628` | **`+0x3e`** |
| `__AUTH_CONST.__auth_got` | `0x1540` | `0x1578` | **`+0x38`** |
| `__AUTH_CONST.__objc_intobj` | `0xd8` | `0x108` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x6b80` | `0x6bb0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1e98` | `0x1e70` | **`-0x28`** |
| `__TEXT.__const` | `0x7a18` | `0x7a38` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x18` | `0x30` | **`+0x18`** |
| `__DATA.__data` | `0x3358` | `0x3368` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xac8` | `0xad8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x5a45` | `0x5a35` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x740` | `0x748` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x50` | `0x58` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-727.0.0.0.0
+734.0.0.0.0

-  Functions: 7295
-  Symbols:   6523
-  CStrings:  1325
+  Functions: 7329
+  Symbols:   6540
+  CStrings:  1326
Symbols:
+ +[CHSWidgetRefreshStrategyFactory onceStrategy]
+ -[CHSConfiguredWidgetDescriptor allowsContentPreferredColorSchemes]
+ -[CHSMutableConfiguredWidgetDescriptor setAllowsContentPreferredColorSchemes:]
+ -[CHSMutableScreenshotPresentationAttributes setAllowsContentPreferredColorScheme:]
+ -[CHSMutableScreenshotPresentationAttributes setColorScheme:]
+ -[CHSMutableWidgetConfiguration setPreventsEagerPlaceholderGeneration:]
+ -[CHSScreenshotPresentationAttributes allowsContentPreferredColorScheme]
+ -[CHSScreenshotPresentationAttributes colorScheme]
+ -[CHSWidgetConfiguration preventsEagerPlaceholderGeneration]
+ -[_CHSSimpleWidgetRefreshStrategy initWithOnceStrategy]
+ -[_CHSSimpleWidgetRefreshStrategy isOnceStrategy]
+ -[_CHSSimpleWidgetRefreshStrategy type]
+ OBJC_IVAR_$_CHSConfiguredWidgetDescriptor._allowsContentPreferredColorSchemes
+ OBJC_IVAR_$_CHSConfiguredWidgetDescriptor._supportedColorSchemes
+ OBJC_IVAR_$_CHSScreenshotPresentationAttributes._allowsContentPreferredColorScheme
+ OBJC_IVAR_$_CHSScreenshotPresentationAttributes._colorScheme
+ OBJC_IVAR_$_CHSWidgetConfiguration._preventsEagerPlaceholderGeneration
+ _CHSAllowsContentPreferredColorSchemesFromColorSchemePolicies
+ _OBJC_IVAR_$__CHSSimpleWidgetRefreshStrategy._type
+ __OBJC_$_INSTANCE_METHODS_CHSConfiguredWidgetDescriptor(ChronoServices)
+ __OBJC_$_INSTANCE_METHODS_CHSMutableConfiguredWidgetDescriptor(ChronoServices)
+ ___34-[CHSWidgetConfiguration isEqual:]_block_invoke_7
+ ___41-[CHSConfiguredWidgetDescriptor isEqual:]_block_invoke_14
+ ___47-[CHSScreenshotPresentationAttributes isEqual:]_block_invoke_7
+ ___kCFBooleanFalse
+ _symbolic _____ySbG s11_SetStorageC
+ _symbolic _____ySbG s23_ContiguousArrayStorageC
+ _symbolic _____ySo8NSNumberCG s11_SetStorageC
+ _symbolic _____ySo8NSNumberC_G Sh5IndexV
- -[CHSMutableScreenshotPresentationAttributes setColorSchemePolicy:]
- -[CHSScreenshotPresentationAttributes colorSchemePolicy]
- OBJC_IVAR_$_CHSConfiguredWidgetDescriptor._supportedColorSchemePolicies
- OBJC_IVAR_$_CHSScreenshotPresentationAttributes._colorSchemePolicy
- _CHSColorSchemePoliciesFromWidgetColorSchemes
- _OBJC_IVAR_$__CHSSimpleWidgetRefreshStrategy._isDefaultStrategy
- _OBJC_IVAR_$__CHSSimpleWidgetRefreshStrategy._isDisabledStrategy
- __OBJC_$_INSTANCE_METHODS_CHSConfiguredWidgetDescriptor
- __OBJC_$_INSTANCE_METHODS_CHSMutableConfiguredWidgetDescriptor
- __OBJC_$_PROP_LIST_CHSConfiguredWidgetDescriptor
- __OBJC_$_PROP_LIST_CHSMutableConfiguredWidgetDescriptor
- ___block_descriptor_40_ea8_32s_e27_"CHSColorSchemePolicy"8?0ls32l8
CStrings:
+ "NSString *CHSColorSchemeGetAttributeDescription(CHSColorScheme, BOOL)"
+ "No color schemes encoded for %{public}@; assuming all"
+ "allowsContentPreferredColorSchemes"
+ "invalid color scheme: snapshot cannot be generated with default color scheme"
+ "isOnceStrategy"
+ "once"
+ "preventsEagerPlaceholderGeneration"
- "@\"CHSColorSchemePolicy\"8@?0"
- "Cannot find color scheme policies encoded for %{public}@"
- "Invalid condition not satisfying: %@"
- "NSString *CHSColorSchemePolicyGetAttributeDescription(CHSColorSchemePolicy *__strong)"
- "colorSchemePolicy"
- "invalid colorSchemePolicy: snapshot cannot be generated with default color scheme"
```
