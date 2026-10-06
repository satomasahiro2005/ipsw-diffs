## InstallCoordination

> `/System/Library/PrivateFrameworks/InstallCoordination.framework/InstallCoordination`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f374` | `0x70724` | **`+0x13b0`** |
| `__DATA_DIRTY.__data` | `0x8` | `0xb18` | **`+0xb10`** |
| `__DATA.__data` | `0xae8` | `—` | **`-0xae8`** |
| `__DATA_DIRTY.__objc_data` | `0xfa0` | `0x1540` | **`+0x5a0`** |
| `__AUTH.__objc_data` | `0x5a0` | `0xa0` | **`-0x500`** |
| `__TEXT.__cstring` | `0x10831` | `0x10b6b` | **`+0x33a`** |
| `__AUTH_CONST.__objc_const` | `0xd440` | `0xd640` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0x885d` | `0x89f4` | **`+0x197`** |
| `__DATA_CONST.__const` | `0x1ee0` | `0x1fd0` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x4ba0` | `0x4c70` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x6480` | `0x6540` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2470` | `0x24f0` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1b60` | `0x1bb8` | **`+0x58`** |
| `__DATA.__bss` | `0xc8` | `0xf8` | **`+0x30`** |
| `__AUTH.__data` | `0x20` | `—` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0x3c0` | `0x3e0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1f58` | `0x1f78` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x518` | `0x530` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x220` | `0x230` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x190` | `0x1a0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x268` | `0x274` | **`+0xc`** |

### Other Changes

