## deviceaccessd

> `/usr/libexec/deviceaccessd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90c24` | `0x91498` | **`+0x874`** |
| `__TEXT.__cstring` | `0x15044` | `0x151c4` | **`+0x180`** |
| `__TEXT.__const` | `0x1c08` | `0x1cc8` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0x7f20` | `0x7e60` | **`-0xc0`** |
| `__DATA_CONST.__objc_intobj` | `0x120` | `0xd8` | **`-0x48`** |
| `__TEXT.__gcc_except_tab` | `0x40cc` | `0x408c` | **`-0x40`** |
| `__DATA.__objc_selrefs` | `0x2748` | `0x2718` | **`-0x30`** |
| `__TEXT.__auth_stubs` | `0x2250` | `0x2280` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x26f8` | `0x2728` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0xa314` | `0xa334` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1138` | `0x1150` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x68` | `0x78` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x1b1a` | `0x1b2a` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1a88` | `0x1a98` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2700.22.0.0.0
+2700.26.0.0.0

-  Functions: 2509
-  Symbols:   912
-  CStrings:  3953
+  Functions: 2514
+  Symbols:   915
+  CStrings:  3955
Symbols:
+ _$s14ProductKitCore9ProxSetupO6ServerO10productionyA2EmFWC
+ _$s14ProductKitCore9ProxSetupO6ServerO7stagingyA2EmFWC
+ _$s14ProductKitCore9ProxSetupO6ServerOMa
+ _$s14ProductKitCore9ProxSetupO7ManagerC6serverAeC6ServerO_tcfc
+ _DAExtensionCapabilityAllowedTransports
+ _DAExtensionTypeFromPointIdentifier
+ _DASupportedTransportFlagsToString
- _OBJC_CLASS_$_NEConfigurationManager
- _OBJC_CLASS_$_RBSProcessHandle
- _getuid
- _mbr_uid_to_uuid
CStrings:
+ "### FlushPending: failed to prepare message '%@' for delivery: %@"
+ "### FlushPending: unable to get extension with type: %@ for message '%@'"
+ "### runMigrationWithDiscovery pairing state for %@: paired=%s SC=%s CTKD=%s"
+ "-[DADaemonServer _createMigratedDADeviceFromConfig:]"
+ "-[DAExtensionCoordinator _executeCommandRuntimeAssertion:error:]_block_invoke_2"
+ "-[DAExtensionCoordinator _transportTypeBestForCapability:]"
+ "-[DAExtensionCoordinator _transportTypeBestForCapability:failedTransport:]"
+ "AccessoryExtensionType"
+ "AccessorySystemFeatureFlags"
+ "Best transport (failed: %@): %@ – CapFl %@, AlwFl %@, SupFl %@"
+ "Best transport: %@ – Conn %@, KED %s, CapFl %@, AlwFl %@, SupFl %@"
+ "CdCC"
+ "Extension should run %s: Type %@, Connection %@, KED %s, CapFl %@, EnFl %@"
+ "FlushPending: no available transport for message '%@', CapFl %@"
+ "FlushPending: transport %@ not yet running (state %d), deferring message '%@'"
+ "Found authorized devices: %@"
+ "No authorized extension feature, missing deviceID: %@"
+ "Q32@0:8Q16Q24"
+ "RuntimeAssertion: starting %@"
+ "_createMigratedDADeviceFromConfig:"
+ "_reportCurrentDeviceCapabilitiesChanged"
+ "_transportTypeBestForCapability:"
+ "_transportTypeBestForCapability:failedTransport:"
+ "com.apple.accessory-setup-extension"
+ "com.apple.discovery-extension"
+ "extensionCapability"
+ "reportCurrentDeviceCapabilitiesChanged:"
+ "updateLocalDeviceCapabiltiesIfNone"
+ "v16@?0q8"
- "### FlushPending: failed to prepare messages for delivery: %@"
- "### runMigrationWithDiscovery single centralManager Off to migrate: %ld"
- "-[DAExtensionCoordinator _executeCommandRuntimeAssertion:error:]"
- "Asserting extension: %@"
- "BluetoothGlobalTCC"
- "ExecuteCommand: no existing extension found, and it's able to run. Starting %@: %@"
- "Extension should run: Type %@, Connection %@, KED %s, CapFl %@, EnFl %@"
- "FlushPendingOutgoing: No available transports for %@"
- "FlushPendingOutgoing: best transport %@ not yet running (state %d), waiting for startup"
- "LocalNetworkGlobalTCC"
- "_transportTypeBest"
- "_transportTypeBest:"
- "com.apple.frontboard.visibility"
- "com.apple.preferences.networkprivacy"
- "currentState"
- "denyMulticast"
- "endowmentNamespaces"
- "failed to assert runtime: %@"
- "handleForIdentifier:error:"
- "hasSuffix:"
- "loadConfigurationsWithCompletionQueue:handler:"
- "matchSigningIdentifier"
- "pathController"
- "pathRules"
- "sharedManagerForAllUsers"
- "taskState"
- "v24@?0@\"NSArray\"8@\"NSError\"16"
```
