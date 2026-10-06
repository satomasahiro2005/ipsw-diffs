## AppIntentsRunnerXPCService

> `/System/Library/PrivateFrameworks/AppIntentsServices.framework/XPCServices/AppIntentsRunnerXPCService.xpc/AppIntentsRunnerXPCService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36e6c` | `0x3cf84` | **`+0x6118`** |
| `__TEXT.__objc_methname` | `0xb77` | `0x12f7` | **`+0x780`** |
| `__TEXT.__objc_methtype` | `0x480` | `0xa60` | **`+0x5e0`** |
| `__TEXT.__eh_frame` | `0x3ad0` | `0x3f68` | **`+0x498`** |
| `__TEXT.__auth_stubs` | `0x1ef0` | `0x2120` | **`+0x230`** |
| `__TEXT.__objc_stubs` | `0x660` | `0x860` | **`+0x200`** |
| `__TEXT.__const` | `0x1f42` | `0x20d8` | **`+0x196`** |
| `__DATA.__data` | `0x998` | `0xb10` | **`+0x178`** |
| `__TEXT.__unwind_info` | `0x1428` | `0x1580` | **`+0x158`** |
| `__DATA.__objc_selrefs` | `0x2d8` | `0x428` | **`+0x150`** |
| `__TEXT.__objc_methlist` | `0x29c` | `0x3ec` | **`+0x150`** |
| `__TEXT.__swift5_typeref` | `0xaa8` | `0xbeb` | **`+0x143`** |
| `__DATA_CONST.__auth_got` | `0xf80` | `0x1098` | **`+0x118`** |
| `__DATA.__objc_const` | `0x500` | `0x610` | **`+0x110`** |
| `__TEXT.__cstring` | `0x8d4` | `0x9a1` | **`+0xcd`** |
| `__DATA_CONST.__const` | `0x1520` | `0x15c0` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x7c8` | `0x858` | **`+0x90`** |
| `__DATA_CONST.__auth_ptr` | `0x590` | `0x5f0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xdad` | `0xdf4` | **`+0x47`** |
| `__TEXT.__swift_as_cont` | `0x2e4` | `0x324` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x24c` | `0x274` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x101` | `0x121` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x1e0` | `0x1fc` | **`+0x1c`** |
| `__DATA.__common` | `0x1c0` | `0x1d8` | **`+0x18`** |
| `__TEXT.__swift5_acfuncs` | `0x1a4` | `0x1b8` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x67c` | `0x68c` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x285` | `0x292` | **`+0xd`** |
| `__TEXT.__swift5_fieldmd` | `0x2a0` | `0x2ac` | **`+0xc`** |
| `__DATA.__objc_data` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-41.0.41.16.0
+41.0.42.6.0

