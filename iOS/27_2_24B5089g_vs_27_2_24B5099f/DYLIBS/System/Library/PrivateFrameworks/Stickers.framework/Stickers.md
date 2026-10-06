## Stickers

> `/System/Library/PrivateFrameworks/Stickers.framework/Stickers`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x95cd0` | `0x9b050` | **`+0x5380`** |
| `__DATA_DIRTY.__data` | `0x24c0` | `0x2e90` | **`+0x9d0`** |
| `__AUTH.__data` | `0x648` | `—` | **`-0x648`** |
| `__AUTH.__objc_data` | `0x5f8` | `—` | **`-0x5f8`** |
| `__DATA_DIRTY.__objc_data` | `0x11a0` | `0x1798` | **`+0x5f8`** |
| `__DATA.__data` | `0x1240` | `0xf30` | **`-0x310`** |
| `__TEXT.__eh_frame` | `0x4fa0` | `0x5270` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x2159` | `0x2339` | **`+0x1e0`** |
| `__AUTH_CONST.__const` | `0x3258` | `0x3338` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x23e0` | `0x2498` | **`+0xb8`** |
| `__TEXT.__swift5_typeref` | `0x1659` | `0x16e5` | **`+0x8c`** |
| `__DATA.__bss` | `0x4af0` | `0x4a70` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x1100` | `0x1180` | **`+0x80`** |
| `__TEXT.__const` | `0x4838` | `0x48b8` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x13c8` | `0x1418` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x254` | `0x28c` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x8e4` | `0x90c` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x2080` | `0x20a4` | **`+0x24`** |
| `__TEXT.__swift5_fieldmd` | `0x18c4` | `0x18e0` | **`+0x1c`** |
| `__TEXT.__swift5_reflstr` | `0x11af` | `0x11bf` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x11c` | `0x12c` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0xf8` | `0x108` | **`+0x10`** |
| `__DATA.__common` | `0x58` | `0x60` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x828` | `0x830` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1cc` | `0x1d0` | **`+0x4`** |

### Other Changes

```diff

-90.1.2.0.0
+90.1.5.0.0

-  Functions: 2893
-  Symbols:   1147
-  CStrings:  313
+  Functions: 2933
+  Symbols:   1154
+  CStrings:  319
Symbols:
+ _symbolic SDy___________pG8failures_t 10Foundation6LocaleV s5ErrorP
+ _symbolic _____ 8Stickers0A12SearchPolicyO
+ _symbolic _____3key_Say_____G5valuet 10Foundation6LocaleV 8Stickers7StickerC
+ _symbolic _____Sg 10Foundation6LocaleV6RegionV
+ _symbolic _____Sg_ABt 10Foundation6LocaleV6RegionV
+ _symbolic ____________pt 10Foundation6LocaleV s5ErrorP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 14StarmojiSearch13DeleteRequestV
+ _symbolic _____y_____Say_____GG s18_DictionaryStorageC 10Foundation6LocaleV 8Stickers7StickerC
+ _symbolic _____y___________pG s18_DictionaryStorageC 10Foundation6LocaleV s5ErrorP
- _swift_cvw_initEnumMetadataSingleCaseWithLayoutString
- _symbolic ___________t 10Foundation6LocaleV 14StarmojiSearch0cD6EngineC
CStrings:
+ "Could not fetch stickers to remove from the search index: %@"
+ "Could not remove %ld sticker(s) from the %s index: %s"
+ "Could not remove stickers from the search index with underlying error: %@"
+ "Index removal completed for %ld sticker(s) (%fs)"
+ "No search index removal for %ld identifier(s); SearchEngine_V2 enabled: %{bool}d"
+ "Skipping search index removal for %ld identifier(s); their index entries are now orphaned"
+ "Sticker (%{private}s) lacked an associated locale identifier; defaulting to the device locale: %s"
- "Sticker (%s) lacked an associated locale identifier; defaulting to current locale."
```
