## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19db34` | `0x19b298` | **`-0x289c`** |
| `__AUTH_CONST.__objc_const` | `0x2af38` | `0x2aa48` | **`-0x4f0`** |
| `__TEXT.__objc_methlist` | `0x1b630` | `0x1b300` | **`-0x330`** |
| `__TEXT.__oslogstring` | `0x13b77` | `0x13897` | **`-0x2e0`** |
| `__TEXT.__cstring` | `0x14236` | `0x13f76` | **`-0x2c0`** |
| `__DATA_CONST.__objc_selrefs` | `0xb7c0` | `0xb5e0` | **`-0x1e0`** |
| `__DATA.__data` | `0x3d58` | `0x3c38` | **`-0x120`** |
| `__AUTH_CONST.__cfstring` | `0x125a0` | `0x124c0` | **`-0xe0`** |
| `__TEXT.__unwind_info` | `0x6d50` | `0x6c80` | **`-0xd0`** |
| `__AUTH.__objc_data` | `0x2fd8` | `0x2f38` | **`-0xa0`** |
| `__TEXT.__dlopen_cstrs` | `0x8df` | `0x845` | **`-0x9a`** |
| `__TEXT.__gcc_except_tab` | `0x181c` | `0x1788` | **`-0x94`** |
| `__DATA.__bss` | `0x7650` | `0x7610` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0x2040` | `0x2078` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x37d8` | `0x37b0` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0x1900` | `0x18dc` | **`-0x24`** |
| `__AUTH_CONST.__const` | `0x46d8` | `0x46f8` | **`+0x20`** |
| `__TEXT.__const` | `0x40a8` | `0x40c8` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2d0` | `0x2b8` | **`-0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0xa00` | `0x9e8` | **`-0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x420` | `0x408` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x888` | `0x878` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x6e8` | `0x6d8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x14f8` | `0x1500` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xff8` | `0xff0` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x360` | `0x364` | **`+0x4`** |

### Other Changes

