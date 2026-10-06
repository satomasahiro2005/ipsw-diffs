## resourcegrabberd

> `/usr/libexec/resourcegrabberd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13048` | `0x13b38` | **`+0xaf0`** |
| `__TEXT.__objc_methname` | `0x35d6` | `0x379d` | **`+0x1c7`** |
| `__TEXT.__oslogstring` | `0x18ec` | `0x1a6e` | **`+0x182`** |
| `__TEXT.__objc_stubs` | `0x25e0` | `0x2700` | **`+0x120`** |
| `__DATA.__objc_selrefs` | `0xef0` | `0xf88` | **`+0x98`** |
| `__TEXT.__objc_methtype` | `0x1193` | `0x1229` | **`+0x96`** |
| `__TEXT.__objc_methlist` | `0x17ac` | `0x1834` | **`+0x88`** |
| `__DATA_CONST.__const` | `0x6f0` | `0x740` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x7f0` | `0x7a0` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x5ac` | `0x5fc` | **`+0x50`** |
| `__DATA.__objc_const` | `0x3088` | `0x30d0` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x5e0` | `0x610` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x408` | `0x3e0` | **`-0x28`** |
| `__TEXT.__cstring` | `0x937` | `0x924` | **`-0x13`** |
| `__TEXT.__objc_classname` | `0x2ea` | `0x2e5` | **`-0x5`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-116.0.0.0.0
+117.0.0.0.0

+  - /System/Library/PrivateFrameworks/PairedDeviceRegistry.framework/PairedDeviceRegistry

-  Functions: 540
-  Symbols:   207
-  CStrings:  1029
+  Functions: 557
+  Symbols:   202
+  CStrings:  1061
Symbols:
+ _OBJC_CLASS_$_PDRRegistry
+ _PDRDevicePropertyKeyScreenScale
+ _PDRDevicePropertyKeySystemBuildVersion
- _NRDevicePropertyLocalPairingDataStorePath
- _NRDevicePropertyScreenScale
- _NRDevicePropertySystemBuildVersion
- _NRGWaitForActivePairedDeviceStorePath
- _gizmoBuildPath
- _loadGizmoBuild
- _objc_retain_x7
- _saveGizmoBuild
CStrings:
+ "@\"PDRDevice\""
+ "PDRRegistryDelegate"
+ "T@\"PDRDevice\",&,N,V_pairedDevice"
+ "addDelegate:"
+ "bluetoothIdentifier"
+ "com.apple.private.nanoresourcegrabber"
+ "createDirectoryAtPath:withIntermediateDirectories:attributes:error:"
+ "dataWithContentsOfFile:"
+ "device:propertyDidChange:"
+ "enumerateInstalledApplicationsOnDeviceWithPairingID:withBlock:"
+ "gizmoBuild.plist"
+ "ignoring app conduit update as activeDevice %@ does not support the PDRCAPABILITY_STANDALONE_APPS capability"
+ "loadGizmoBuild: failed to load gizmo build from %@"
+ "loadGizmoBuild: gizmoBuild = %@ %@"
+ "no IDS device for active paired device, cannot send protobuf request of type %u"
+ "no active paired device, cannot retrieve icon for %@"
+ "no active paired device, cannot send protobuf request of type %u"
+ "nrg_deviceForPDRDevice:"
+ "nsuuid"
+ "pairingStorePath"
+ "pdrPairedDevice"
+ "registry:added:"
+ "registry:changed:properties:"
+ "registry:compatibilityStateChanged:"
+ "registry:didActivate:"
+ "registry:didDeactivate:"
+ "registry:didPair:"
+ "registry:didSetup:"
+ "registry:didUnpair:"
+ "registry:removed:"
+ "registryChanged:"
+ "saveGizmoBuild: NSKeyedArchiver fail"
+ "saveGizmoBuild: writeToFile fail %@"
+ "saveGizmoBuild: wrote %@ %@ to %@"
+ "stringByAppendingPathComponent:"
+ "unarchivedObjectOfClass:fromData:error:"
+ "v24@0:8@\"PDRRegistry\"16"
+ "v32@0:8@\"PDRRegistry\"16@\"NSUUID\"24"
+ "v32@0:8@\"PDRRegistry\"16@\"PDRDevice\"24"
+ "v32@0:8@\"PDRRegistry\"16q24"
+ "v32@0:8@16q24"
+ "v40@0:8@\"PDRRegistry\"16@\"PDRDevice\"24@\"NSSet\"32"
+ "waitForAltAccountPairingStorePathPairingID:"
+ "writeToFile:options:error:"
- "15874345-3594-4d3f-9a28-ba2aea650a0d"
- "1cfaccb8-ffeb-4682-a50e-16f853583912"
- "@\"NRDevice\""
- "NRDevicePropertyObserver"
- "T@\"NRDevice\",&,N,V_pairedDevice"
- "addPropertyObserver:forPropertyChanges:"
- "device:propertyDidChange:fromValue:"
- "deviceForNRDevice:fromIDSDevices:"
- "enumerateInstalledApplicationsOnPairedDevice:withBlock:"
- "ignoring app conduit update as activeDevice %@ does not support the NRDEVICECAPABILITY_STANDALONE_APPS capability"
- "initWithUUIDString:"
- "v40@0:8@\"NRDevice\"16@\"NSString\"24@32"
```
