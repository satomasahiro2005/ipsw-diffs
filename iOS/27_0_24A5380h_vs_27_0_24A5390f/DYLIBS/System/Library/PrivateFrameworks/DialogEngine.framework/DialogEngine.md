## DialogEngine

> `/System/Library/PrivateFrameworks/DialogEngine.framework/DialogEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1900` | `0x18b0` | **`-0x50`** |
| `__DATA.__bss` | `0x2de8` | `0x2d98` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__DATA.__data` | `0x52c` | `0x4ec` | **`-0x40`** |
| `__DATA_DIRTY.__data` | `0x1800` | `0x1840` | **`+0x40`** |
| `__DATA_DIRTY.__bss` | `0x268` | `0x288` | **`+0x20`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3600.23.4.0.0
+3600.23.6.0.0
Functions:
~ __ZN4siri12dialogengine18GetFallbackLocalesERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE : 3936 -> 3940
~ __ZN6google8protobuf2io18StringOutputStreamD0Ev : 28 -> 24
CStrings:
+ "3600.23.6"
+ "CAT Request (Dialog Engine 3600.23.6)"
- "3600.23.4"
- "CAT Request (Dialog Engine 3600.23.4)"
```
