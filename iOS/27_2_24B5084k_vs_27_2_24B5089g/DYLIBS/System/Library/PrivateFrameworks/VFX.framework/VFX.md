## VFX

> `/System/Library/PrivateFrameworks/VFX.framework/VFX`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x81a50` | `0x855d0` | **`+0x3b80`** |
| `__DATA_DIRTY.__bss` | `0x7400` | `0x3890` | **`-0x3b70`** |
| `__DATA_DIRTY.__data` | `0xfec8` | `0xf078` | **`-0xe50`** |
| `__DATA.__data` | `0x15168` | `0x15f28` | **`+0xdc0`** |
| `__DATA.__common` | `0x10c9` | `0x1219` | **`+0x150`** |
| `__DATA_DIRTY.__common` | `0x518` | `0x3c8` | **`-0x150`** |
| `__AUTH.__data` | `0x379a8` | `0x37a20` | **`+0x78`** |
| `__AUTH_CONST.__const` | `0x91d78` | `0x91de0` | **`+0x68`** |
| `__TEXT.__const` | `0x8df78` | `0x8dfa8` | **`+0x30`** |
| `__AUTH.__objc_data` | `0xcc68` | `0xcc40` | **`-0x28`** |
| `__DATA_DIRTY.__objc_data` | `0x3ff8` | `0x4020` | **`+0x28`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-233.40.1.0.0
+233.40.2.0.0
CStrings:
+ "233.40.2"
+ "Welcome to VFX 233.40.2 (Sep 13 2026 21:01:30)"
- "233.40.1"
- "Welcome to VFX 233.40.1 (Sep  4 2026 01:41:19)"
```
