## IntentsCore

> `/System/Library/PrivateFrameworks/IntentsCore.framework/IntentsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17508` | `0x174d4` | **`-0x34`** |

### Other Changes

```diff

-4016.0.41.16.102
+4016.0.42.4.0
Functions:
~ -[INCExtensionProxy _processIntent:intentResponse:withCacheItems:] : 872 -> 868
~ -[INCExtensionTransaction _addUserActivities:] : 532 -> 528
~ -[INCDisplayLayoutMonitorObserver updateDisplayLayout:] : 456 -> 452
~ -[INCExtensionPlugInBundleManager _registerBundle:bundleIdentifier:] : 792 -> 788
~ -[INCDisplayLayoutMonitor lock_resume] : 616 -> 612
~ ___42-[INCDisplayLayoutMonitor lock_invalidate]_block_invoke : 456 -> 452
~ _INCDecodeHashedRouteUIDs : 1328 -> 1324
~ -[INCIntentDefaultValueProvider loadDefaultValuesWithCompletionHandler:] : 1008 -> 1004
~ -[INCIntentDefaultValueProvider loadDefaultValuesWithAttributes:extensionProxy:completionHandler:] : 1208 -> 1204
~ ___72-[INCExtensionProxy getDefaultValueForParameterNamed:completionHandler:]_block_invoke_2 : 956 -> 952
~ ___72-[INCAppLaunchRequest observeForAppLaunchWithTimeout:completionHandler:]_block_invoke_2 : 480 -> 476
~ +[INCAppLaunchRequest removeDenyListedApplicationProxies:] : 364 -> 360
~ -[INCWidgetIntentProvider intentsExtensionForExtension:compatibleWithIntent:error:] : 956 -> 952
```
