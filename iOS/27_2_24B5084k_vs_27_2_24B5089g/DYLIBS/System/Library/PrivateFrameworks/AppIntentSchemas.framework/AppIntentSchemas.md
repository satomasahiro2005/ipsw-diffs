## AppIntentSchemas

> `/System/Library/PrivateFrameworks/AppIntentSchemas.framework/AppIntentSchemas`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9b5d4` | `0x9df68` | **`+0x2994`** |
| `__DATA_DIRTY.__data` | `0x1ed0` | `0x2528` | **`+0x658`** |
| `__AUTH.__data` | `0x650` | `0x48` | **`-0x608`** |
| `__TEXT.__cstring` | `0x6663` | `0x69e3` | **`+0x380`** |
| `__AUTH_CONST.__const` | `0x8a41` | `0x8d50` | **`+0x30f`** |
| `__TEXT.__const` | `0xe318` | `0xe538` | **`+0x220`** |
| `__DATA.__bss` | `0xd280` | `0xd480` | **`+0x200`** |
| `__DATA_DIRTY.__bss` | `0xbd00` | `0xbf00` | **`+0x200`** |
| `__TEXT.__swift5_fieldmd` | `0x38d0` | `0x39a4` | **`+0xd4`** |
| `__TEXT.__unwind_info` | `0x3380` | `0x3410` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x2477` | `0x24f7` | **`+0x80`** |
| `__TEXT.__swift5_assocty` | `0x6a8` | `0x708` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x2abf` | `0x2b0b` | **`+0x4c`** |
| `__TEXT.__constg_swiftt` | `0x2368` | `0x23a0` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0xd38` | `0xd58` | **`+0x20`** |
| `__DATA.__data` | `0x16d0` | `0x16b8` | **`-0x18`** |
| `__TEXT.__swift5_types` | `0x364` | `0x36c` | **`+0x8`** |

### Other Changes

```diff

-3502.1.9.1.101
+3502.1.10.2.0

-  Functions: 5587
-  Symbols:   1470
-  CStrings:  488
+  Functions: 5688
+  Symbols:   1479
+  CStrings:  510
Symbols:
+ _associated conformance 16AppIntentSchemas6DialogV10DateFormatOSHAASQ
+ _associated conformance 16AppIntentSchemas6DialogV10DateFormatOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 16AppIntentSchemas6DialogV16PersonNameFormatOSHAASQ
+ _associated conformance 16AppIntentSchemas6DialogV16PersonNameFormatOs12CaseIterableAA8AllCasessAFP_Sl
+ _symbolic Say_____G 16AppIntentSchemas6DialogV10DateFormatO
+ _symbolic Say_____G 16AppIntentSchemas6DialogV16PersonNameFormatO
+ _symbolic _____ 16AppIntentSchemas6DialogV10DateFormatO
+ _symbolic _____ 16AppIntentSchemas6DialogV16PersonNameFormatO
+ _symbolic _____Sg_ABt 16AppIntentSchemas5ValueV
CStrings:
+ " modifiers on an entity property require a single-entity parameter, not an array or set. Parameter '"
+ "Collection comparison operators can only be used with array or set properties. Property '"
+ "Date format modifiers can only be used with date-related parameters (Date or DateComponents). Parameter '"
+ "Date format modifiers can only be used with date-related properties (Date or DateComponents). Property '"
+ "Person name format"
+ "Person name format modifiers can only be used with PersonNameComponents parameters. Parameter '"
+ "Person name format modifiers can only be used with PersonNameComponents properties. Property '"
+ "Property-path When branching requires a single-entity parameter, not an array or set. Parameter '"
+ "date"
+ "dateTime"
+ "dayOfWeek"
+ "familyName"
+ "givenName"
+ "long"
+ "medium"
+ "middleName"
+ "namePrefix"
+ "nameSuffix"
+ "nickname"
+ "propertyPath"
+ "short"
+ "time"
```