```diff

-849.40.4.0.1
+849.40.7.0.2

+  - /System/Library/PrivateFrameworks/ManagedDevice.framework/ManagedDevice

-  Functions: 2278
-  Symbols:   3181
-  CStrings:  1929
+  Functions: 2308
+  Symbols:   3233
+  CStrings:  1950
Symbols:
+ +[IXAppInstallCoordinator(IXAppReplacement) _onQueue_subscribeToManagedAppEventsWithError:]
+ +[IXAppInstallCoordinator(IXAppReplacement) managedAppBundleIdentifiersWithError:]
+ +[IXAppInstallCoordinator(IXAppReplacement) prepareForAppReplacementSourceLookupWithOptions:error:]
+ +[IXAppReplacementSourceResolver _deviceHasPersonas]
+ -[IXAppReplacementSourceCacheOptions copyWithZone:]
+ -[IXAppReplacementSourceCacheOptions hash]
+ -[IXAppReplacementSourceCacheOptions initForTesting]
+ -[IXAppReplacementSourceCacheOptions isEqual:]
+ -[IXAppReplacementSourceResolver .cxx_destruct]
+ -[IXAppReplacementSourceResolver _appIsHidden:]
+ -[IXAppReplacementSourceResolver _appIsRestricted:]
+ -[IXAppReplacementSourceResolver _personaForIdentity:record:error:]
+ -[IXAppReplacementSourceResolver _personaForRecord:error:]
+ -[IXAppReplacementSourceResolver identity]
+ -[IXAppReplacementSourceResolver initWithIdentity:managedAppBundleIdentifiers:]
+ -[IXAppReplacementSourceResolver managedAppBundleIdentifiers]
+ -[IXAppReplacementSourceResolver resolveAppReplacementSource:replacementRuledOut:replacementCandidate:error:]
+ -[IXPlaceholderAttributes alternateDisplayNames]
+ -[IXPlaceholderAttributes setAlternateDisplayNames:]
+ _MobileInstallationPushReplacementInfo
+ _OBJC_CLASS_$_IXAppReplacementSourceCacheOptions
+ _OBJC_CLASS_$_IXAppReplacementSourceResolver
+ _OBJC_CLASS_$_MDFManagedAppMonitor
+ _OBJC_IVAR_$_IXAppReplacementSourceResolver._identity
+ _OBJC_IVAR_$_IXAppReplacementSourceResolver._managedAppBundleIdentifiers
+ _OBJC_IVAR_$_IXPlaceholderAttributes._alternateDisplayNames
+ _OBJC_METACLASS_$_IXAppReplacementSourceCacheOptions
+ _OBJC_METACLASS_$_IXAppReplacementSourceResolver
+ __ManagedAppQueue
+ __ManagedAppQueue.onceToken
+ __ManagedAppQueue.queue
+ __OBJC_$_CLASS_METHODS_IXAppReplacementSourceResolver
+ __OBJC_$_INSTANCE_METHODS_IXAppReplacementSourceCacheOptions
+ __OBJC_$_INSTANCE_METHODS_IXAppReplacementSourceResolver
+ __OBJC_$_INSTANCE_VARIABLES_IXAppReplacementSourceResolver
+ __OBJC_$_PROP_LIST_IXAppReplacementSourceResolver
+ __OBJC_CLASS_PROTOCOLS_$_IXAppReplacementSourceCacheOptions
+ __OBJC_CLASS_RO_$_IXAppReplacementSourceCacheOptions
+ __OBJC_CLASS_RO_$_IXAppReplacementSourceResolver
+ __OBJC_METACLASS_RO_$_IXAppReplacementSourceCacheOptions
+ __OBJC_METACLASS_RO_$_IXAppReplacementSourceResolver
+ ___43-[IXPlaceholderAttributes infoPlistContent]_block_invoke
+ ___82+[IXAppInstallCoordinator(IXAppReplacement) managedAppBundleIdentifiersWithError:]_block_invoke
+ ___91+[IXAppInstallCoordinator(IXAppReplacement) _onQueue_subscribeToManagedAppEventsWithError:]_block_invoke
+ ___91+[IXAppInstallCoordinator(IXAppReplacement) _onQueue_subscribeToManagedAppEventsWithError:]_block_invoke_2
+ ___91+[IXAppInstallCoordinator(IXAppReplacement) _onQueue_subscribeToManagedAppEventsWithError:]_block_invoke_3
+ ___99+[IXAppInstallCoordinator(IXAppReplacement) prepareForAppReplacementSourceLookupWithOptions:error:]_block_invoke
+ ____ManagedAppQueue_block_invoke
+ ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
+ ___block_descriptor_40_e8_32s_e28_v16?0"MDFManagedAppEvent"8ls32l8
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSString"8"NSString"16^B24ls32l8
+ ___block_descriptor_48_e5_v8?0l
+ ___block_descriptor_48_e8_32s_e20_v24?0q8"NSError"16ls32l8
+ ___block_descriptor_56_e8_32r40r_e5_v8?0lr32l8r40l8
+ _sManagedAppBundleIdentifiers
+ _sManagedAppSubscription
+ _sReSubscribeCount
- +[IXAppInstallCoordinator(IXAppReplacement) _appIsHidden:]
- +[IXAppInstallCoordinator(IXAppReplacement) _deviceHasPersonas]
- +[IXAppInstallCoordinator(IXAppReplacement) _personaForIdentity:record:error:]
- +[IXAppInstallCoordinator(IXAppReplacement) _personaForRecord:error:]
- GCC_except_table19
CStrings:
+ "%s: %@ is restricted for reason %lu"
+ "%s: Failed to fetch list of managed apps: %@"
+ "%s: Failed to re-subscribe to managed app events: %@"
+ "%s: Giving up on managed app events after %d re-subscribe attempts"
+ "%s: Managed app subscription invalidated for reason %ld: %@"
+ "%s: The set of apps MDM manages isn't known: nothing has subscribed to managed app events in this process, or the subscription has gone away : %@"
+ "+[IXAppInstallCoordinator(IXAppReplacement) _onQueue_subscribeToManagedAppEventsWithError:]_block_invoke"
+ "+[IXAppInstallCoordinator(IXAppReplacement) _onQueue_subscribeToManagedAppEventsWithError:]_block_invoke_3"
+ "+[IXAppInstallCoordinator(IXAppReplacement) getAppReplacementSource:forAppIdentity:options:error:]"
+ "+[IXAppInstallCoordinator(IXAppReplacement) managedAppBundleIdentifiersWithError:]"
+ "-[IXAppReplacementSourceResolver _appIsRestricted:]"
+ "-[IXAppReplacementSourceResolver _personaForIdentity:record:error:]"
+ "-[IXAppReplacementSourceResolver _personaForRecord:error:]"
+ "CFBundleDisplayName#"
+ "Car"
+ "Failed to replace data container."
+ "The set of apps MDM manages isn't known: nothing has subscribed to managed app events in this process, or the subscription has gone away"
+ "alternateDisplayNames"
+ "com.apple.developer.severe-vehicular-crash-event"
+ "com.apple.installcoordination.managed-app-events"
+ "v16@?0@\"MDFManagedAppEvent\"8"
+ "v24@?0q8@\"NSError\"16"
+ "v32@?0@\"NSString\"8@\"NSString\"16^B24"
- "+[IXAppInstallCoordinator(IXAppReplacement) _personaForIdentity:record:error:]"
- "+[IXAppInstallCoordinator(IXAppReplacement) _personaForRecord:error:]"
```
