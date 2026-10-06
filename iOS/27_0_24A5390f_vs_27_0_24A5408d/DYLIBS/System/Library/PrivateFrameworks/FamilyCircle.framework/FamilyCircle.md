## FamilyCircle

> `/System/Library/PrivateFrameworks/FamilyCircle.framework/FamilyCircle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc7fa8` | `0xca2b0` | **`+0x2308`** |
| `__TEXT.__eh_frame` | `0x57a8` | `0x5958` | **`+0x1b0`** |
| `__AUTH_CONST.__const` | `0x6928` | `0x6a78` | **`+0x150`** |
| `__TEXT.__oslogstring` | `0x4e13` | `0x4f13` | **`+0x100`** |
| `__TEXT.__const` | `0x87f8` | `0x88c8` | **`+0xd0`** |
| `__AUTH.__objc_data` | `0x24c8` | `0x2588` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x3c78` | `0x3d28` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0xc9f8` | `0xcaa0` | **`+0xa8`** |
| `__TEXT.__swift5_reflstr` | `0x159d` | `0x161d` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x2498` | `0x2508` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x74c` | `0x7a8` | **`+0x5c`** |
| `__TEXT.__objc_methlist` | `0x413c` | `0x4184` | **`+0x48`** |
| `__DATA.__data` | `0x2610` | `0x2650` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x27f8` | `0x282c` | **`+0x34`** |
| `__TEXT.__swift5_fieldmd` | `0x1e48` | `0x1e7c` | **`+0x34`** |
| `__AUTH.__data` | `0x1b68` | `0x1b90` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x3e0` | `0x404` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x2888` | `0x28a8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5fa4` | `0x5fb4` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x1b4` | `0x1c4` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1ec` | `0x1fc` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x13b8` | `0x13b0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2e0` | `0x2e4` | **`+0x4`** |

### Other Changes

```diff

-285.0.0.0.0
+290.0.0.0.0

-  Functions: 5518
-  Symbols:   4069
-  CStrings:  1318
+  Functions: 5566
+  Symbols:   4084
+  CStrings:  1322
Symbols:
+ -[FAAgeRangeResponse kind]
+ _OBJC_CLASS_$_AKAgeRangeSettingsProvider
+ _OBJC_CLASS_$_FAFetchScreenTimeMigrationFlagRequest
+ _OBJC_METACLASS_$_FAFetchScreenTimeMigrationFlagRequest
+ __DATA_FAFetchScreenTimeMigrationFlagRequest
+ __INSTANCE_METHODS_FAFetchScreenTimeMigrationFlagRequest
+ __IVARS_FAFetchScreenTimeMigrationFlagRequest
+ __METACLASS_DATA_FAFetchScreenTimeMigrationFlagRequest
+ ___swift_closure_destructor.16Tm
+ ___swift_closure_destructor.8Tm
+ _symbolic SbSo7NSErrorCSgIeyByy_
+ _symbolic ScCySb______pG s5ErrorP
+ _symbolic SccySo18AKAgeRangeSettingsC______pG s5ErrorP
+ _symbolic So26AKAgeRangeSettingsProviderC
+ _symbolic _____ 12FamilyCircle37FAFetchScreenTimeMigrationFlagRequestC
CStrings:
+ "Error fetching age range from AuthKit: %s"
+ "FAFetchScreenTimeMigrationFlagRequest: serviceRemoteObject returned nil"
+ "PersonalAttestationController: No primary AuthKit account."
+ "PersonalAttestationController: Unable to fetch birth year."
+ "PersonalAttestationController: Unable to fetch primary account altDSID."
+ "fetchScreenTimeMigrationFlag XPC connection error: %s"
+ "parentsAndGuardiansAgeOutDisabled"
- "PersonalAttestationController: Unable to fetch authkit account."
- "PersonalAttestationController: Unable to primary authkit account."
- "shouldVendVerificationStatus()"
```
