## bluetoothd

> `/usr/sbin/bluetoothd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x903c40` | `0x904e90` | **`+0x1250`** |
| `__TEXT.__oslogstring` | `0xc0c3a` | `0xc0f13` | **`+0x2d9`** |
| `__TEXT.__cstring` | `0xc7f46` | `0xc7dbe` | **`-0x188`** |
| `__DATA_CONST.__cfstring` | `0x27880` | `0x27a00` | **`+0x180`** |
| `__TEXT.__gcc_except_tab` | `0x70a0c` | `0x70b58` | **`+0x14c`** |
| `__TEXT.__objc_methname` | `0x1f59b` | `0x1f6d6` | **`+0x13b`** |
| `__DATA.__objc_const` | `0x108c8` | `0x109a8` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x9b64` | `0x9bf4` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x19ba0` | `0x19c20` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x7740` | `0x77a0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x34330` | `0x342d0` | **`-0x60`** |
| `__DATA.__bss` | `0x76c82` | `0x76c52` | **`-0x30`** |
| `__DATA_CONST.__objc_dictobj` | `0x2f8` | `0x2d0` | **`-0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x428` | `0x408` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x26278` | `0x26298` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x11b8` | `0x11d4` | **`+0x1c`** |
| `__TEXT.__objc_methtype` | `0x5a3b` | `0x5a56` | **`+0x1b`** |
| `__DATA_CONST.__objc_intobj` | `0xa80` | `0xa98` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x248` | `0x258` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x5260` | `0x5270` | **`+0x10`** |
| `__TEXT.__const` | `0x25e90` | `0x25ea0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2948` | `0x2950` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xe50` | `0xe48` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0xd0` | `0xd8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x152` | `0x158` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2700.51.1.3.0
+2701.3.0.0.0

-  Functions: 37368
-  Symbols:   1803
-  CStrings:  43044
+  Functions: 37393
+  Symbols:   1804
+  CStrings:  43068
Symbols:
+ _$s14ProductKitCore9ProxSetupO04HomeB0O7RequestV14manufacturerID05modelI005colorI011environment13cachingPolicyAgE012ManufacturerI0V_AE05ModelI0VSuSgAC11EnvironmentOAC07CachingN0OtcfC
+ _$s14ProductKitCore9ProxSetupO04HomeB0O8MetadataV17accessoryCategoryAC09AccessoryI0Ovg
+ _$s14ProductKitCore9ProxSetupO17AccessoryCategoryO8rawValues5UInt8Vvg
+ _$s14ProductKitCore9ProxSetupO17AccessoryCategoryOMa
+ _$ss5UInt8VMn
+ _swift_retain_x19
- _$s14ProductKitCore9ProxSetupO04HomeB0O7RequestV14manufacturerID05modelI011environment13cachingPolicyAgE012ManufacturerI0V_AE05ModelI0VAC11EnvironmentOAC07CachingM0OtcfC
- _IOObjectConformsTo
- _OBJC_CLASS_$_NSAssertionHandler
- _dlerror
- _swift_retain_x22
CStrings:
+ "%s published ColorID with no reachable LocationID"
+ "%{public}s: dropping held pairing notification for “%s”"
+ "%{public}s: posting held pairing notification for “%s” with colorID %d"
+ "%{public}s: refusing to record unresolved colorID"
+ "%{public}s: “%s” has no ColorID yet, holding pairing notification until it is published"
+ "%{public}s: “%s” published colorID %d (stored color %d)"
+ "20:54:18"
+ "255f66bd287a0de132348bcd355dffcfd59a14ccf36585e06786872ed3c2c33c"
+ "771783b8e832813b93b16f99a63281197d05bd7284b551bfd25ec6e004529191"
+ "AllowTonesData set to %d"
+ "AudioQualityOptimizer - isOptimizableLink:No(incomplete service discovery)"
+ "CSMainModeOverride"
+ "DaemonXPCToScanMgr"
+ "Freeing transient LeDevice %{public}@ read from cache for address %@ (returning identifier only, device not tracked)"
+ "Freeing transient LeDevice %{public}@ read from cache for address %s (inspection only, not tracked)"
+ "GapRxToObserver"
+ "GapToObserver"
+ "HCIToGap"
+ "IONotificationPortCreate for ColorID failed"
+ "IOServiceAddMatchingNotification for %s failed (%d)"
+ "Keeping IRK for \"%s\": still in use by OOB owner (slot %d), device %{public}s"
+ "LeChannelSoundingAgent initialize fEnableRTTMainMode set to %d"
+ "ObserverToPreNotify"
+ "PairingManager::leDevicePaired LK:%{private, mask.hash}.16P LKype:%d, isAppleWatch %d"
+ "PreNotifyToDaemonXPC"
+ "Registered for %s notifications for ColorID"
+ "ScanMgrToWPDClient"
+ "Sep  9 2026"
+ "Shared memory reset"
+ "[LeAdvMetric] getAdvReportMetricCBv1 (ms) %@"
+ "[LeAdvMetric] inXPC not a dict"
+ "accessoryCategory"
+ "com.apple.icloud.findmydeviced"
+ "daemonXPCSendAt"
+ "ed3fd5388913b157ffcc58229cc4c1c1f705ecbace5746b51eaf8e49c1c7a17c"
+ "fetchHomeKitMetadataWithManufacturerID:modelID:colorCode:completionHandler:"
+ "gapRxAt"
+ "getAdvReportDictFromXPC:"
+ "getAdvReportMetricCBv1"
+ "getAdvReportTimestamps"
+ "getAdvReportXPCRepresentation"
+ "hciRxAt"
+ "kCBAdvReportMetricHeySiri"
+ "observerRxAt"
+ "preNotifyAt"
+ "proximityServiceColorCode"
+ "reject non-credit-based channel in reconfiguration REQ: cid:0x%x type:%d psm:0x%x"
+ "sAllowTonesData"
+ "scanMgrRxAt"
+ "setAdvReportTimestamps:"
+ "setDaemonXPCSendAt"
+ "setGapRxAt:"
+ "setHciRxAt:"
+ "setObserverRxAt"
+ "setPreNotifyAt"
+ "setProximityServiceAccessoryCategory:"
+ "setScanMgrRxAt"
+ "setWPDClientAt"
+ "v44@0:8@16@24C32@?36"
+ "void BT::USBPairingManager::forgetColorIDState(Device *)"
+ "void BT::USBPairingManager::handleColorIDServiceAvailable(io_service_t)"
+ "void BT::USBPairingManager::notifyPairingCompleteWhenColorKnown(Device *)_block_invoke"
+ "void BT::USBPairingManager::recordResolvedColorID(Device *, uint32_t)"
+ "wpdClientAt"
- "%Y_%m_%d_%H:%M:%S"
- "/usr/lib/libtailspin.dylib"
- "/usr/local/lib/libtailspin.dylib"
- "20:56:10"
- "A2DP Overwait detected"
- "A2DP Tailspin logging %{public}s"
- "AudioLinkManager.mm"
- "Aug 27 2026"
- "Captured tailspin %s at %s"
- "EnableTailspinLogging"
- "Failed to create filepath at %@ to capture tailspin"
- "Failed to open file descriptor to capture tailspin: %@"
- "LeConnectionDenyList: Apple Watch %@ added to incoming deny list, requesting TTR alert"
- "LeConnectionDenyList: Apple Watch %@ added to outgoing deny list, requesting TTR alert"
- "Overwait_A2DP_%s.tailspin"
- "PairingManager::leDevicePaired LK:%{private, mask.hash}.16P LKype:%d"
- "TSPDumpOptions_NoSymbolicate"
- "TSPDumpOptions_ReasonString"
- "Trying to save tailspin %@"
- "bool BT::soft_tailspin_config_apply_sync(const tailspin_config_t)"
- "currentHandler"
- "fetchHomeKitMetadataWithManufacturerID:modelID:completionHandler:"
- "handleFailureInFunction:file:lineNumber:description:"
- "int BT::soft_tailspin_dump_output_with_options(int, NSDictionary * _Nullable __strong, dispatch_queue_t _Nullable, void (^ _Nullable __strong)(bool))"
- "setRequestHandler:"
- "tailspin_config_apply_sync"
- "tailspin_config_create_with_current_state"
- "tailspin_config_create_with_default_config"
- "tailspin_config_free"
- "tailspin_config_t BT::soft_tailspin_config_create_with_current_state()"
- "tailspin_config_t BT::soft_tailspin_config_create_with_default_config()"
- "tailspin_dump_output_with_options"
- "tailspin_enabled_set"
- "tailspin_kdbg_filter_subclass_set"
- "v40@?0@\"NSString\"8@\"NSDictionary\"16@\"NSDictionary\"24@?<v@?@\"NSDictionary\"@\"NSDictionary\"@\"NSError\">32"
- "void *BT::libtailspinLibrary()"
- "void BT::USBPairingManager::setEarlyReturnDeviceProperties(IOHIDDeviceRef, Device *, BOOL, std::string)"
- "void BT::soft_tailspin_config_free(tailspin_config_t)"
- "void BT::soft_tailspin_enabled_set(tailspin_config_t, bool)"
- "void BT::soft_tailspin_kdbg_filter_subclass_set(tailspin_config_t, uint8_t, uint8_t, bool)"
```
