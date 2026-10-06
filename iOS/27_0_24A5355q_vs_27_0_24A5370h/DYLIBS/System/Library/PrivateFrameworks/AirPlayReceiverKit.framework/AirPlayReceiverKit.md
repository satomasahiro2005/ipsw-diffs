## AirPlayReceiverKit

> `/System/Library/PrivateFrameworks/AirPlayReceiverKit.framework/AirPlayReceiverKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__gcc_except_tab` | `0x528` | `0x774` | **`+0x24c`** |
| `__TEXT.__text` | `0x267f0` | `0x26a3c` | **`+0x24c`** |
| `__TEXT.__cstring` | `0x8d67` | `0x8dc0` | **`+0x59`** |
| `__AUTH_CONST.__objc_const` | `0x2298` | `0x22b8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xb18` | `0xb08` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x878` | `0x880` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x298` | `0x29c` | **`+0x4`** |

### Other Changes

```diff

-980.58.1.11.1
+980.63.2.0.0

-  Functions: 956
-  Symbols:   1570
-  CStrings:  857
+  Functions: 947
+  Symbols:   1572
+  CStrings:  859
Symbols:
+ GCC_except_table142
+ GCC_except_table57
+ GCC_except_table61
+ _OBJC_IVAR_$_APRKMediaPlayer._suppressSeekInducedPauseState
+ ___46-[APRKMediaPlayer _setPropertyWithDictionary:]_block_invoke_2
+ ___47-[APRKMediaPlayer _figPlaybackStateStringFrom:]_block_invoke
+ ___47-[APRKMediaPlayer _figPlaybackStateStringFrom:]_block_invoke_2
- GCC_except_table139
- GCC_except_table60
- _OUTLINED_FUNCTION_19
- _OUTLINED_FUNCTION_20
- _OUTLINED_FUNCTION_21
CStrings:
+ "-[APRKMediaPlayer _figPlaybackStateStringFrom:]"
+ "980.63.2"
+ "Resetting _suppressSeekInducedPauseState = NO"
- "980.58.1.11.1"
```
