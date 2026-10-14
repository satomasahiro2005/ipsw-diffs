## TextComposer

> `/System/Library/PrivateFrameworks/TextComposer.framework/TextComposer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d0fbc` | `0x1d10a0` | **`+0xe4`** |
| `__TEXT.__oslogstring` | `0xab22` | `0xab62` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1d0c` | `0x1d30` | **`+0x24`** |

### Other Changes

```diff

-211.36.0.0.0
+211.37.1.0.0

-  CStrings:  2627
+  CStrings:  2628
Functions:
~ sub_1c17dcba4 -> sub_1c1b68ba4 : 1996 -> 2208
~ sub_1c18a5bfc -> sub_1c1c31cd0 : 160 -> 176
~ sub_1c18b5f68 -> sub_1c1c4204c : 12 -> 24
~ sub_1c18b5f74 -> sub_1c1c42064 : 24 -> 12
~ sub_1c18b62fc -> sub_1c1c423e0 : 12 -> 20
~ sub_1c18b6314 -> sub_1c1c42400 : 20 -> 12
CStrings:
+ "Skipping smart replies - conversation is in onCompose state"
```
