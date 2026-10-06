## CarPlay

> `/System/Library/Frameworks/CarPlay.framework/CarPlay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6dce8` | `0x6ed40` | **`+0x1058`** |
| `__AUTH_CONST.__objc_const` | `0x211b0` | `0x21490` | **`+0x2e0`** |
| `__TEXT.__objc_methlist` | `0x9828` | `0x99d0` | **`+0x1a8`** |
| `__TEXT.__oslogstring` | `0x32c6` | `0x3436` | **`+0x170`** |
| `__TEXT.__cstring` | `0x58a6` | `0x5996` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x4230` | `0x4310` | **`+0xe0`** |
| `__AUTH_CONST.__cfstring` | `0x55a0` | `0x5620` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1f18` | `0x1f68` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x1ec8` | `0x1ef0` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xa0c` | `0xa30` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0xbe8` | `0xbc8` | **`-0x20`** |
| `__DATA.__bss` | `0x580` | `0x590` | **`+0x10`** |

### Other Changes

```diff

-531.2.1.0.0
+534.3.0.0.0

-  Functions: 3325
-  Symbols:   6264
-  CStrings:  1078
+  Functions: 3364
+  Symbols:   6310
+  CStrings:  1089
Symbols:
+ +[CPInterfaceController _remoteSupportsSelector:]
+ +[CPInterfaceController _remoteVersion]
+ +[CPMapPanel maximumPanelItemsCount]
+ +[CPPanel maximumPanelItemsCount]
+ -[CPButton copyWithZone:]
+ -[CPInterfaceController _configureTemplateProviderWithCompletion:]
+ -[CPInterfaceController _templateProviderSupportsSelector:]
+ -[CPInterfaceController setTemplateProviderSupportedSelectors:]
+ -[CPInterfaceController setTemplateProviderVersion:]
+ -[CPInterfaceController templateProviderSupportedSelectors]
+ -[CPInterfaceController templateProviderVersion]
+ -[CPMapPanelButtonConfiguration initWithPrimaryAction:secondaryButton:travelEstimates:]
+ -[CPMapPanelButtonConfiguration secondaryButton]
+ -[CPMapPanelButtonConfiguration setTravelEstimates:]
+ -[CPMapPanelItem _initWithMapTemplateObject:handler:interactionAllowed:]
+ -[CPMapPanelItem interactionAllowed]
+ -[CPMapPanelItem setInteractionAllowed:]
+ -[CPMapPanelSection _init]
+ -[CPMapTemplate clientRouteSharingEnabledStatusUpdateReceivedFromVehicle:]
+ -[CPMapTemplate clientRouteSharingSupportedStatusUpdateReceivedFromVehicle:]
+ -[CPMapTemplate lastReceivedRouteSharingEnabled]
+ -[CPMapTemplate lastReceivedRouteSharingSupported]
+ -[CPMapTemplate setLastReceivedRouteSharingEnabled:]
+ -[CPMapTemplate setLastReceivedRouteSharingSupported:]
+ -[CPMultiStopCardConfiguration image]
+ -[CPMultiStopCardConfiguration initWithTitle:buttons:image:]
+ -[CPNavigationManager routeSharingSupported]
+ -[CPNavigationManager vehicleStateManager:didUpdateRouteSharingSupported:]
+ -[CPNavigationSession isRouteSharingEnabled]
+ -[CPNavigationSession isRouteSharingSupported]
+ -[CPNavigationSession setRouteSharingEnabled:]
+ -[CPNavigationSession setRouteSharingSupported:]
+ -[CPPanel setShowsCloseButton:]
+ -[CPPanel showsCloseButton]
+ -[CPTravelEstimates copyWithZone:]
+ GCC_except_table104
+ GCC_except_table130
+ _$sSo21CPVehicleStateManagerC7CarPlayE03carC0_016didUpdateCurrentD0ySo06CAFCarC0C_So0J0CSgtFTf4dnn_n
+ _$sSo21CPVehicleStateManagerC7CarPlayE21routeSharingSupportedSbvgTo
+ _OBJC_IVAR_$_CPInterfaceController._templateProviderSupportedSelectors
+ _OBJC_IVAR_$_CPInterfaceController._templateProviderVersion
+ _OBJC_IVAR_$_CPMapPanelButtonConfiguration._secondaryButton
+ _OBJC_IVAR_$_CPMapPanelItem._interactionAllowed
+ _OBJC_IVAR_$_CPMapTemplate._lastReceivedRouteSharingEnabled
+ _OBJC_IVAR_$_CPMapTemplate._lastReceivedRouteSharingSupported
+ _OBJC_IVAR_$_CPMultiStopCardConfiguration._image
+ _OBJC_IVAR_$_CPNavigationSession._routeSharingEnabled
+ _OBJC_IVAR_$_CPNavigationSession._routeSharingSupported
+ _OBJC_IVAR_$_CPPanel._showsCloseButton
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CPNavigationSessionProviding
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_2
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_3
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_4
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_5
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_6
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_7
+ ___66-[CPInterfaceController _configureTemplateProviderWithCompletion:]_block_invoke_8
+ ___74-[CPMapTemplate clientRouteSharingEnabledStatusUpdateReceivedFromVehicle:]_block_invoke
+ ___76-[CPMapTemplate clientRouteSharingSupportedStatusUpdateReceivedFromVehicle:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e18_v24?0Q8"NSSet"16ls32l8s40l8
+ __sharedRemoteVersion
+ __sharedSupportedSelectors
+ _objc_retain_x10
- -[CPMapPanelButtonConfiguration initWithPrimaryAction:symbolButton:travelEstimates:]
- -[CPMapPanelButtonConfiguration symbolButton]
- -[CPMapPanelItem _initWithMapTemplateObject:handler:]
- -[CPMapPanelSection updateItems:]
- -[CPMapTemplate clientPanelSymbolButtonTapped]
- GCC_except_table103
- GCC_except_table125
- _OBJC_IVAR_$_CPMapPanelButtonConfiguration._symbolButton
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_CPNavigationSessionProviding
- ___46-[CPMapTemplate clientPanelSymbolButtonTapped]_block_invoke
- ___54-[CPInterfaceController _completeSetupWithCompletion:]_block_invoke_2
- ___54-[CPInterfaceController _completeSetupWithCompletion:]_block_invoke_3
- ___54-[CPInterfaceController _completeSetupWithCompletion:]_block_invoke_4
- ___54-[CPInterfaceController _completeSetupWithCompletion:]_block_invoke_5
- ___54-[CPInterfaceController _completeSetupWithCompletion:]_block_invoke_6
- ___54-[CPInterfaceController _completeSetupWithCompletion:]_block_invoke_7
- ___54-[CPInterfaceController _completeSetupWithCompletion:]_block_invoke_8
- _objc_retain_x9
CStrings:
+ "%@: Forwarding route sharing enabled status update to map delegate: enabled=%{public}@"
+ "%@: Updating route sharing supported status: supported=%{public}@"
+ "%s: routeSharingSupported=%{public}@"
+ "-[CPNavigationManager vehicleStateManager:didUpdateRouteSharingSupported:]"
+ "<%@: %p, identifier: %@, showsCloseButton: %i>"
+ "<%@: %p, primaryAction: %@, travelEstimates: %@, secondaryButton: %@>"
+ "Map delegate does not support receiving route sharing enabled status updates from vehicle."
+ "No panel matching id %@ found"
+ "Server version %lu is below client's minimum required version %lu"
+ "kCPMapButtonsConfigSecondaryButtonKey"
+ "kCPMapPanelItemInteractionAllowedKey"
+ "kCPMultiStopCardConfigurationImageKey"
+ "kCPPanelShowsCloseButtonKey"
+ "v24@?0Q8@\"NSSet\"16"
- "("
- "<%@: %p, primaryAction: %@, travelEstimates: %@, symbolButton: %@>"
- "kCPMapButtonsConfigSymbolButtonKey"
```
