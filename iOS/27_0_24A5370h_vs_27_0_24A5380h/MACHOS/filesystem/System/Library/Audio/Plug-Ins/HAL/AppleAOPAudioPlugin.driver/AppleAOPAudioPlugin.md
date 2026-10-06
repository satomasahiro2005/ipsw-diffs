## AppleAOPAudioPlugin

> `/System/Library/Audio/Plug-Ins/HAL/AppleAOPAudioPlugin.driver/AppleAOPAudioPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x182d0` | `0x182a4` | **`-0x2c`** |

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
~ __ZN24CAStreamBasicDescription8FromTextEPKcR27AudioStreamBasicDescription : 1400 -> 1388
~ __ZN12CADeprecated15CADispatchQueue32InstallMachPortDeathNotificationEjU13block_pointerFvvE : 556 -> 544
~ __ZN12CADeprecated15CADispatchQueue31RemoveMachPortDeathNotificationEj : 316 -> 312
~ __ZN12CADeprecated15CADispatchQueue23InstallMachPortReceiverEjU13block_pointerFvvE : 556 -> 544
~ __ZN12CADeprecated15CADispatchQueue22RemoveMachPortReceiverEjU13block_pointerFvvE : 344 -> 340
CStrings:
+ "02:55:34"
+ "Jun 23 2026"
- "17:41:53"
- "Jun  9 2026"
```
