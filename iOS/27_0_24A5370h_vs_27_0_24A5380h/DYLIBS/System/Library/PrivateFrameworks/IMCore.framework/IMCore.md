## IMCore

> `/System/Library/PrivateFrameworks/IMCore.framework/IMCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fe320` | `0x2fe854` | **`+0x534`** |
| `__AUTH.__objc_data` | `0x4318` | `0x4020` | **`-0x2f8`** |
| `__DATA_DIRTY.__objc_data` | `0x1b40` | `0x1e38` | **`+0x2f8`** |
| `__DATA_DIRTY.__data` | `0x268` | `0x3f8` | **`+0x190`** |
| `__AUTH.__data` | `0x2e40` | `0x2d20` | **`-0x120`** |
| `__AUTH_CONST.__objc_const` | `0x22128` | `0x22198` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x72f8` | `0x72b0` | **`-0x48`** |
| `__TEXT.__objc_methlist` | `0x18cd4` | `0x18d1c` | **`+0x48`** |
| `__DATA.__data` | `0x6520` | `0x64f8` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0xba60` | `0xba80` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xea70` | `0xea90` | **`+0x20`** |
| `__TEXT.__const` | `0x116e0` | `0x116f0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x13505` | `0x13515` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x240fb` | `0x240eb` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x2878` | `0x2880` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x340` | `0x348` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x12080` | `0x12088` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc470` | `0xc478` | **`+0x8`** |

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 15202
-  Symbols:   2690
+  Functions: 15208
+  Symbols:   2691
Symbols:
+ _IMCloudKitAttachmentDownloadHistoryFinished
CStrings:
+ "payloadAttachmentCountChanged=%{BOOL}d needsPayloadAttachmentUpdate=%{BOOL}d for messageGUID=%@ bundleID=%@"
+ "sp:"
- "No context available for this chat, display links by default."
- "payloadAttachmentCountChanged %@ needsPayloadAttachmentUpdate %@"
```
