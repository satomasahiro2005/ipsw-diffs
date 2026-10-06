## Seeding

> `/System/Library/PrivateFrameworks/Seeding.framework/Seeding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d28c` | `0x1d3b8` | **`+0x12c`** |
| `__TEXT.__oslogstring` | `0x3159` | `0x31e2` | **`+0x89`** |
| `__DATA.__bss` | `0x60` | `0x40` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0xd8` | `0xf8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2a0` | `0x2b0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1160` | `0x1170` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x534` | `0x540` | **`+0xc`** |
| `__TEXT.__const` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-128.0.0.0.0
+129.0.0.0.0

+  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry

-  Functions: 697
-  Symbols:   1145
-  CStrings:  598
+  Functions: 699
+  Symbols:   1147
+  CStrings:  600
Symbols:
+ _NRDevicePropertyProductType
+ _OBJC_CLASS_$_NRPairedDeviceRegistry
CStrings:
+ "Multiple platforms set in bitmap [0x%{public}lx]; cannot reliably determine product type"
+ "No paired watch productType available for watch"
```
