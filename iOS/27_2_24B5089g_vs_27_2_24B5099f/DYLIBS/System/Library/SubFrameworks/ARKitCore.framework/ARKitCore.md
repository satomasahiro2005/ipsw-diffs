## ARKitCore

> `/System/Library/SubFrameworks/ARKitCore.framework/ARKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x10` | `0x1c70` | **`+0x1c60`** |
| `__DATA.__data` | `0x1c90` | `0x40` | **`-0x1c50`** |
| `__AUTH.__objc_data` | `0xf0` | `—` | **`-0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x5500` | `0x55f0` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x134bc` | `0x13584` | **`+0xc8`** |
| `__TEXT.__text` | `0x19ae6c` | `0x19aeac` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x3d100` | `0x3d120` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6ad8` | `0x6af8` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x20dd9` | `0x20dbe` | **`-0x1b`** |
| `__AUTH.__data` | `0x10` | `—` | **`-0x10`** |
| `__DATA.__bss` | `0x19a8` | `0x1998` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x203c` | `0x2040` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-781.40.3.0.0
+781.40.6.0.0

-  Symbols:   14603
-  CStrings:  4554
+  Symbols:   14604
+  CStrings:  4553
Symbols:
+ _OBJC_IVAR_$_ARReplaySensorPublic._metadataCacheLock
Functions:
~ -[ARReplaySensorPublic initWithSequenceURL:replayMode:] : 3472 -> 3484
~ -[ARReplaySensorPublic prepareForReplay] : 2744 -> 2832
~ -[ARReplaySensorPublic _endReplay] : 224 -> 136
~ -[ARReplaySensorPublic getWrappedItemsFromStream:upToMovieTime:withBlock:] : 476 -> 528
CStrings:
- "%{public}@ <%p>: endReplay"
```
