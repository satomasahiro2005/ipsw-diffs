## PriMLETL

> `/System/Library/PrivateFrameworks/PriMLETL.framework/PriMLETL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb8194` | `0xb9740` | **`+0x15ac`** |
| `__TEXT.__eh_frame` | `0x60d0` | `0x61d0` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x4cc0` | `0x4d60` | **`+0xa0`** |
| `__AUTH_CONST.__auth_got` | `0x14d0` | `0x1558` | **`+0x88`** |
| `__TEXT.__oslogstring` | `0x1d37` | `0x1da7` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x2ea9` | `0x2f09` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x2710` | `0x2770` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x1b25` | `0x1b83` | **`+0x5e`** |
| `__AUTH_CONST.__objc_const` | `0xbe8` | `0xc28` | **`+0x40`** |
| `__TEXT.__const` | `0x8f18` | `0x8f58` | **`+0x40`** |
| `__DATA.__data` | `0x1828` | `0x1860` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x2950` | `0x2974` | **`+0x24`** |
| `__TEXT.__swift5_capture` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__AUTH.__data` | `0x1038` | `0x1048` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1538` | `0x1548` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x3f8` | `0x408` | **`+0x10`** |
| `__DATA.__common` | `0xd0` | `0xd8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1a8` | `0x1a0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x488` | `0x490` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x14cc` | `0x14d4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x198` | `0x19c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x1f8` | `0x1fc` | **`+0x4`** |

### Other Changes

```diff

-42.0.0.0.0
+44.0.0.0.0

-  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Functions: 2972
-  Symbols:   1058
-  CStrings:  309
+  Functions: 2996
+  Symbols:   1064
+  CStrings:  311
Symbols:
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _swift_retain_x1
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
+ _symbolic ScCySay_____G______pG 8PriMLETL21LocaleAwareDataRecordC s5ErrorP
+ _symbolic So10NSProgressCSg
+ _symbolic So20CSSearchQueryContextC
+ _symbolic _____ySSSg_____G 9PriMLCore12SingleResumeC s5NeverO
+ _symbolic _____ySay_____G______pG 9PriMLCore12SingleResumeC 0A5MLETL21LocaleAwareDataRecordC s5ErrorP
- __swift_FORCE_LOAD_$_swiftAppleArchive
- __swift_FORCE_LOAD_$_swiftAppleArchive_$_PriMLETL
- _symbolic ScCyyt______pG s5ErrorP
- _symbolic Siz_Xx
CStrings:
+ "EMMessage.requestRepresentation timed out after %fs, cancelled"
+ "Spotlight query timed out after %fs: %s"
+ "runSpotlightQuery(queryString:context:)"
- "fetchDataRecords(since:)"
```
