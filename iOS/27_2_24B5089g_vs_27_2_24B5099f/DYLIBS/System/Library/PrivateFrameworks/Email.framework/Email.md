## Email

> `/System/Library/PrivateFrameworks/Email.framework/Email`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `0x158` | `0x28` | **`-0x130`** |
| `__DATA_DIRTY.__data` | `0x250` | `0x380` | **`+0x130`** |
| `__TEXT.__text` | `0xd91bc` | `0xd928c` | **`+0xd0`** |
| `__AUTH_CONST.__objc_const` | `0x16b90` | `0x16c30` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0xce24` | `0xce84` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x250` | `0x200` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x3718` | `0x3768` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x67f3` | `0x67a3` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x1ad70` | `0x1ada0` | **`+0x30`** |
| `__DATA.__data` | `0x28c0` | `0x28e0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x6158` | `0x6178` | **`+0x20`** |
| `__DATA.__bss` | `0x23e0` | `0x23d0` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x45e8` | `0x45d8` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0xac0` | `0xad0` | **`+0x10`** |
| `__TEXT.__cstring` | `0xc369` | `0xc379` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xc44` | `0xc4c` | **`+0x8`** |

### Other Changes

```diff

-3901.200.41.0.0
+3901.200.66.2.1

-  Functions: 5157
-  Symbols:   8927
-  CStrings:  2151
+  Functions: 5161
+  Symbols:   8931
+  CStrings:  2150
Symbols:
+ -[EMOutgoingMessage setSourceAutosaveID:]
+ -[EMOutgoingMessage setSourceDraftObjectID:]
+ -[EMOutgoingMessage sourceAutosaveID]
+ -[EMOutgoingMessage sourceDraftObjectID]
+ _OBJC_IVAR_$_EMOutgoingMessage._sourceAutosaveID
+ _OBJC_IVAR_$_EMOutgoingMessage._sourceDraftObjectID
- _EMUserDefaultForceSpotlightSearchBackend
- _EMUserDefaultShowNoResultsInAYT
CStrings:
+ "EFPropertyKey_sourceAutosaveID"
+ "EFPropertyKey_sourceDraftObjectID"
- "ForceSpotlightSearchBackend"
- "Forcing spotlight search as ForceSpotlightSearchBackend default is enabled."
- "ShowNoResultsInAYT"
```
