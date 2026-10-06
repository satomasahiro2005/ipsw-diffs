## magicswitchd

> `/usr/libexec/magicswitchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x1f5e` | `0x1f5d` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-43.0.0.0.0
+44.0.0.0.0
CStrings:
+ "MagicSwitchEnabler --- Launching; \"MagicSwitch-44\" \"290\""
- "MagicSwitchEnabler --- Launching; \"MagicSwitch-43\" \"3527\""
```
