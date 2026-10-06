## HearingUtilities

> `/System/Library/PrivateFrameworks/HearingUtilities.framework/HearingUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb6570` | `0xb68dc` | **`+0x36c`** |
| `__TEXT.__oslogstring` | `0xeee3` | `0xf1e3` | **`+0x300`** |
| `__AUTH.__objc_data` | `0x1320` | `0x11d8` | **`-0x148`** |
| `__DATA_DIRTY.__objc_data` | `0x460` | `0x5a8` | **`+0x148`** |
| `__DATA_DIRTY.__data` | `—` | `0xc8` | **`+0xc8`** |
| `__DATA.__data` | `0x1020` | `0xf80` | **`-0xa0`** |
| `__DATA.__bss` | `0x850` | `0x7e0` | **`-0x70`** |
| `__DATA_DIRTY.__bss` | `0xa8` | `0x110` | **`+0x68`** |
| `__TEXT.__cstring` | `0x6046` | `0x609b` | **`+0x55`** |
| `__AUTH_CONST.__cfstring` | `0x5d00` | `0x5d40` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0xbdb0` | `0xbdf0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x36e8` | `0x3710` | **`+0x28`** |
| `__AUTH.__data` | `0xc8` | `0xa8` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x54f8` | `0x5508` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x919c` | `0x91ac` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x9ec` | `0x9f4` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x760` | `0x768` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2c38` | `0x2c30` | **`-0x8`** |

### Other Changes

```diff

-530.0.0.0.0
+534.0.0.0.0

-  CStrings:  2060
+  CStrings:  2071
Symbols:
+ -[HUComfortSoundsController scheduleFileWithRetryCount:]
+ -[HUNoiseController writeAttenuationSampleToHealth]
+ GCC_except_table3109
+ GCC_except_table3131
+ GCC_except_table3139
+ GCC_except_table3148
+ GCC_except_table3157
+ GCC_except_table3160
+ GCC_except_table3162
+ GCC_except_table3215
+ GCC_except_table3242
+ GCC_except_table3329
+ GCC_except_table3335
+ GCC_except_table3341
+ GCC_except_table3344
+ GCC_except_table3356
+ GCC_except_table3364
+ GCC_except_table3371
+ GCC_except_table3374
+ GCC_except_table3382
+ GCC_except_table3384
+ GCC_except_table3394
+ GCC_except_table3397
+ GCC_except_table3406
+ _OBJC_IVAR_$_HUNoiseController._dBAUnit
+ _OBJC_IVAR_$_HUNoiseController._useArtifactFilterMigration
+ ___51-[HUNoiseController writeAttenuationSampleToHealth]_block_invoke
+ ___56-[HUComfortSoundsController scheduleFileWithRetryCount:]_block_invoke
+ ___56-[HUComfortSoundsController scheduleFileWithRetryCount:]_block_invoke_2
+ ___block_descriptor_41_e8_32s_e35_v32?0"AXHearingAidDevice"8Q16^B24ls32l8
- -[HUNoiseController writeAttentuationSampleToHealth]
- GCC_except_table3108
- GCC_except_table3129
- GCC_except_table3138
- GCC_except_table3147
- GCC_except_table3156
- GCC_except_table3159
- GCC_except_table3161
- GCC_except_table3214
- GCC_except_table3241
- GCC_except_table3311
- GCC_except_table3330
- GCC_except_table3336
- GCC_except_table3342
- GCC_except_table3345
- GCC_except_table3357
- GCC_except_table3365
- GCC_except_table3372
- GCC_except_table3375
- GCC_except_table3383
- GCC_except_table3385
- GCC_except_table3395
- GCC_except_table3398
- GCC_except_table3407
- ___41-[HUComfortSoundsController scheduleFile]_block_invoke
- ___41-[HUComfortSoundsController scheduleFile]_block_invoke_2
- ___52-[HUNoiseController writeAttentuationSampleToHealth]_block_invoke
- ___58-[AXHearingAidDeviceController pairedHearingAidsDidChange]_block_invoke_3
- ___58-[AXHearingAidDeviceController pairedHearingAidsDidChange]_block_invoke_4
- _getHKUnitClass
CStrings:
+ "CentralManager: No peripherals with IDs, unpairing %@"
+ "Error playing node: %@"
+ "Error starting engine (attempt %ld): %@"
+ "HearingAidDevice: Set Paired=YES"
+ "HearingAidDeviceController: pairedHearingAidsDidChange, Adding to Loaded and Available device: %@"
+ "HearingAidDeviceController: pairedHearingAidsDidChange, Adding to persistent device: %@"
+ "HearingAidDeviceController: pairedHearingAidsDidChange, Available devices:\n%@"
+ "HearingAidDeviceController: pairedHearingAidsDidChange, Created device for persistent representation\n%@"
+ "HearingAidDeviceController: pairedHearingAidsDidChange, Found device for persistent representation\n%@"
+ "HearingAidDeviceController: pairedHearingAidsDidChange, No peripheral IDs %@, unpairing persistent device\n%@"
+ "HearingAidDeviceController: pairedHearingAidsDidChange, Persistent devices:\n%@"
+ "HearingAidDeviceController: pairedHearingAidsDidChange, isFromiCloud: %d, keepDevicePaired: %d"
+ "HearingAidDeviceController: pairedHearingAidsDidChange, match peripheral IDs, set Paired=YES to connected device: %@"
+ "HearingAidDeviceController: pairedHearingAidsDidChange, no peripheral IDs, Disconnecting and Unpairing connected device: %@"
+ "HearingAidTooManyDisconnectionAlertDescription_Generic"
+ "HearingAidTooManyDisconnectionAlertTitle_Generic"
+ "Max retries (%d) reached starting engine: %@. Stopping."
+ "_Generic"
- "CentralManager: No peripherals with identifiers, unpairing %@"
- "Error starting engine %@"
- "HearingAidDevice: Set isPaired to YES"
- "HearingAidDeviceController: pairedHearingAidsDidChange \nPersistent device: %@,\n%@"
- "HearingAidDeviceController: pairedHearingAidsDidChange, No peripheral identifiers %@, unpairing persistent device\n%@"
- "HearingAidDeviceController: pairedHearingAidsDidChange, Updating Persistent/Loaded/Available with device\n%@"
- "HearingAidDeviceGenericLabel"
```
