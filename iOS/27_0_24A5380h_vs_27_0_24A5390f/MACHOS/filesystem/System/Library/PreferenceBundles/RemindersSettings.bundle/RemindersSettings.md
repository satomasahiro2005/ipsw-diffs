## RemindersSettings

> `/System/Library/PreferenceBundles/RemindersSettings.bundle/RemindersSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20f40` | `0x213d0` | **`+0x490`** |
| `__TEXT.__objc_methname` | `0x3865` | `0x3a95` | **`+0x230`** |
| `__DATA_CONST.__cfstring` | `0x900` | `0x9e0` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x137d` | `0x144d` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x2120` | `0x21c0` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x1728` | `0x1788` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xbdc` | `0xc24` | **`+0x48`** |
| `__DATA.__objc_selrefs` | `0xb90` | `0xbd0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x4e0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x94` | `0x9c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x808` | `0x810` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4040.0.0.0.0
+4043.0.0.0.0

-  Functions: 648
-  Symbols:   308
-  CStrings:  698
+  Functions: 656
+  Symbols:   310
+  CStrings:  715
Symbols:
+ _OBJC_CLASS_$_REMGroceryAvailabilityBridge
+ _OBJC_CLASS_$__TtC19ReminderKitInternal9Analytics
+ _REMSettingsNaturalLanguageInputIdentifier
- _OBJC_CLASS_$__TtC19ReminderKitInternal20REMGroceryDummyModel
CStrings:
+ "%@#NATURAL_LANGUAGE_INPUT"
+ "Recognize Reminder Details"
+ "T@\"<REMUserDefaultsObserveToken>\",&,N,V_daemonUserDefaultsEnableNaturalLanguageInputObserver"
+ "T@\"PSSpecifier\",&,N,V_enableNaturalLanguageInput"
+ "Toggle Recognize Reminder Details Settings"
+ "_daemonUserDefaultsEnableNaturalLanguageInputObserver"
+ "_enableNaturalLanguageInput"
+ "daemonUserDefaultsEnableNaturalLanguageInputObserver"
+ "enableNaturalLanguageInput"
+ "enableNaturalLanguageInput:"
+ "isClassicModelPreferredForLocaleWithIdentifier:"
+ "magicCompose.settingToggle.disable"
+ "magicCompose.settingToggle.enable"
+ "observeEnableNaturalLanguageInputWithBlock:"
+ "postUserOperationEventWithOperationId:viewLocation:"
+ "setDaemonUserDefaultsEnableNaturalLanguageInputObserver:"
+ "setEnableNaturalLanguageInput:"
+ "setEnableNaturalLanguageInput:specifier:"
- "isGrocerySupportedForLocaleWithIdentifier:"
```
