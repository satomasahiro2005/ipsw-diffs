## AppleHIDALS

> `/System/Library/Extensions/AppleHIDALSService.kext/PlugIns/AppleHIDALS.plugin/AppleHIDALS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcf00` | `0xcedc` | **`-0x24`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2285.0.0.502.1
+2300.0.0.502.1
Functions:
~ __ZN11AppleUSBALS12copyPropertyEPK10__CFString : 5656 -> 5648
~ __ZN11AppleUSBALS11setPropertyEPK10__CFStringPKv : 11704 -> 11676
```
