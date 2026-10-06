## CalendarFoundation

> `/System/Library/PrivateFrameworks/CalendarFoundation.framework/CalendarFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62a84` | `0x64ff0` | **`+0x256c`** |
| `__DATA.__bss` | `0x720` | `0xc40` | **`+0x520`** |
| `__AUTH.__objc_data` | `0x12c8` | `0xdf0` | **`-0x4d8`** |
| `__DATA_DIRTY.__objc_data` | `0xf00` | `0x13d8` | **`+0x4d8`** |
| `__TEXT.__const` | `0x594` | `0x8f4` | **`+0x360`** |
| `__AUTH_CONST.__const` | `0x1058` | `0x11a8` | **`+0x150`** |
| `__TEXT.__swift5_typeref` | `0x1f8` | `0x2cc` | **`+0xd4`** |
| `__TEXT.__oslogstring` | `0x38d5` | `0x39a5` | **`+0xd0`** |
| `__TEXT.__constg_swiftt` | `0x104` | `0x1b8` | **`+0xb4`** |
| `__TEXT.__unwind_info` | `0x1c28` | `0x1cc0` | **`+0x98`** |
| `__AUTH_CONST.__auth_got` | `0xc28` | `0xcb8` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0xf8` | `0x170` | **`+0x78`** |
| `__AUTH.__data` | `0x118` | `0x178` | **`+0x60`** |
| `__DATA.__data` | `0xb48` | `0xb98` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0xf7` | `0x140` | **`+0x49`** |
| `__AUTH_CONST.__cfstring` | `0x9540` | `0x9580` | **`+0x40`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x50` | **`+0x3c`** |
| `__DATA_DIRTY.__data` | `0x80` | `0xb0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x65d2` | `0x6602` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `—` | `0x30` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x41b0` | `0x41d8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x5d8c` | `0x5db4` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0xc` | `0x34` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x8f0` | `0x910` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x14` | `0x2c` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x278` | `0x288` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1788` | `0x1790` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x188` | `0x180` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xafc` | `0xaf8` | **`-0x4`** |

### Other Changes

```diff

-1636.1.2.0.0
+1636.2.2.0.0

-  Functions: 2680
-  Symbols:   4444
-  CStrings:  1561
+  Functions: 2753
+  Symbols:   4480
+  CStrings:  1567
Symbols:
+ +[CalPersonaUtils _isPersonalPersonaAvailable]
+ +[CalPersonaUtils _personaUtilErrorForUserManagementError:]
+ +[CalPersonaUtils _personaUtilErrorWithCode:underlyingError:]
+ +[CalPersonaUtils performBlockAsPersonaWithIdentifier:block:error:]
+ +[CalUMCalendarDataContainerInfo containerInfoWithAccount:error:]
+ +[CalUMCalendarDataContainerInfo containerInfoWithPersonaID:error:]
+ -[CalMockCalendarDataContainerProvider containerForAccountIdentifier:error:]
+ -[CalMockCalendarDataContainerProvider containerInfoForAccount:error:]
+ -[CalMockCalendarDataContainerProvider containerInfoForAccountIdentifier:error:]
+ -[CalMockCalendarDataContainerProvider containerInfoForPersonaIdentifier:error:]
+ -[CalMockCalendarDataContainerProvider personaForAccountIdentifier:error:]
+ -[CalUMCalendarDataContainerProvider containerForAccountIdentifier:error:]
+ -[CalUMCalendarDataContainerProvider containerInfoForAccount:error:]
+ -[CalUMCalendarDataContainerProvider containerInfoForAccountIdentifier:error:]
+ -[CalUMCalendarDataContainerProvider containerInfoForPersonaIdentifier:error:]
+ _CalPersonaUtilsErrorDomain
+ _NSPOSIXErrorDomain
+ _NSUnderlyingErrorKey
+ ___67+[CalUMCalendarDataContainerInfo containerInfoWithPersonaID:error:]_block_invoke
+ ___swift_memcpy17_8
+ ___swift_memcpy8_8
+ _associated conformance 18CalendarFoundation19CachedDateFormatterV11FormatStyleOSHAASQ
+ _associated conformance 18CalendarFoundation19CachedDateFormatterV3Key33_9D03EE37A6E1641E4F2D3701453009D0LLVSHAASQ
+ _associated conformance So19NSFormattingContextVSHSCSQ
+ _associated conformance So20NSDateFormatterStyleVSHSCSQ
+ _get_enum_tag_for_layout_string 18CalendarFoundation19CachedDateFormatterV11FormatStyleO
+ _swift_cvw_enumFn_getEnumTag
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getSingletonMetadata
+ _swift_storeEnumTagSinglePayloadGeneric
+ _symbolic $sSY
+ _symbolic SS
+ _symbolic Si
+ _symbolic So15NSDateFormatterC
+ _symbolic Su
+ _symbolic _____ 10Foundation8CalendarV
+ _symbolic _____ 18CalendarFoundation19CachedDateFormatterV
+ _symbolic _____ 18CalendarFoundation19CachedDateFormatterV11FormatStyleO
+ _symbolic _____ 18CalendarFoundation19CachedDateFormatterV3Key33_9D03EE37A6E1641E4F2D3701453009D0LLV
+ _symbolic _____ So19NSFormattingContextV
+ _symbolic _____ So20NSDateFormatterStyleV
+ _symbolic _____4date_AA4timet So20NSDateFormatterStyleV
+ _symbolic _____Sg 10Foundation6LocaleV
+ _symbolic _____ySDy_____So15NSDateFormatterCG_____G s13ManagedBufferCsRi__rlE 18CalendarFoundation19CachedDateFormatterV3Key33_9D03EE37A6E1641E4F2D3701453009D0LLV So16os_unfair_lock_sV
+ _symbolic _____y_____So15NSDateFormatterCG s18_DictionaryStorageC 18CalendarFoundation19CachedDateFormatterV3Key33_9D03EE37A6E1641E4F2D3701453009D0LLV
+ _type_layout_string 18CalendarFoundation19CachedDateFormatterV
+ _type_layout_string 18CalendarFoundation19CachedDateFormatterV11FormatStyleO
- +[CalPersonaUtils performBlockAsPersonaWithIdentifier:block:]
- -[CalMockCalendarDataContainerProvider containerForAccountIdentifier:]
- -[CalMockCalendarDataContainerProvider containerInfoForAccount:]
- -[CalMockCalendarDataContainerProvider containerInfoForAccountIdentifier:]
- -[CalMockCalendarDataContainerProvider containerInfoForPersonaIdentifier:]
- -[CalMockCalendarDataContainerProvider personaForAccountIdentifier:]
- -[CalUMCalendarDataContainerInfo initWithAccount:]
- -[CalUMCalendarDataContainerInfo initWithPersonaID:]
- -[CalUMCalendarDataContainerProvider containerForAccountIdentifier:]
- -[CalUMCalendarDataContainerProvider containerInfoForAccount:]
- -[CalUMCalendarDataContainerProvider containerInfoForAccountIdentifier:]
- -[CalUMCalendarDataContainerProvider containerInfoForPersonaIdentifier:]
- ___52-[CalUMCalendarDataContainerInfo initWithPersonaID:]_block_invoke
CStrings:
+ "CalPersonaUtilsErrorDomain"
+ "Error listing all persona attributes: %@"
+ "Personal persona is available. Assuming the requested persona was actually deleted."
+ "Personal persona is not available."
+ "Unexpected error from UserManagement: %@"
+ "value.stringValue"
```
