## HybridSearch

> `/System/Library/PrivateFrameworks/HybridSearch.framework/HybridSearch`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x479e5c` | `0x489850` | **`+0xf9f4`** |
| `__TEXT.__eh_frame` | `0x1abe0` | `0x1c5a4` | **`+0x19c4`** |
| `__TEXT.__const` | `0x50be0` | `0x51870` | **`+0xc90`** |
| `__DATA.__bss` | `0x8b920` | `0x8c520` | **`+0xc00`** |
| `__TEXT.__unwind_info` | `0x14370` | `0x14b48` | **`+0x7d8`** |
| `__AUTH_CONST.__const` | `0x3fab0` | `0x400f0` | **`+0x640`** |
| `__TEXT.__swift5_fieldmd` | `0x1717c` | `0x174ec` | **`+0x370`** |
| `__AUTH.__data` | `0xc3f0` | `0xc708` | **`+0x318`** |
| `__TEXT.__swift_as_cont` | `0xa74` | `0xd64` | **`+0x2f0`** |
| `__TEXT.__constg_swiftt` | `0xc24c` | `0xc530` | **`+0x2e4`** |
| `__TEXT.__swift5_reflstr` | `0x13614` | `0x13864` | **`+0x250`** |
| `__TEXT.__swift_as_entry` | `0x698` | `0x83c` | **`+0x1a4`** |
| `__TEXT.__swift_as_ret` | `0x654` | `0x7f8` | **`+0x1a4`** |
| `__DATA.__data` | `0xfc88` | `0xfdf8` | **`+0x170`** |
| `__TEXT.__cstring` | `0x6e73` | `0x6fb3` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x10db6` | `0x10e76` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x1cb0` | `0x1d48` | **`+0x98`** |
| `__TEXT.__swift5_mpenum` | `0x1c4` | `0x24c` | **`+0x88`** |
| `__TEXT.__swift5_proto` | `0x488c` | `0x48ec` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xf0` | `0x140` | **`+0x50`** |
| `__DATA.__common` | `0x120` | `0x170` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x1c9e` | `0x1c4e` | **`-0x50`** |
| `__TEXT.__swift5_types` | `0x13ac` | `0x13d4` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x474c` | `0x4768` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x320` | `0x334` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x160` | `0x170` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3f4` | `0x404` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x640` | `0x648` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xb0` | `0xb8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x528` | `0x530` | **`+0x8`** |

### Other Changes

```diff

-59.0.1.0.0
+62.1.0.0.0

+  - /System/Library/PrivateFrameworks/CoreEmoji.framework/CoreEmoji

-  Functions: 33714
+  Functions: 34284

-  CStrings:  1108
+  CStrings:  1112
Symbols:
+ _CEMStringIsSingleEmoji
- _swift_retain_x12
CStrings:
+ "' is not registered for HybridSearch"
+ "SearchIngestionClient.generationVersion"
+ "The use case identifier has not been registered with GenerativeSearch. Contact the HybridSearch team to register your use case."
+ "The use case identifier has not been registered with HybridSearch. Contact the HybridSearch team to register your use case."
+ "contentCreationDate"
+ "hasSynchronizedGenerationVersion"
+ "provenanceIdentity"
- "DisableCLIPSafetyBlocking"
- "The use case identifier has not been registered with HybridSearch. Contact the GenerativeSearch team to register your use case."
- "subscribeToVersionChanges() failed to get index version: %{public}@"
```
