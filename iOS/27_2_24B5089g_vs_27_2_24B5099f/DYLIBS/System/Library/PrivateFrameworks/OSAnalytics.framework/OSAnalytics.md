## OSAnalytics

> `/System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x810` | `0x218` | **`-0x5f8`** |
| `__DATA_DIRTY.__objc_data` | `0x2d0` | `0x8c8` | **`+0x5f8`** |
| `__AUTH.__data` | `0x198` | `—` | **`-0x198`** |
| `__DATA_DIRTY.__data` | `—` | `0x198` | **`+0x198`** |
| `__TEXT.__text` | `0x4b240` | `0x4b2d8` | **`+0x98`** |
| `__TEXT.__eh_frame` | `0x220` | `0x248` | **`+0x28`** |

### Other Changes

```diff

-1056.40.5.0.0
+1056.40.8.0.0
Functions:
~ -[OSALog initWithPath:forRouting:usingConfig:options:error:] : 2856 -> 2972
~ sub_1b2ab7a98 -> sub_1aff91b0c : 32 -> 68
```
