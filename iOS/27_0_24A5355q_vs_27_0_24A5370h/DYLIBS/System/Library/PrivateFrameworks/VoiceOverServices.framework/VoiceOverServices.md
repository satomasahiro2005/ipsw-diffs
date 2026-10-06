## VoiceOverServices

> `/System/Library/PrivateFrameworks/VoiceOverServices.framework/VoiceOverServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34a70` | `0x349ac` | **`-0xc4`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0
Functions:
~ -[VOSGestureCategory hash] : 268 -> 264
~ +[VOSGesture gestureWithStringValue:] : 312 -> 308
~ +[VOSScreenreaderMode modeWithStringValue:] : 312 -> 308
~ -[VOSCommandManager _validateUserProfileDiscrepancies:] : 1376 -> 1368
~ __VOSCrystalReplacementForTableIdentifier : 588 -> 584
~ __VOSHasReplaceableTableInRotorItems : 336 -> 332
~ _VOSCrystalMigrateBrailleTableReplacements : 2308 -> 2304
~ +[VOSSettingsItem settingsIDtoItemMap:] : 340 -> 336
~ +[VOSOutputEvent eventWithStringValue:] : 312 -> 308
~ -[_VOSProfileCommand _initWithCommand:gestures:keyboardShortcuts:quickNavShortcuts:secondaryCommands:] : 1088 -> 1072
~ -[_VOSProfileCommand profileGestureForGesture:] : 336 -> 332
~ -[_VOSProfileCommand profileKeyboardShortcutForKeyChord:] : 336 -> 332
~ -[_VOSProfileCommand profileQuickNavShortcutForKeyChord:] : 336 -> 332
~ +[VOSCommandCategory categories:containsCommand:] : 284 -> 280
~ -[_VOSProfileMode _initWithMode:commands:] : 388 -> 384
~ +[VOSCommand builtInCommandWithStringValue:] : 312 -> 308
~ +[VOSCommand commandForVOSEventCommand:] : 352 -> 348
~ -[VOSSettingsHelper _enabledVoices] : 668 -> 664
~ -[VOSSettingsHelper userSettingsItems] : 1136 -> 1128
~ -[VOSSettingsHelper saveUserSettingsItems:] : 472 -> 468
~ -[VOSSettingsHelper possibleValuesForSettingsItem:] : 1552 -> 1548
~ -[VOSBluetoothManager isValidBrailleDevice:] : 1340 -> 1336
~ -[VOSBluetoothManager isPairedDeviceBrailleDisplay:] : 476 -> 472
~ ___38-[VOSOutputEventDispatcher sendEvent:]_block_invoke : 428 -> 424
~ -[VOSCommandProfile debugDescription] : 1192 -> 1180
~ -[VOSCommandProfile commandForTouchGesture:withResolver:] : 900 -> 896
~ -[VOSCommandProfile _rawCommandForTouchGesture:withResolver:] : 580 -> 576
~ -[VOSCommandProfile commandForKeyChord:withResolver:] : 928 -> 924
~ -[VOSCommandProfile _rawCommandForKeyChord:withResolver:] : 604 -> 600
~ -[VOSCommandProfile _resolvedSecondaryCommandForProfileCommand:resolver:] : 584 -> 580
~ -[VOSCommandProfile allCommandsWithResolver:] : 508 -> 504
~ -[VOSCommandProfile allShortcutBindingsWithResolver:] : 676 -> 672
~ -[VOSCommandProfile gestureBindingsForCommand:withResolver:] : 580 -> 572
~ -[VOSCommandProfile shortcutBindingsForCommand:withResolver:] : 612 -> 604
~ -[VOSCommandProfile _profileModeForScreenreaderMode:] : 336 -> 332
~ -[VOSCommandProfile _profileCommandForCommand:inMode:] : 880 -> 876
~ +[VOSCommandProfile _addGesturesToCommand:fromCommandProperties:overlayProperties:] : 528 -> 524
~ +[VOSCommandProfile _addKeyboardShortcutsToCommand:fromCommandProperties:overlayProperties:] : 408 -> 404
~ +[VOSCommandProfile _addQuickNavShortcutsToCommand:fromCommandProperties:overlayProperties:] : 408 -> 404
~ +[VOSCommandProfile _profileKeyChordsFromDictionaryValue:] : 476 -> 472
```
