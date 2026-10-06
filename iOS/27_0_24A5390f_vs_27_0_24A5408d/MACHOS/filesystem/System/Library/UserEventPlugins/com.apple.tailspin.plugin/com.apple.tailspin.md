## com.apple.tailspin

> `/System/Library/UserEventPlugins/com.apple.tailspin.plugin/com.apple.tailspin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x78` | `0x70` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__cfstring`
- `__DATA.__const`
- `__TEXT.__const`
- `__TEXT.__cstring`

### Other Changes

```diff

-267.0.0.0.0
+268.0.0.0.0
Functions:
~ _init_tailspin -> sub_868 : 1168 -> 68
~ sub_cf8 -> sub_8ac : 68 -> 96
~ sub_d3c -> sub_90c : 96 -> 128
~ sub_d9c -> _init_tailspin : 128 -> 1168
~ sub_e1c : 68 -> 20
~ sub_e60 -> sub_e30 : 20 -> 28
~ sub_e74 -> sub_e4c : 28 -> 68
```
