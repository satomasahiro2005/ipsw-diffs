## RequestDispatcherBridges

> `/System/Library/PrivateFrameworks/RequestDispatcherBridges.framework/RequestDispatcherBridges`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x112d48` | `0x112e9c` | **`+0x154`** |
| `__TEXT.__oslogstring` | `0xc7c7` | `0xc877` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x72b8` | `0x72e0` | **`+0x28`** |
| `__DATA.__data` | `0xdf0` | `0xdd0` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x2e50` | `0x2e70` | **`+0x20`** |
| `__DATA.__common` | `0x200` | `0x1f8` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x3b8` | `0x3c0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x28a0` | `0x28a8` | **`+0x8`** |

### Other Changes

```diff

-3605.19.1.0.0
+3605.25.1.0.0

-  CStrings:  847
+  CStrings:  848
Functions:
~ sub_22b5aa20c -> sub_22a83f20c : 13440 -> 13744
~ sub_22b5c8e98 -> sub_22a85dfc8 : 32 -> 68
CStrings:
+ "MUX: selectPostNLUser: Could not find context for unknown user on a prompt continuation. Falling back to the current turn's candidate so NL output is still posted."
```
