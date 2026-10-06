## VirtualGarage

> `/System/Library/PrivateFrameworks/VirtualGarage.framework/VirtualGarage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xf0` | `0x410` | **`+0x320`** |
| `__DATA_DIRTY.__objc_data` | `0x5a0` | `0x280` | **`-0x320`** |
| `__TEXT.__gcc_except_tab` | `0xee0` | `0xe48` | **`-0x98`** |
| `__TEXT.__text` | `0x3a4f4` | `0x3a500` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x410` | `0x418` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xbc8` | `0xbc0` | **`-0x8`** |

### Other Changes

```diff

-2433.30.6.5.1
+2435.30.6.12.2

-  Symbols:   1609
+  Symbols:   1608
Symbols:
+ GCC_except_table500
- GCC_except_table463
- GCC_except_table507
Functions:
~ -[VGVirtualGarage _waitForGarageUpdateIfNecessary:] : 252 -> 260
~ ___43-[VGVirtualGarage initWithGaragePersister:]_block_invoke : 920 -> 924
~ -[VGVirtualGarage _onboardVehicle:] : 1312 -> 1252
~ -[VGVirtualGarage _executeQueuedCompletionHandlersIfNeeded] : 560 -> 620
```