-  Functions: 1311
-  Symbols:   211
-  CStrings:  273
+  Functions: 1395
+  Symbols:   217
+  CStrings:  351
Symbols:
+ _LNDaemonApplicationXPCInterface
+ _OBJC_CLASS_$_LNAutoShortcutLocalizedPhrase
+ _OBJC_CLASS_$_LNAutoShortcutsProvider
+ _OBJC_CLASS_$_NSXPCConnection
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_release_x12
CStrings:
+ "AsyncSequenceInlineThreshold"
+ "Cannot convert remote object proxy to LNDaemonApplicationInterface"
+ "Failed to connect to linkd to request update AppShortcut parameters: %s"
+ "LNDaemonApplicationInterface"
+ "RunnerServiceDispatcher.fetchAppShortcuts"
+ "Vv24@0:8@?16"
+ "Vv24@0:8@?<v@?@\"NSString\"@\"NSError\">16"
+ "Vv32@0:8@\"LNDaemonApplicationRequest\"16@?<v@?@\"LNActionMetadata\"@\"NSError\">24"
+ "Vv32@0:8@\"LNDaemonApplicationRequest\"16@?<v@?@\"LNEntityMetadata\"@\"NSError\">24"
+ "Vv32@0:8@\"LNDaemonApplicationRequest\"16@?<v@?@\"LNEnumMetadata\"@\"NSError\">24"
+ "Vv32@0:8@\"LNDaemonApplicationRequest\"16@?<v@?@\"LNQueryMetadata\"@\"NSError\">24"
+ "Vv32@0:8@16@?24"
+ "actionIdentifier"
+ "actionWithRequest:completionHandler:"
+ "activity"
+ "appShortcutsProviderTypeNameWithCompletionHandler:"
+ "autoShortcuts(forLocaleIdentifier:)"
+ "autoShortcutsForLocaleIdentifier:completion:"
+ "entityWithRequest:completionHandler:"
+ "enumWithRequest:completionHandler:"
+ "fetchListenerEndpointForProcessInstanceIdentifier:reply:"
+ "fetchProcessInstanceIdentifiersForBundleIdentifier:reply:"
+ "getObservationStatusForBundleIdentifier:entityType:reply:"
+ "initWithOptions:"
+ "invalidate"
+ "ln_applicationServiceWithError:"
+ "localizedAutoShortcutDescription"
+ "localizedPhrase"
+ "localizedShortTitle"
+ "orderedPhrases"
+ "parameterIdentifier"
+ "perform(activity:intent:options:environment:executionIdentifier:requestMetadata:systemContext:)"
+ "persistIntentEnablementForIntent:enablement:reply:"
+ "propertiesForIdentifiers:error:"
+ "queryWithRequest:completionHandler:"
+ "refreshAutoShortcutSubstitution:spans:parameterPresentationSubstitutions:reply:"
+ "registerListenerEndpointWithXPCListenerEndpoint:reply:"
+ "registerOnObservationStatusChangedForBundleIdentifier:entityType:reply:"
+ "remoteObjectProxyWithErrorHandler:"
+ "removeAllEntities:reply:"
+ "removeAllEntitiesForContext:bundleIdentifier:reply:"
+ "removeEntities:context:bundleIdentifier:reply:"
+ "removeEntitiesAcrossAllContexts:bundleIdentifier:reply:"
+ "requestUpdateAppShortcutParametersForBundleIdentifier:reply:"
+ "requestUpdateAppShortcutParametersWithReply:"
+ "resume"
+ "retrieveEnabledIntentsWithReply:"
+ "retrievePersistedIntentEnablementsWithReply:"
+ "retrieveSiriLanguageWithReply:"
+ "sendAppNotificationEvents:bundleIdentifier:reply:"
+ "setIntentEnabled:enabled:reply:"
+ "setRemoteObjectInterface:"
+ "systemImageName"
+ "unregisterOnObservationStatusChangedForBundleIdentifier:entityType:registrationUUID:reply:"
+ "updateEntities:context:bundleIdentifier:reply:"
+ "updateRelevantIntents:bundleIdentifier:reply:"
+ "updateSuggestedEntities:bundleIdentifier:reply:"
+ "v24@0:8@?16"
+ "v24@0:8@?<v@?@\"NSArray\"@\"NSError\">16"
+ "v24@0:8@?<v@?@\"NSDictionary\"@\"NSError\">16"
+ "v24@0:8@?<v@?@\"NSError\">16"
+ "v24@0:8@?<v@?@\"NSString\"@\"NSError\">16"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
+ "v32@0:8@\"NSString\"16@?<v@?@\"LNConnectionListenerEndpoint\"@\"NSError\">24"
+ "v32@0:8@\"NSString\"16@?<v@?@\"NSArray\"@\"NSError\">24"
+ "v32@0:8@\"NSString\"16@?<v@?@\"NSError\">24"
+ "v32@0:8@\"NSXPCListenerEndpoint\"16@?<v@?@\"NSString\"@\"NSError\">24"
+ "v36@0:8@\"NSString\"16B24@?<v@?@\"NSError\">28"
+ "v36@0:8@16B24@?28"
+ "v40@0:8@\"NSArray\"16@\"NSString\"24@?<v@?@\"NSError\">32"
+ "v40@0:8@\"NSData\"16@\"NSString\"24@?<v@?@\"NSError\">32"
+ "v40@0:8@\"NSString\"16@\"LNIntentEnablement\"24@?<v@?@\"NSError\">32"
+ "v40@0:8@\"NSString\"16@\"NSString\"24@?<v@?@\"NSUUID\"@\"NSError\">32"
+ "v40@0:8@\"NSString\"16@\"NSString\"24@?<v@?B@\"NSError\">32"
+ "v40@0:8@16@24@?32"
+ "v48@0:8@\"NSArray\"16@\"NSArray\"24@\"NSArray\"32@?<v@?@\"NSError\">40"
+ "v48@0:8@\"NSData\"16@\"NSData\"24@\"NSString\"32@?<v@?@\"NSError\">40"
+ "v48@0:8@\"NSString\"16@\"NSString\"24@\"NSUUID\"32@?<v@?@\"NSError\">40"
+ "v48@0:8@16@24@32@?40"
- "perform(intent:options:environment:executionIdentifier:requestMetadata:systemContext:)"
```
