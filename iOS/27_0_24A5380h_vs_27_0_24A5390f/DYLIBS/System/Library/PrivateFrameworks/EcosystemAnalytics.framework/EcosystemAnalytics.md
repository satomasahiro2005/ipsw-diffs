## EcosystemAnalytics

> `/System/Library/PrivateFrameworks/EcosystemAnalytics.framework/EcosystemAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41fdc` | `0x44728` | **`+0x274c`** |
| `__TEXT.__cstring` | `0x5955` | `0x5de1` | **`+0x48c`** |
| `__AUTH_CONST.__const` | `0x2640` | `0x2900` | **`+0x2c0`** |
| `__DATA.__bss` | `0xb80` | `0xd00` | **`+0x180`** |
| `__TEXT.__const` | `0x1592` | `0x1712` | **`+0x180`** |
| `__DATA_DIRTY.__data` | `0xee8` | `0xfc0` | **`+0xd8`** |
| `__TEXT.__eh_frame` | `0x4f8` | `0x5d0` | **`+0xd8`** |
| `__TEXT.__swift5_typeref` | `0x708` | `0x7c0` | **`+0xb8`** |
| `__TEXT.__swift5_capture` | `0x57c` | `0x630` | **`+0xb4`** |
| `__TEXT.__unwind_info` | `0x728` | `0x7c8` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0xa94` | `0xb20` | **`+0x8c`** |
| `__AUTH_CONST.__objc_const` | `0xb38` | `0xb98` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x50` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xa78` | `0xac0` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `—` | `0x40` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x927` | `0x967` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c0` | `0x2f0` | **`+0x30`** |
| `__DATA.__data` | `0x220` | `0x1f8` | **`-0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x940` | `0x960` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1a8` | `0x1b8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x64` | `0x70` | **`+0xc`** |
| `__DATA.__common` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x84` | `0x8c` | **`+0x8`** |

### Other Changes

```diff

-38.0.0.0.0
+39.0.1.0.0

-  Functions: 822
-  Symbols:   534
-  CStrings:  390
+  Functions: 878
+  Symbols:   566
+  CStrings:  407
Symbols:
+ GCC_except_table0
+ _NMExceptionTrapErrorDomain
+ _NMExceptionTrapExceptionNameKey
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_NSError
+ _OBJC_CLASS_$_NSMutableDictionary
+ _OBJC_EHTYPE_$_NSException
+ __Unwind_Resume
+ ___CFConstantStringClassReference
+ ___objc_personality_v0
+ ___swift_closure_destructor.38Tm
+ ___swift_closure_destructor.58Tm
+ ___swift_memcpy32_8
+ ___swift_memcpy33_8
+ _get_enum_tag_for_layout_string 18EcosystemAnalytics18SymbolicationOwnerO
+ _nm_macho_header_is_valid
+ _nm_tryBlock
+ _objc_begin_catch
+ _objc_end_catch
+ _objc_retain_x19
+ _strncmp
+ _swift_cvw_enumFn_getEnumTag
+ _swift_errorRetain
+ _symbolic Ig_
+ _symbolic SDySSSDySS_____GG 18EcosystemAnalytics11LoadCommandV
+ _symbolic SS4uuid_SS4patht
+ _symbolic SS6reason_t
+ _symbolic SaySDySSSo8NSObjectCGG
+ _symbolic SaySDySSSo8NSObjectCGGz_Xx
+ _symbolic _____ 18EcosystemAnalytics18ObjCExceptionErrorV
+ _symbolic _____ 18EcosystemAnalytics18SymbolicationOwnerO
+ _symbolic _____ 18EcosystemAnalytics21SystemPressureMonitorO
+ _symbolic _____SgXw 18EcosystemAnalytics24MachOAnalysisCoordinatorC
+ _symbolic _____SgXwz_Xx 18EcosystemAnalytics24MachOAnalysisCoordinatorC
+ _symbolic ______pIgzo_ s5ErrorP
+ _symbolic ______pSg s5ErrorP
+ _symbolic _____ySSSDySS_____GG s18_DictionaryStorageC 18EcosystemAnalytics11LoadCommandV
+ _symbolic _____y_____G s11_SetStorageC s5Int32V
+ _type_layout_string 18EcosystemAnalytics18ObjCExceptionErrorV
+ _type_layout_string 18EcosystemAnalytics18SymbolicationOwnerO
- ___swift_closure_destructor.34Tm
- ___swift_closure_destructor.54Tm
- ___swift_closure_destructor.99Tm
- ___swift_memcpy28_4
- _symbolic SPy_____G So11mach_headerV
- _symbolic _____ So11mach_headerV
- _symbolic _____ s6UInt32V
- _type_layout_string So11mach_headerV
CStrings:
+ "/System"
+ "/usr"
+ "00000000-0000-0000-0000-000000000000"
+ "EcosystemAnalytics.framework:MachOAnalysisPerformer: Interrupted while building events after %d symbols, stopping"
+ "EcosystemAnalytics.framework:MicrostackshotsParser: Capping historical PIDs from %d to %d"
+ "EcosystemAnalytics.framework:MicrostackshotsParser: Interrupted before collecting 3rd-party PIDs; skipping full-MSS fetch"
+ "EcosystemAnalytics.framework:MicrostackshotsParser: Interrupted before historical microstackshot analysis; skipping"
+ "EcosystemAnalytics.framework:MicrostackshotsParser: Interrupted while collecting 3rd-party PIDs"
+ "EcosystemAnalytics.framework:MicrostackshotsParser: Interrupted, stopping historical microstackshot analysis"
+ "EcosystemAnalytics.framework:ObjCExceptionTrap: caught Objective-C exception: %{public}@ reason: %{private}@"
+ "MachOAnalysisPerformer: Interrupted while building events"
+ "NMExceptionTrapExceptionName"
+ "ObjCException(name: "
+ "com.apple.ecosystemanalytics.NMExceptionTrap"
+ "owning binary UUID is nil/empty"
+ "owning binary UUID is the all-zero sentinel"
+ "owning binary path is nil/empty"
+ "skipping frame: "
- "ownerLibraryStr or uuid are nil"
```
