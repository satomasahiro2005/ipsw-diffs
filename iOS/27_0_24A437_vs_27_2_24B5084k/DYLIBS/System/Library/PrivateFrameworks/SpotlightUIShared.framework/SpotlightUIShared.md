## SpotlightUIShared

> `/System/Library/PrivateFrameworks/SpotlightUIShared.framework/SpotlightUIShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe1d08` | `0xe2be8` | **`+0xee0`** |
| `__TEXT.__const` | `0xa25c` | `0xa39c` | **`+0x140`** |
| `__AUTH_CONST.__const` | `0x6e31` | `0x6ee1` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x7a0` | `0x820` | **`+0x80`** |
| `__TEXT.__cstring` | `0x3408` | `0x3458` | **`+0x50`** |
| `__DATA.__bss` | `0xe7b0` | `0xe7f0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x658` | `0x690` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x21a4` | `0x21d8` | **`+0x34`** |
| `__AUTH_CONST.__objc_const` | `0x3ac8` | `0x3a98` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x1352` | `0x1382` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1ca8` | `0x1cd8` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x3446` | `0x3476` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x718` | `0x738` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x37fc` | `0x3818` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x1608` | `0x1620` | **`+0x18`** |
| `__DATA.__common` | `0x1a0` | `0x190` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x41c8` | `0x41d8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1d30` | `0x1d38` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x8c9c` | `0x8ca4` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xf08` | `0xf00` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x32c` | `0x334` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x84` | `0x80` | **`-0x4`** |

### Other Changes

```diff

-236.0.21.105.0
+250.1.2.0.0

-  Functions: 5206
-  Symbols:   2268
-  CStrings:  432
+  Functions: 5227
+  Symbols:   2278
+  CStrings:  436
Symbols:
+ +[SUIUtilities isSearchFieldAutocorrectAlwaysEnabled]
+ _SUISCorespotlightLog
+ _SUISCorespotlightLog.log
+ _SUISCorespotlightLog.once
+ ___SUISCorespotlightLog_block_invoke
+ ___block_descriptor_40_e8_32s_e17_v16?0"NSError"8ls32l8
+ ___swift_memcpy225_8
+ ___swift_memcpy96_8
+ _get_enum_tag_for_layout_string 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextVIeghn_Sg
+ _swift_getDynamicType
+ _symbolic _____ 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextV
+ _symbolic _____Ieghn_ 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextV
+ _symbolic _____ytIeghnr_ 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextV
+ _symbolic y_____YbScMYccSg 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextV
+ _type_layout_string 17SpotlightUIShared21WindowSizingAnimationV04AxisE0V7ContextV
- -[SUISPasteboardManager foundItems]
- -[SUISPasteboardManager setFoundItems:]
- _OBJC_IVAR_$_SUISPasteboardManager._foundItems
- ___swift_memcpy193_8
- ___swift_memcpy64_8
CStrings:
+ "QueryController: Starting query(%llu): %{sensitive}s browseMode: %s queryType: %s tokens: %s context: %s"
+ "SUISearchFieldAutocorrectAlwaysEnabled"
+ "com.apple.spotlight.clear.pasteboard.history"
+ "com.apple.spotlight.delete.pasteboard.expired"
+ "delete command had nothing to delete reason:%@"
+ "deleting domains (%lu) reason:%@ domains:%@"
+ "deleting files (%lu) reason:%@"
+ "deleting items (%lu) reason:%@ hashes:%@"
+ "failed to delete domains with error: %@"
+ "failed to delete files with error: %@"
+ "failed to delete items with error: %@"
+ "finished deleting domains reason:%@"
+ "finished deleting items by hash reason:%@"
+ "unspecified"
- "Deleting expired files (%lu)"
- "QueryController: Starting query(%llu): %{sensitive}s context: %s"
- "deleting expired pasteboard items (%lu) hashes:%@"
- "deleting pasteboard domains (%lu): %@"
- "failed to delete expired domains with error: %@"
- "failed to delete expired files with error: %@"
- "failed to delete expired items with error: %@"
- "finished deleting expired pasteboard items by hash"
- "finished deleting pasteboard domains"
- "title for suggestion section in files and apps browse"
```
