## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Sharing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3aab74` | `0x3ac358` | **`+0x17e4`** |
| `__TEXT.__cstring` | `0x3bb15` | `0x3bc05` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0xc89b` | `0xc97b` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0x1d0d0` | `0x1d188` | **`+0xb8`** |
| `__TEXT.__swift5_reflstr` | `0x4992` | `0x4a22` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x7b28` | `0x7b90` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x3d120` | `0x3d180` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xf5f0` | `0xf650` | **`+0x60`** |
| `__DATA.__data` | `0xd4f0` | `0xd530` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x10634` | `0x10664` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x9b58` | `0x9b7e` | **`+0x26`** |
| `__TEXT.__swift5_fieldmd` | `0x7fc4` | `0x7fe8` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x138a0` | `0x138c0` | **`+0x20`** |
| `__DATA.__bss` | `0x41450` | `0x41470` | **`+0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x4c68` | `0x4c80` | **`+0x18`** |
| `__TEXT.__const` | `0x266f4` | `0x26704` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2cc0` | `0x2cc8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x3658` | `0x3660` | **`+0x8`** |

### Other Changes

```diff

-2131.21.21.0.0
+2131.21.31.2.4

-  Functions: 25459
-  Symbols:   20713
-  CStrings:  9056
+  Functions: 25501
+  Symbols:   20725
+  CStrings:  9066
Symbols:
+ GCC_except_table174
+ GCC_except_table90
+ _SFIsDeviceHomeAccessory
+ _SFIsDeviceHomeAccessory.onceToken
+ _SFIsDeviceHomeAccessory.result
+ _SFShouldPrintSensitiveData
+ _SFShouldPrintSensitiveData.onceToken
+ _SFShouldPrintSensitiveData.sensitive
+ _SFStringForSensitiveData
+ _SFStringsForSensitiveData
+ ___SFIsDeviceHomeAccessory_block_invoke
+ ___SFShouldPrintSensitiveData_block_invoke
+ ___unnamed_72
+ _keypath_set.117Tm
+ _os_variant_has_internal_content
+ _symbolic _____ySdG 7Sharing13SFUserDefaultC
+ _symbolic _____ySdG 7Sharing18AirDropUserDefaultC
+ _symbolic _____ySdSg_____G 7Combine19CurrentValueSubjectC s5NeverO
- GCC_except_table166
- GCC_except_table168
- GCC_except_table175
- GCC_except_table84
- ___unnamed_69
- _keypath_set.106Tm
CStrings:
+ "%{public}@ advertisement request for %{public}@ succeeded"
+ "%{public}@ dispatching advertisement request for %{public}@ failed (%@)"
+ "%{public}@ dispatching request to advertise %{public}@"
+ "%~@"
+ "(null)"
+ "AudioAccessory11,1"
+ "B525"
+ "B525ish"
+ "HomeAccessory"
+ "WarpShockwaveEffectDuration_connectionHint"
+ "WarpShockwaveEffectDuration_shockwave"
+ "WarpShockwaveEffectTransitionSpeed"
+ "[%{public}@] Did send payload to %{public}@ for activity identifier %@. Handled: %{public}@"
+ "[%{public}@] Dispatching payload request to %{public}@ for %{public}@"
+ "[%{public}@] Found device %{public}@. Handled:%{public}@"
+ "[%{public}@] Lost device %{public}@. Handled:%{public}@"
+ "[%{public}@] Received advertisement %{public}@. Handled:%{public}@"
+ "[%{public}@] Received payload request from %{public}@ for %{public}@"
+ "[%{public}@] Received payload request from %{public}@ for %{public}@. Handled: %{public}@"
+ "iPhone18Pro"
+ "iPhone19,4"
+ "privateLoggingEnabled"
- "%@ advertisement request for %@ succeeded"
- "%@ dispatching advertisement request for %@ failed (%@)"
- "%@ dispatching request to advertise %@"
- "V63"
- "V64"
- "[%@] Did send payload to %@ for activity identifier %@. Handled: %@"
- "[%@] Dispatching payload request to %@ for %@"
- "[%@] Found device %@. Handled:%@"
- "[%@] Lost device %@. Handled:%@"
- "[%@] Received advertisement %@. Handled:%@"
- "[%@] Received payload request from %@ for %@"
- "[%@] Received payload request from %@ for %@. Handled: %@"
```
