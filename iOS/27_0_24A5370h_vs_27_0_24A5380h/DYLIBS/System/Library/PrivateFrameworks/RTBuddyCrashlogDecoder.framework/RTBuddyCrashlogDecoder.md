## RTBuddyCrashlogDecoder

> `/System/Library/PrivateFrameworks/RTBuddyCrashlogDecoder.framework/RTBuddyCrashlogDecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2854` | `0x29d8` | **`+0x184`** |
| `__AUTH_CONST.__cfstring` | `0x600` | `0x620` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x260` | `0x280` | **`+0x20`** |
| `__TEXT.__cstring` | `0x19c2` | `0x19d9` | **`+0x17`** |
| `__DATA.__data` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xf8` | `0x100` | **`+0x8`** |

### Other Changes

```diff

-778.0.2.0.0
+778.0.6.0.0

-  Functions: 49
-  Symbols:   119
-  CStrings:  256
+  Functions: 50
+  Symbols:   121
+  CStrings:  258
Symbols:
+ __ZL27_rtk_symbols_section_decodePK27RTK_scrlg_section_decoder_sP26RTK_scrlg_section_writer_sPKvm
+ _rtkit_symbols_section_decoder
Functions:
~ __ZL37multi_agent_crashlog_find_first_crashP26RTK_scrlg_section_writer_sPKhPmPy : 324 -> 332
+ __ZL27_rtk_symbols_section_decodePK27RTK_scrlg_section_decoder_sP26RTK_scrlg_section_writer_sPKvm
~ __ZL27_rtk_mailbox_section_decodePK27RTK_scrlg_section_decoder_sP26RTK_scrlg_section_writer_sPKvm : 864 -> 872
~ __ZL35_rtk_armv8_registers_section_decodePK27RTK_scrlg_section_decoder_sP26RTK_scrlg_section_writer_sPKvm : 668 -> 672
~ __ZL36_rtk_armv7a_registers_section_decodePK27RTK_scrlg_section_decoder_sP26RTK_scrlg_section_writer_sPKvm : 636 -> 632
CStrings:
+ "Symbols Section"
+ "images"
```
