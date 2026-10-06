## assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x371fcc` | `0x372924` | **`+0x958`** |
| `__TEXT.__oslogstring` | `0x45d7e` | `0x45eeb` | **`+0x16d`** |
| `__TEXT.__objc_methname` | `0x61bac` | `0x61cb0` | **`+0x104`** |
| `__TEXT.__cstring` | `0x52dfa` | `0x52ede` | **`+0xe4`** |
| `__TEXT.__objc_stubs` | `0x47440` | `0x474c0` | **`+0x80`** |
| `__TEXT.__dlopen_cstrs` | `0x99d` | `0x9e9` | **`+0x4c`** |
| `__TEXT.__gcc_except_tab` | `0x3aac` | `0x3ae4` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x155e0` | `0x15610` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xff45` | `0xff75` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xa520` | `0xa548` | **`+0x28`** |
| `__DATA.__objc_const` | `0x34c58` | `0x34c78` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x23710` | `0x23730` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x143e8` | `0x14400` | **`+0x18`** |
| `__DATA.__bss` | `0xdd0` | `0xde0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x3840` | `0x3850` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1c30` | `0x1c38` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2694` | `0x2698` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
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
- `__TEXT.__eh_frame`

### Other Changes

```diff

-3600.68.61.11.1
+3600.68.61.11.9

-  Functions: 14626
-  Symbols:   3004
-  CStrings:  27881
+  Functions: 14634
+  Symbols:   3005
+  CStrings:  27900
Symbols:
+ _NSStringFromAFSiriStatus
CStrings:
+ "%s #SiriAvailability computed status=%{public}@ restrictionReasons=%{public}@ isAssistantEnabled=%{bool}d"
+ "%s #SiriAvailability recomputing: assessment mode active changed"
+ "%s #SiriAvailability recomputing: first unlock since boot — data-protected capability inputs are now readable"
+ "%s Siri restriction lifted - restoring assistant to its pre-restriction state: %d"
+ "-[ADSiriCapabilitiesStore handleAssessmentModeActiveDidChange]"
+ "-[ADSiriCapabilitiesStore handleFirstUnlockNotification:]"
+ "5"
+ "@\"AEAssessmentModeGestalt\""
+ "AEAssessmentModeGestalt"
+ "Class getAEAssessmentModeGestaltClass(void)_block_invoke"
+ "MobileAssistantDaemons-3600.68.61.11.9"
+ "_assessmentModeGestalt"
+ "addObserver:forKeyPath:options:context:"
+ "assistantEnabledBeforeRestriction"
+ "handleAssessmentModeActiveDidChange"
+ "handleFirstUnlockNotification:"
+ "observeValueForKeyPath:ofObject:change:context:"
+ "removeObserver:forKeyPath:"
+ "setAssistantEnabledBeforeRestriction:"
+ "softlink:o:path:/System/Library/PrivateFrameworks/AACCore.framework/AACCore"
+ "v48@0:8@16@24@32^v40"
+ "void *AACCoreLibrary(void)"
- "37"
- "MobileAssistantDaemons-3600.68.61.11.1"
- "isDeviceScreenON"
```
