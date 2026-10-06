## CarAccessoryFramework

> `/System/Library/PrivateFrameworks/CarAccessoryFramework.framework/CarAccessoryFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10cc10` | `0x10ec40` | **`+0x2030`** |
| `__AUTH_CONST.__objc_const` | `0x50188` | `0x50bf0` | **`+0xa68`** |
| `__TEXT.__objc_methlist` | `0x1901c` | `0x1930c` | **`+0x2f0`** |
| `__DATA_CONST.__objc_arraydata` | `0xc218` | `0xc4c8` | **`+0x2b0`** |
| `__AUTH_CONST.__objc_dictobj` | `0x66d0` | `0x6860` | **`+0x190`** |
| `__AUTH_CONST.__cfstring` | `0xdf20` | `0xe020` | **`+0x100`** |
| `__DATA.__data` | `0x49a0` | `0x4a60` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x7da0` | `0x7e50` | **`+0xb0`** |
| `__AUTH.__objc_data` | `0xf0` | `0x190` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x7ef1` | `0x7f7f` | **`+0x8e`** |
| `__TEXT.__unwind_info` | `0x3bd0` | `0x3c30` | **`+0x60`** |
| `__DATA_CONST.__got` | `0xf10` | `0xf20` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xdd0` | `0xde0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x620` | `0x630` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x5c0` | `0x5d0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x7f0` | `0x800` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x2738` | `0x2740` | **`+0x8`** |

### Other Changes

```diff

-540.1.0.0.0
+542.7.0.0.0

-  Functions: 7764
-  Symbols:   13172
-  CStrings:  2188
+  Functions: 7815
+  Symbols:   13253
+  CStrings:  2196
Symbols:
+ +[CAFEqualizerPresets observerProtocol]
+ +[CAFEqualizerPresets serviceIdentifier]
+ +[CAFSoundDistributionPresets observerProtocol]
+ +[CAFSoundDistributionPresets serviceIdentifier]
+ -[CAFAudioSettings equalizerPresetsService]
+ -[CAFAudioSettings equalizerPresets]
+ -[CAFAudioSettings soundDistributionPresetsService]
+ -[CAFAudioSettings soundDistributionPresets]
+ -[CAFChargingTime elapsedTimeCharacteristic]
+ -[CAFChargingTime elapsedTimeInvalid]
+ -[CAFChargingTime elapsedTimeMeasurementRange]
+ -[CAFChargingTime elapsedTimeRange]
+ -[CAFChargingTime elapsedTime]
+ -[CAFChargingTime hasElapsedTime]
+ -[CAFChargingTime registeredForElapsedTime]
+ -[CAFEqualizerPresets _characteristicDidUpdate:fromGroupUpdate:]
+ -[CAFEqualizerPresets addObserver:]
+ -[CAFEqualizerPresets hasPresetLabel]
+ -[CAFEqualizerPresets name]
+ -[CAFEqualizerPresets presetLabelCharacteristic]
+ -[CAFEqualizerPresets presetLabel]
+ -[CAFEqualizerPresets registerObserver:]
+ -[CAFEqualizerPresets registeredForPresetLabel]
+ -[CAFEqualizerPresets registeredForSelectSettingEntryList]
+ -[CAFEqualizerPresets registeredForSelectedEntryIndex]
+ -[CAFEqualizerPresets removeObserver:]
+ -[CAFEqualizerPresets selectSettingEntryListCharacteristic]
+ -[CAFEqualizerPresets selectSettingEntryList]
+ -[CAFEqualizerPresets selectedEntryIndexCharacteristic]
+ -[CAFEqualizerPresets selectedEntryIndexRange]
+ -[CAFEqualizerPresets selectedEntryIndex]
+ -[CAFEqualizerPresets setSelectedEntryIndex:]
+ -[CAFEqualizerPresets unregisterObserver:]
+ -[CAFSoundDistributionPresets _characteristicDidUpdate:fromGroupUpdate:]
+ -[CAFSoundDistributionPresets addObserver:]
+ -[CAFSoundDistributionPresets hasPresetLabel]
+ -[CAFSoundDistributionPresets name]
+ -[CAFSoundDistributionPresets presetLabelCharacteristic]
+ -[CAFSoundDistributionPresets presetLabel]
+ -[CAFSoundDistributionPresets registerObserver:]
+ -[CAFSoundDistributionPresets registeredForPresetLabel]
+ -[CAFSoundDistributionPresets registeredForSelectSettingEntryList]
+ -[CAFSoundDistributionPresets registeredForSelectedEntryIndex]
+ -[CAFSoundDistributionPresets removeObserver:]
+ -[CAFSoundDistributionPresets selectSettingEntryListCharacteristic]
+ -[CAFSoundDistributionPresets selectSettingEntryList]
+ -[CAFSoundDistributionPresets selectedEntryIndexCharacteristic]
+ -[CAFSoundDistributionPresets selectedEntryIndexRange]
+ -[CAFSoundDistributionPresets selectedEntryIndex]
+ -[CAFSoundDistributionPresets setSelectedEntryIndex:]
+ -[CAFSoundDistributionPresets unregisterObserver:]
+ _CAFCharacteristicTypeElapsedTime
+ _CAFCharacteristicTypePresetLabel
+ _CAFServiceTypeEqualizerPresets
+ _CAFServiceTypeSoundDistributionPresets
+ _OBJC_CLASS_$_CAFEqualizerPresets
+ _OBJC_CLASS_$_CAFSoundDistributionPresets
+ _OBJC_METACLASS_$_CAFEqualizerPresets
+ _OBJC_METACLASS_$_CAFSoundDistributionPresets
+ __OBJC_$_CLASS_METHODS_CAFEqualizerPresets
+ __OBJC_$_CLASS_METHODS_CAFSoundDistributionPresets
+ __OBJC_$_INSTANCE_METHODS_CAFEqualizerPresets
+ __OBJC_$_INSTANCE_METHODS_CAFSoundDistributionPresets
+ __OBJC_$_PROP_LIST_CAFEqualizerPresets
+ __OBJC_$_PROP_LIST_CAFSoundDistributionPresets
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CAFEqualizerPresetsObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CAFSoundDistributionPresetsObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CAFEqualizerPresetsObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CAFSoundDistributionPresetsObserver
+ __OBJC_$_PROTOCOL_REFS_CAFEqualizerPresetsObserver
+ __OBJC_$_PROTOCOL_REFS_CAFSoundDistributionPresetsObserver
+ __OBJC_CLASS_RO_$_CAFEqualizerPresets
+ __OBJC_CLASS_RO_$_CAFSoundDistributionPresets
+ __OBJC_LABEL_PROTOCOL_$_CAFEqualizerPresetsObserver
+ __OBJC_LABEL_PROTOCOL_$_CAFSoundDistributionPresetsObserver
+ __OBJC_METACLASS_RO_$_CAFEqualizerPresets
+ __OBJC_METACLASS_RO_$_CAFSoundDistributionPresets
+ __OBJC_PROTOCOL_$_CAFEqualizerPresetsObserver
+ __OBJC_PROTOCOL_$_CAFSoundDistributionPresetsObserver
+ __OBJC_PROTOCOL_REFERENCE_$_CAFEqualizerPresetsObserver
+ __OBJC_PROTOCOL_REFERENCE_$_CAFSoundDistributionPresetsObserver
CStrings:
+ "0x0000000013000006"
+ "0x0000000013000007"
+ "0x0000000030000029"
+ "0x0000000033000010"
+ "ElapsedTime"
+ "EqualizerPresets"
+ "PresetLabel"
+ "SoundDistributionPresets"
```
