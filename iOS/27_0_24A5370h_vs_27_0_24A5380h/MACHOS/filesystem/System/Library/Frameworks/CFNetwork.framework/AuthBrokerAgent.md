## AuthBrokerAgent

> `/System/Library/Frameworks/CFNetwork.framework/AuthBrokerAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x4ad` | `0x4f5` | **`+0x48`** |
| `__TEXT.__text` | `0x339c` | `0x33e4` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x234` | `0x238` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3888.100.1.0.0
+3890.100.1.0.0

-  CStrings:  119
+  CStrings:  120
Functions:
~ sub_1000023f8 : 2408 -> 2480
CStrings:
+ "Could not present prompt to user, will retry on next request %{public}@"
```
