## Diagnostic-8079

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8079.appex/Diagnostic-8079`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b58` | `0x8c7c` | **`+0x124`** |
| `__DATA_CONST.__cfstring` | `0xc80` | `0xca0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2400` | `0x2420` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x291f` | `0x2936` | **`+0x17`** |
| `__TEXT.__cstring` | `0x6d6` | `0x6e3` | **`+0xd`** |
| `__DATA.__objc_selrefs` | `0xa38` | `0xa40` | **`+0x8`** |
| `__TEXT.__const` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x228` | `0x220` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0xbf7` | `0xbf8` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 240
+  Functions: 238

-  CStrings:  700
+  CStrings:  703
Symbols:
+ _EXDisplayPipeOpenDisplay
- _EXDisplayPipeOpen
CStrings:
+ "Returning %ld stat sets"
+ "Stats found on index %u."
+ "displayIndex"
+ "numberWithUnsignedInt:"
- "Failed to open ExDisplayPipe client for status!"
```
