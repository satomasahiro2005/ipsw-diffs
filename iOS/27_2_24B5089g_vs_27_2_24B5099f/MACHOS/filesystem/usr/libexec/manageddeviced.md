## manageddeviced

> `/usr/libexec/manageddeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41950` | `0x43dec` | **`+0x249c`** |
| `__TEXT.__objc_methname` | `0x9d72` | `0xa4a7` | **`+0x735`** |
| `__DATA.__objc_const` | `0x8768` | `0x8e78` | **`+0x710`** |
| `__TEXT.__objc_stubs` | `0x8dc0` | `0x92e0` | **`+0x520`** |
| `__TEXT.__oslogstring` | `0x651b` | `0x6897` | **`+0x37c`** |
| `__TEXT.__objc_methlist` | `0x3fd4` | `0x41ec` | **`+0x218`** |
| `__DATA.__objc_selrefs` | `0x28d8` | `0x2a40` | **`+0x168`** |
| `__TEXT.__objc_methtype` | `0xdf2` | `0xe98` | **`+0xa6`** |
| `__DATA.__objc_data` | `0x2170` | `0x2210` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x1210` | `0x1298` | **`+0x88`** |
| `__TEXT.__auth_stubs` | `0xc90` | `0xd00` | **`+0x70`** |
| `__DATA.__data` | `0x480` | `0x4e0` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x6ac` | `0x708` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x1960` | `0x19b0` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0xd61` | `0xdab` | **`+0x4a`** |
| `__DATA_CONST.__cfstring` | `0x3480` | `0x34c0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2f5e` | `0x2f9e` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x658` | `0x690` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x1e8` | `0x214` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x9a8` | `0x9d0` | **`+0x28`** |
| `__DATA.__bss` | `0x338` | `0x348` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x358` | `0x368` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x2f0` | `0x300` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__const` | `0x110` | `0x118` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-29.0.0.0.0
+31.0.0.0.0

-  Functions: 1703
-  Symbols:   529
-  CStrings:  2684
+  Functions: 1756
+  Symbols:   541
+  CStrings:  2779
Symbols:
+ _MDFManagedAppClientObjectInterface
+ _MDFManagedAppEntitlement
+ _MDFManagedAppMachServiceName
+ _MDFManagedAppRemoteObjectInterface
+ _OBJC_CLASS_$_MDFManagedAppEvent
+ _OBJC_CLASS_$_MDFManagedAppSnapshot
+ _OBJC_CLASS_$_NSXPCConnection
+ _dispatch_queue_attr_make_with_autorelease_frequency
+ _dispatch_queue_attr_make_with_qos_class
+ _objc_getProperty
+ _objc_setProperty_atomic_copy
+ _objc_storeWeak
CStrings:
+ "!"
+ "%{public}@ for unknown managed app subscription %{public}@"
+ "@\"NSXPCConnection\""
+ "@40@0:8@16@24@32"
+ "Accepted managed app connection from pid %d"
+ "Duplicate managed app subscription %{public}@ from pid %d"
+ "MDDManagedAppService"
+ "MDDManagedAppSubscriber"
+ "MDFManagedAppRemoteInterface"
+ "Managed app %{public}@ to %lu subscriber(s)"
+ "Managed app connection gone; dropped %lu subscription(s), %lu remaining"
+ "Managed app delivery to subscription %{public}@ failed: %{public}@"
+ "Managed app service instance %{public}@"
+ "Managed app subscription %{public}@ ended (%lu remaining)"
+ "Managed app subscription %{public}@ from pid %d (%lu total)"
+ "No persona to add for bundle:%{public}@. Skipping."
+ "No persona to remove for bundle:%{public}@. Skipping."
+ "Rejecting %{public}@ of managed app subscription %{public}@ from pid %d: not the owning connection"
+ "Rejecting managed app connection from pid %d: missing %{public}@"
+ "Resynchronize"
+ "Resynchronizing managed app subscription %{public}@ (pid %d)"
+ "T@\"NSDictionary\",C,V_cachedManagementStates"
+ "T@\"NSDictionary\",R,C,N"
+ "T@\"NSMutableDictionary\",R,N,V_subscribers"
+ "T@\"NSObject<OS_dispatch_queue>\",R,N,V_stateQueue"
+ "T@\"NSSet\",C,N,V_publishedBundleIdentifiers"
+ "T@\"NSUUID\",R,C,N,V_sourceIdentifier"
+ "T@\"NSXPCConnection\",R,W,N,V_connection"
+ "T@\"NSXPCListener\",R,N,V_managedAppServiceListener"
+ "TB,N,V_reconciliationPending"
+ "TQ,N,V_generation"
+ "Ti,R,N,V_processIdentifier"
+ "UUIDString"
+ "Unhandled app state %lu in managed app membership predicate"
+ "Unsubscribe"
+ "_cachedManagementStates"
+ "_connection"
+ "_currentBundleIdentifiers"
+ "_deliverOnStateQueueEvent:toSubscriber:"
+ "_emitOnStateQueueEventOfType:bundleIdentifiers:"
+ "_generation"
+ "_init"
+ "_managedAppServiceListener"
+ "_managementStatesFromManifestOnQueue"
+ "_ownedSubscriberOnStateQueueWithIdentifier:connection:operation:"
+ "_processIdentifier"
+ "_publishedBundleIdentifiers"
+ "_reconcileOnStateQueue"
+ "_reconciliationPending"
+ "_removeSubscriberWithIdentifier:"
+ "_removeSubscribersForConnection:"
+ "_sendResetOnStateQueueToSubscriber:"
+ "_snapshotOnStateQueue"
+ "_sourceIdentifier"
+ "_stateQueue"
+ "_subscribers"
+ "array"
+ "cachedManagementStates"
+ "com.apple.mdd.managed-apps.state"
+ "connection"
+ "currentConnection"
+ "deliverEvent:forSubscriptionIdentifier:"
+ "dictionary"
+ "fetchManagedAppSnapshotWithReplyHandler:"
+ "generation"
+ "i16@0:8"
+ "initWithIdentifier:connection:"
+ "initWithManagedBundleIdentifiers:sourceIdentifier:generation:creationDate:"
+ "initWithType:bundleIdentifiers:snapshot:sourceIdentifier:generation:creationDate:"
+ "isEqualToSet:"
+ "managedAppServiceListener"
+ "managedAppsMayHaveChanged"
+ "managementStatesByBundleIdentifier"
+ "minusSet:"
+ "publishedBundleIdentifiers"
+ "reconciliationPending"
+ "remoteObjectProxyWithErrorHandler:"
+ "resynchronizeSubscriptionWithIdentifier:"
+ "setCachedManagementStates:"
+ "setGeneration:"
+ "setInterruptionHandler:"
+ "setInvalidationHandler:"
+ "setPublishedBundleIdentifiers:"
+ "setReconciliationPending:"
+ "setRemoteObjectInterface:"
+ "setWithCapacity:"
+ "sharedService"
+ "stateQueue"
+ "subscribeWithIdentifier:replyHandler:"
+ "subscribers"
+ "unsubscribeWithIdentifier:"
+ "v24@0:8@\"NSUUID\"16"
+ "v24@0:8@?<v@?@\"MDFManagedAppSnapshot\"@\"NSError\">16"
+ "v32@0:8@\"NSUUID\"16@?<v@?@\"NSError\">24"
+ "v32@0:8q16@24"
```
