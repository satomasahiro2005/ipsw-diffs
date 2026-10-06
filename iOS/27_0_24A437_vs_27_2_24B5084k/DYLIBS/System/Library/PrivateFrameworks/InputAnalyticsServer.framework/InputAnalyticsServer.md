## InputAnalyticsServer

> `/System/Library/PrivateFrameworks/InputAnalyticsServer.framework/InputAnalyticsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e290` | `0x8153c` | **`+0x32ac`** |
| `__AUTH_CONST.__cfstring` | `0x6aa0` | `0x6ea0` | **`+0x400`** |
| `__TEXT.__oslogstring` | `0x7b50` | `0x7f20` | **`+0x3d0`** |
| `__TEXT.__cstring` | `0x64e2` | `0x67f2` | **`+0x310`** |
| `__AUTH_CONST.__objc_const` | `0xa5a8` | `0xa7b0` | **`+0x208`** |
| `__TEXT.__objc_methlist` | `0x62a4` | `0x641c` | **`+0x178`** |
| `__DATA_CONST.__objc_selrefs` | `0x31c8` | `0x32e0` | **`+0x118`** |
| `__AUTH.__objc_data` | `0xa88` | `0xb78` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0xd28` | `0xe0c` | **`+0xe4`** |
| `__DATA_CONST.__const` | `0x17b8` | `0x1890` | **`+0xd8`** |
| `__TEXT.__unwind_info` | `0x1818` | `0x18d0` | **`+0xb8`** |
| `__AUTH_CONST.__const` | `0x1558` | `0x15f8` | **`+0xa0`** |
| `__DATA.__bss` | `0x770` | `0x7f0` | **`+0x80`** |
| `__AUTH_CONST.__objc_intobj` | `0x1878` | `0x18f0` | **`+0x78`** |
| `__DATA.__data` | `0x4e8` | `0x548` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x5f8` | `0x658` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x1930` | `0x1958` | **`+0x28`** |
| `__DATA_DIRTY.__bss` | `0x678` | `0x650` | **`-0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x3c8` | `0x3e0` | **`+0x18`** |
| `__TEXT.__const` | `0xab0` | `0xac0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xc00` | `0xbf8` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x218` | `0x220` | **`+0x8`** |

### Other Changes

```diff

-153.0.0.0.0
+154.1.4.0.0

+  - /System/Library/PrivateFrameworks/BatteryCenter.framework/BatteryCenter

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 2848
-  Symbols:   982
-  CStrings:  1500
+  Functions: 2902
+  Symbols:   986
+  CStrings:  1542
Symbols:
+ _IAPayloadKeyImageGenerationNumInputImages
+ _IAPayloadValueSidecarInteractionModalitySidecar
+ _IOHIDManagerRegisterDeviceRemovalCallback
+ _OBJC_CLASS_$_BCBatteryDeviceController
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
- _IOHIDDeviceGetProperty
CStrings:
+ "!!"
+ "3!"
+ "ChargingStateChanged"
+ "Concise Rewrite"
+ "Failed to initialize the pencil data store. Will retry on the next call to sharedInstance."
+ "Failed to initialize the sidecar data store. Will retry on the next call to sharedInstance."
+ "Failed to initialize the system table. Will retry on the next call to sharedInstance."
+ "Failed to open the pencil data store tables (usageTable ok: %d, errorTable ok: %d). Will retry on the next call to sharedInstance."
+ "Failed to open the sidecar data store tables (usageTable ok: %d, lifecycleTable ok: %d). Will retry on the next call to sharedInstance."
+ "Friendly Rewrite"
+ "IASImageGenerationDirectManipulationAnalyzer.m"
+ "IASPencilAnalyzerDataStoreBatteryTable"
+ "Key Points"
+ "List"
+ "NSUserDefaults returns value: %@; for key: %@"
+ "PKPencilDoubleTapVisualIntelligenceHighlightEnabledKey"
+ "PKUIPencilHoverPreviewEnabledKey"
+ "Professional Rewrite"
+ "Restored charging state from the data store: state = %lu, battery = %ld, time = %f, identifier=%{private}@, pencilVersion = %lu"
+ "Summary"
+ "Table"
+ "The battery table has %lu rows but should only ever have one. Using the one with the newest timeAtPeriodStart."
+ "This analyzer does not and should not emit CoreAnalytics event."
+ "XCTestCase"
+ "[%{private}@] Biome UserInteraction: %{sensitive}@"
+ "accessoryIdentifier"
+ "batteryChange"
+ "batteryEnd"
+ "batteryPercentage"
+ "batteryPercentageAtPeriodStart"
+ "batteryStart"
+ "chargingState"
+ "com.apple.inputAnalytics.pencilBattery"
+ "com.apple.inputAnalytics.server.IASImageGenerationDirectManipulationAnalyzer"
+ "com.apple.preferences.sounds"
+ "connectedDevicesDidChange pencil productIdentifier=%ld, version=%lu"
+ "effects-pencil-haptic"
+ "hapticsEnablement"
+ "identifierAtPeriodStart"
+ "just published a pencilBattery event with state=Unspecified. This shouldn't happen."
+ "numInputImages"
+ "pencilState"
+ "secondsInState"
+ "shadowEnablement"
+ "singleRowKey"
+ "timeAtPeriodStart"
+ "viAcceleratorState"
- "!"
- "#"
- "C!"
- "ProductID"
- "stylusDeviceAddedCallback pencil productID=%lu"
```
