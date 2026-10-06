## com.apple.tailspin

> `/System/Library/UserEventPlugins/com.apple.tailspin.plugin/com.apple.tailspin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xfe` | `0x11c` | **`+0x1e`** |
| `__TEXT.__text` | `0x620` | `0x628` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__objc_selrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-264.0.0.0.0
+267.0.0.0.0
Functions:
~ _init_tailspin : 1160 -> 1168
CStrings:
+ "%{public}s reset on-disk tailspin configuration. Apple-Internal: %{bool}d, Is Photos: %{bool}d, Is tailspind 300MB: %{bool}d"
- "%{public}s reset on-disk tailspin configuration. Apple-Internal: %{bool}d, Is Photos: %{bool}d"
```
