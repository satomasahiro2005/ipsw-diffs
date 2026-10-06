## magicswitchd

> `/usr/libexec/magicswitchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x1f5d` | `0x1f5e` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff
CStrings:
+ "MagicSwitchEnabler --- Launching; \"MagicSwitch-44\" \"1210\""
- "MagicSwitchEnabler --- Launching; \"MagicSwitch-44\" \"675\""
```
