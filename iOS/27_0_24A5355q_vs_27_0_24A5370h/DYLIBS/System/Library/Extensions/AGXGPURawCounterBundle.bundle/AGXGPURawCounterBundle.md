## AGXGPURawCounterBundle

> `/System/Library/Extensions/AGXGPURawCounterBundle.bundle/AGXGPURawCounterBundle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2df0` | `0x2dbc` | **`-0x34`** |

### Other Changes

```diff

-360.27.0.0.0
+360.27.3.1.0
Symbols:
+ __ZNSt3__16vectorIPKcNS_9allocatorIS2_EEE20__throw_length_errorB9fqn220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqn220106v
- __ZNSt3__16vectorIPKcNS_9allocatorIS2_EEE20__throw_length_errorB9fqn220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqn220100v
Functions:
~ -[AGXGPURawCounterSource initWithSourceGroup:impl:] : 1828 -> 1800
~ -[AGXGPURawCounterSource resetRawDataPostProcessor] : 308 -> 304
~ -[AGXGPURawCounterSourceGroup initWithAcceleratorPort:] : 1584 -> 1580
~ -[AGXGPURawCounterSourceGroup subDivideCounterList:withOptions:] : 3152 -> 3140
~ __ZNSt3__16vectorIPKcNS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_ : 224 -> 220
```
