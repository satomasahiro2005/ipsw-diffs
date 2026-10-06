## AppleAOPAudioPlugin

> `/System/Library/Audio/Plug-Ins/HAL/AppleAOPAudioPlugin.driver/AppleAOPAudioPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1828c` | `0x182d0` | **`+0x44`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ __Z13ReadInputDatajdPvbjjS_RNSt3__110shared_ptrI23AOPAudioDeviceHWManagerEERNS1_IN12CADeprecated7CAMutexEEEb : 1040 -> 1036
~ __ZNK20CAAudioChannelLayouteqERKS_ : 180 -> 192
~ __ZNK20CAAudioChannelLayoutneERKS_ : 180 -> 192
~ __ZN14CACFDictionary10PrintToLogEPK14__CFDictionaryj : 516 -> 488
~ __ZN10CACFString10PrintToLogEPK10__CFStringj : 348 -> 344
~ __ZN10CACFNumber10PrintToLogEPK10__CFNumberj : 1156 -> 1152
~ __ZN11CACFBoolean10PrintToLogEPK11__CFBooleanj : 280 -> 276
~ __ZN9CACFArray10PrintToLogEPK9__CFArrayj : 460 -> 456
~ __ZN20CAAudioChannelLayout6CreateEj : 164 -> 180
~ __ZN20CAAudioChannelLayout15SetAllToUnknownER18AudioChannelLayoutj : 48 -> 64
~ __ZN24CAStreamBasicDescription8FromTextEPKcR27AudioStreamBasicDescription : 1396 -> 1400
~ __ZN12CADeprecated15CADispatchQueue32InstallMachPortDeathNotificationEjU13block_pointerFvvE : 528 -> 556
~ __ZN12CADeprecated15CADispatchQueue23InstallMachPortReceiverEjU13block_pointerFvvE : 528 -> 556
~ __ZN12CADeprecated15CADispatchQueue22RemoveMachPortReceiverEjU13block_pointerFvvE : 336 -> 344
~ sub_14710 -> sub_1475c : 380 -> 372
CStrings:
+ "17:41:53"
+ "Jun  9 2026"
- "07:55:45"
- "May 21 2026"
```