```diff

-1614.100.3.2.1
+1616.100.2.2.1

-  Functions: 11544
-  Symbols:   16034
-  CStrings:  4603
+  Functions: 11471
+  Symbols:   15920
+  CStrings:  4563
Symbols:
+ +[TUHardwareControlsBroadcaster hidServiceMatchingDictionaries]
+ -[TUConfigurationProvider numberForKeyHierarchy:subscriptionContext:error:]
+ -[TUConversation dealloc]
+ -[TUConversation didRegisterContactStoreObserver]
+ -[TUConversation setDidRegisterContactStoreObserver:]
+ GCC_except_table208
+ GCC_except_table91
+ _OBJC_IVAR_$_TUConversation._didRegisterContactStoreObserver
+ _TUBundleIdentifierPreferences
+ __OBJC_$_CLASS_METHODS_TUHardwareControlsBroadcaster
- -[TUCall requiresRemoteVideo]
- -[TUCall setLocalVideoLayer:forMode:]
- -[TUCall setRemoteVideoLayer:forMode:]
- -[TUCall setRequiresRemoteVideo:]
- -[TUFeatureFlags outgoingCallCallerIDEnabled]
- -[TUProxyCall _cameraTypeForVideoAttributeCamera:]
- -[TUProxyCall _createLocalVideoIfNecessary]
- -[TUProxyCall _createRemoteVideoIfNecessary]
- -[TUProxyCall _orientationForVideoAttributesOrientation:]
- -[TUProxyCall _synchronizeLocalVideo]
- -[TUProxyCall _synchronizeRemoteVideo]
- -[TUProxyCall avcRemoteVideoModeForMode:]
- -[TUProxyCall localVideo]
- -[TUProxyCall remoteVideoClient:remoteMediaDidStall:]
- -[TUProxyCall remoteVideoClient:remoteScreenAttributesDidChange:]
- -[TUProxyCall remoteVideoClient:remoteVideoAttributesDidChange:]
- -[TUProxyCall remoteVideoClient:remoteVideoDidPause:]
- -[TUProxyCall remoteVideoClient:videoDidDegrade:]
- -[TUProxyCall remoteVideoModeToLayer]
- -[TUProxyCall remoteVideo]
- -[TUProxyCall requiresRemoteVideo]
- -[TUProxyCall setLocalVideo:]
- -[TUProxyCall setLocalVideoLayer:forMode:]
- -[TUProxyCall setRemoteVideo:]
- -[TUProxyCall setRemoteVideoLayer:forMode:]
- -[TUProxyCall setRemoteVideoModeToLayer:]
- -[TUProxyCall setRequiresRemoteVideo:]
- -[TUProxyCall setVideoCaptureModeToLayer:]
- -[TUProxyCall videoCaptureModeToLayer]
- -[TURemoteVideoClient .cxx_destruct]
- -[TURemoteVideoClient cleanUpSubLayerForLayer:]
- -[TURemoteVideoClient initWithVideoContextSlotIdentifier:]
- -[TURemoteVideoClient init]
- -[TURemoteVideoClient insertSubLayerInLayer:videoSlotIdentifier:]
- -[TURemoteVideoClient nameForSubLayer]
- -[TURemoteVideoClient setVideoLayer:]
- -[TURemoteVideoClient setVideoLayer:forMode:]
- -[TURemoteVideoClient videoContextSlotIdentifier]
- -[TURemoteVideoClient videoLayer]
- -[TUVideoDeviceController availableVideoEffects]
- -[TUVideoDeviceController currentVideoEffect]
- -[TUVideoDeviceController setCurrentVideoEffect:]
- -[TUVideoDeviceControllerProvider availableVideoEffects]
- -[TUVideoDeviceControllerProvider currentVideoEffect]
- -[TUVideoDeviceControllerProvider setCurrentVideoEffect:]
- -[TUVideoDeviceControllerProvider thumbnailImageForVideoEffectName:]
- -[TUVideoEffect .cxx_destruct]
- -[TUVideoEffect hash]
- -[TUVideoEffect initWithName:thumbnailImage:]
- -[TUVideoEffect init]
- -[TUVideoEffect isEqual:]
- -[TUVideoEffect isEqualToEffect:]
- -[TUVideoEffect name]
- -[TUVideoEffect thumbnailImage]
- GCC_except_table205
- GCC_except_table94
- _CoreGraphicsLibraryCore.frameworkLibrary
- _OBJC_CLASS_$_TURemoteVideoClient
- _OBJC_CLASS_$_TUVideoEffect
- _OBJC_IVAR_$_TUProxyCall._localVideo
- _OBJC_IVAR_$_TUProxyCall._remoteVideo
- _OBJC_IVAR_$_TUProxyCall._remoteVideoModeToLayer
- _OBJC_IVAR_$_TUProxyCall._requiresRemoteVideo
- _OBJC_IVAR_$_TUProxyCall._videoCaptureModeToLayer
- _OBJC_IVAR_$_TURemoteVideoClient._videoContextSlotIdentifier
- _OBJC_IVAR_$_TURemoteVideoClient._videoLayer
- _OBJC_IVAR_$_TUVideoDeviceControllerProvider._currentVideoEffect
- _OBJC_IVAR_$_TUVideoEffect._name
- _OBJC_IVAR_$_TUVideoEffect._thumbnailImage
- _OBJC_METACLASS_$_TURemoteVideoClient
- _OBJC_METACLASS_$_TUVideoEffect
- _QuartzCoreLibrary
- _QuartzCoreLibraryCore.frameworkLibrary
- __OBJC_$_INSTANCE_METHODS_TURemoteVideoClient
- __OBJC_$_INSTANCE_METHODS_TUVideoEffect
- __OBJC_$_INSTANCE_VARIABLES_TURemoteVideoClient
- __OBJC_$_INSTANCE_VARIABLES_TUVideoEffect
- __OBJC_$_PROP_LIST_TURemoteVideoClient
- __OBJC_$_PROP_LIST_TUVideoEffect
- __OBJC_$_PROP_LIST_TUVideoEffectsProvider
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_AVCRemoteVideoClientDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_TURemoteVideoClient
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_TUVideoEffectsProvider
- __OBJC_$_PROTOCOL_METHOD_TYPES_AVCRemoteVideoClientDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_TURemoteVideoClient
- __OBJC_$_PROTOCOL_METHOD_TYPES_TUVideoEffectsProvider
- __OBJC_$_PROTOCOL_REFS_AVCRemoteVideoClientDelegate
- __OBJC_$_PROTOCOL_REFS_TURemoteVideoClient
- __OBJC_$_PROTOCOL_REFS_TUVideoEffectsProvider
- __OBJC_CLASS_PROTOCOLS_$_TURemoteVideoClient
- __OBJC_CLASS_RO_$_TURemoteVideoClient
- __OBJC_CLASS_RO_$_TUVideoEffect
- __OBJC_LABEL_PROTOCOL_$_AVCRemoteVideoClientDelegate
- __OBJC_LABEL_PROTOCOL_$_TURemoteVideoClient
- __OBJC_LABEL_PROTOCOL_$_TUVideoEffectsProvider
- __OBJC_METACLASS_RO_$_TURemoteVideoClient
- __OBJC_METACLASS_RO_$_TUVideoEffect
- __OBJC_PROTOCOL_$_AVCRemoteVideoClientDelegate
- __OBJC_PROTOCOL_$_TURemoteVideoClient
- __OBJC_PROTOCOL_$_TUVideoEffectsProvider
- ___49-[TUProxyCall remoteVideoClient:videoDidDegrade:]_block_invoke
- ___53-[TUProxyCall remoteVideoClient:remoteMediaDidStall:]_block_invoke
- ___53-[TUProxyCall remoteVideoClient:remoteVideoDidPause:]_block_invoke
- ___64-[TUProxyCall remoteVideoClient:remoteVideoAttributesDidChange:]_block_invoke
- ___65-[TUProxyCall remoteVideoClient:remoteScreenAttributesDidChange:]_block_invoke
- ___65-[TURemoteVideoClient insertSubLayerInLayer:videoSlotIdentifier:]_block_invoke
- ___CoreGraphicsLibraryCore_block_invoke
- ___QuartzCoreLibraryCore_block_invoke
- ___getCAContextClass_block_invoke
- ___getCALayerClass_block_invoke
- ___getCATransactionClass_block_invoke
- ___getCATransform3DMakeAffineTransformSymbolLoc_block_invoke
- ___getCGAffineTransformMakeRotationSymbolLoc_block_invoke
- ___getkCAGravityResizeAspectFillSymbolLoc_block_invoke
- _audit_stringCoreGraphics
- _audit_stringQuartzCore
- _getCAContextClass.softClass
- _getCALayerClass.softClass
- _getCATransactionClass
- _getCATransactionClass.softClass
- _getCATransform3DMakeAffineTransformSymbolLoc.ptr
- _getCGAffineTransformMakeRotationSymbolLoc.ptr
- _getkCAGravityResizeAspectFill
- _getkCAGravityResizeAspectFillSymbolLoc.ptr
CStrings:
+ "DeviceUsagePage"
+ "PhoneSettings"
+ "Retrieved ShowBCIDSwitch feature capability value '%@' for subscription %@"
+ "Retrieving ShowBCIDSwitch feature capability value for subscription %@ failed with error %@"
+ "ShowBCIDSwitch"
+ "com.apple.Preferences"
+ "\xf0\xf0\xf0A"
- "%@-%p"
- "-[TURemoteVideoClient init]"
- "-[TUVideoEffect initWithName:thumbnailImage:]"
- "-[TUVideoEffect init]"
- "AVCRemoteVideoClient"
- "AVTAnimoji"
- "Asked to set local video layer %@ for mode %ld"
- "Asked to set remote video layer %@ for mode %ld"
- "AvatarKit"
- "CAContext"
- "CALayer"
- "CATransaction"
- "CATransform3D _CATransform3DMakeAffineTransform(CGAffineTransform)"
- "CATransform3DMakeAffineTransform"
- "CGAffineTransform _CGAffineTransformMakeRotation(CGFloat)"
- "CGAffineTransformMakeRotation"
- "Class getCAContextClass(void)_block_invoke"
- "Class getCALayerClass(void)_block_invoke"
- "Class getCATransactionClass(void)_block_invoke"
- "Client asked to synchronize remote video layers but we don't have a AVCRemoteVideoClient which is only created once we have a nonzero videoStreamToken"
- "Creating AVCRemoteVideoClient with stream token %ld"
- "DeviceUsage"
- "Disabled"
- "NSString *getkCAGravityResizeAspectFill(void)"
- "No layers to synchronize so setting self.remoteVideo to nil"
- "No layers to synchronize, set local TURemoteVideoClient to nil"
- "Retrieved verstat feature capability value '%@' for subscription %@"
- "Retrieving verstat feature capability value for subscription %@ failed with error %@"
- "Setting video layer %@ for mode %d"
- "TURemoteVideoClient.m"
- "TURemoteVideoSubLayer"
- "TUVideoEffect.m"
- "Unable to weak-link symbol kCAGravityResizeAspectFill"
- "VerstatFeatureCapability"
- "[WARN] Cannot create TUVideoEffect named %@ with nil thumbnailImage"
- "kCAGravityResizeAspectFill"
- "outgoingCallCallerID"
- "self.videoStreamToken: %ld didPause: %d"
- "self.videoStreamToken: %ld didStall: %d"
- "self.videoStreamToken: %ld screenAttributes: %@"
- "self.videoStreamToken: %ld videoAttributes: %@"
- "softlink:r:path:/System/Library/Frameworks/CoreGraphics.framework/CoreGraphics"
- "softlink:r:path:/System/Library/Frameworks/QuartzCore.framework/QuartzCore"
- "thumbnailImage"
- "void *CoreGraphicsLibrary(void)"
- "void *QuartzCoreLibrary(void)"
- "\xf0\xf0\xf0Q"
```
