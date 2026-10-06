## ColourSensorFilterPlugin

> `/System/Library/HIDPlugins/ColourSensorFilterPlugin.plugin/ColourSensorFilterPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36f24` | `0x3fb4c` | **`+0x8c28`** |
| `__TEXT.__const` | `0x1f18` | `0x4598` | **`+0x2680`** |
| `__TEXT.__cstring` | `0x280b` | `0x2e8b` | **`+0x680`** |
| `__TEXT.__gcc_except_tab` | `0x9c8` | `0xe64` | **`+0x49c`** |
| `__TEXT.__unwind_info` | `0xc80` | `0xfa0` | **`+0x320`** |
| `__DATA_CONST.__auth_ptr` | `0x1d8` | `0x4c0` | **`+0x2e8`** |
| `__TEXT.__auth_stubs` | `0x1350` | `0x14d0` | **`+0x180`** |
| `__DATA_CONST.__auth_got` | `0x9b8` | `0xa78` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x8ab9` | `0x8b39` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x2144` | `0x2185` | **`+0x41`** |
| `__DATA_CONST.__got` | `0x270` | `0x288` | **`+0x18`** |
| `__DATA.__bss` | `0x1760` | `0x1770` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2285.0.0.502.1
+2300.0.0.502.1

-  Functions: 1145
-  Symbols:   417
-  CStrings:  575
+  Functions: 1309
+  Symbols:   448
+  CStrings:  632
Symbols:
+ _CBU_DeviceHasDisplayRearALSSamplingPolicy
+ _CBU_IsDualColorRampThresholdingEnabled
+ _CBU_IsTransitionPolicyEnabled
+ _CFStringCreateCopy
+ _CFStringCreateMutableCopy
+ _CFStringCreateWithBytes
+ _CFStringGetBytes
+ _CFStringLowercase
+ __ZNKSt13runtime_error4whatEv
+ __ZNSt13runtime_errorC1EPKc
+ __ZNSt13runtime_errorC2EPKc
+ __ZNSt13runtime_errorD1Ev
+ __ZNSt13runtime_errorD2Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6appendEPKcm
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE9push_backEc
+ __ZNSt3__16localeC1ERKS0_
+ __ZNSt3__16localeaSERKS0_
+ __ZNSt3__18numpunctIcE2idE
+ __ZNSt3__18to_charsEPcS0_d
+ __ZNSt3__18to_charsEPcS0_dNS_12chars_formatE
+ __ZNSt3__18to_charsEPcS0_dNS_12chars_formatEi
+ __ZNSt3__18to_charsEPcS0_e
+ __ZNSt3__18to_charsEPcS0_eNS_12chars_formatE
+ __ZNSt3__18to_charsEPcS0_eNS_12chars_formatEi
+ __ZNSt3__18to_charsEPcS0_f
+ __ZNSt3__18to_charsEPcS0_fNS_12chars_formatE
+ __ZNSt3__18to_charsEPcS0_fNS_12chars_formatEi
+ __ZTISt13runtime_error
+ __ZTVN10__cxxabiv120__si_class_type_infoE
+ ___udivti3
+ ___umodti3
+ _memchr
- _load_integer_array_from_edt
CStrings:
+ " does not allow the "
+ " formatting argument"
+ " option"
+ "0"
+ "01"
+ "01234567"
+ "0123456789abcdef"
+ "0123456789abcdefghijklmnopqrstuvwxyz"
+ "0B"
+ "0X"
+ "0b"
+ "0x"
+ "An argument index may not have a negative value"
+ "Could not construct"
+ "Could not convert"
+ "End of input while parsing an argument index"
+ "End of input while parsing format specifier precision"
+ "Found sensor manufacturer: %@\n"
+ "Integral value outside the range of the char type"
+ "Replacement argument isn't a standard signed or unsigned integer type"
+ "The argument index is invalid"
+ "The argument index should end with a ':' or a '}'"
+ "The argument index starts with an invalid character"
+ "The argument index value is too large for the number of arguments supplied"
+ "The fill option contains an invalid value"
+ "The format specifier contains malformed Unicode characters"
+ "The format specifier for "
+ "The format specifier should consume the input or end with a '}'"
+ "The format string contains an invalid escape sequence"
+ "The format string terminates at a '{'"
+ "The numeric value of the format specifier is too large"
+ "The precision option does not contain a value or an argument index"
+ "The replacement field misses a terminating '}'"
+ "The type does not fit in the mask"
+ "The type option contains an invalid value for "
+ "The type option contains an invalid value for a string formatting argument"
+ "The value of the argument index exceeds its maximum value"
+ "The width option should not have a leading zero"
+ "Using automatic argument numbering in manual argument numbering mode"
+ "Using manual argument numbering in automatic argument numbering mode"
+ "[ma-filter] Initializing with thresholds: %s (from \"%s\")"
+ "[ma-filter] Property \"%s\" not present"
+ "[ma-filter] Thresholds count %zu (%s) from property %s does not correspond to ALS channel count %d."
+ "a bool"
+ "a character"
+ "a floating-point"
+ "a pointer"
+ "alternate form"
+ "an integer"
+ "false"
+ "infnanINFNAN"
+ "locale-specific form"
+ "ma-channel-thr-{}"
+ "manufacturer"
+ "precision"
+ "sign"
+ "true"
+ "vector"
+ "zero-padding"
- "Initializing channel-wise MA filter with thresholds: %s"
- "Moving average thresholds count %zu does not correspond to ALS channel count %d. Possibly a typo in EDT?"
```
