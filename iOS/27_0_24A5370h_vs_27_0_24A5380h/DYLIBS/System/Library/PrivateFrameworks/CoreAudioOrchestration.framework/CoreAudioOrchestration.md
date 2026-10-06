## CoreAudioOrchestration

> `/System/Library/PrivateFrameworks/CoreAudioOrchestration.framework/CoreAudioOrchestration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7335c` | `0x731f8` | **`-0x164`** |
| `__DATA_DIRTY.__data` | `0x3668` | `0x3748` | **`+0xe0`** |
| `__AUTH.__data` | `0x790` | `0x6b8` | **`-0xd8`** |
| `__AUTH.__objc_data` | `0x2b8` | `0x240` | **`-0x78`** |
| `__DATA_DIRTY.__objc_data` | `0x9e8` | `0xa60` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x263a` | `0x265a` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xf64` | `0xf50` | **`-0x14`** |
| `__DATA_CONST.__got` | `0x2b8` | `0x2a8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xc58` | `0xc50` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2668` | `0x2660` | **`-0x8`** |

### Other Changes

```diff

-92.30.0.0.0
+93.1.0.0.0

-  Functions: 3159
-  Symbols:   2331
+  Functions: 3156
+  Symbols:   2326
Symbols:
- GCC_except_table28
- __ZN17MicActivityClient14setIsRunningIOEb
- __ZN18MicActivityContext14setIsRunningIOEib
- __ZN28MicActivityClientConnections14setIsRunningIOEib
- _swift_willThrowTypedImpl
CStrings:
+ "%25s:%-5d UNSUPPORTED: Disabling mic activity detection - %d"
+ "%25s:%-5d UNSUPPORTED: Enabling mic activity detection - %d"
- "%25s:%-5d Disabling mic activity detection - %d"
- "%25s:%-5d Enabling mic activity detection - %d"
```
