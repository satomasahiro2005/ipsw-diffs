## WirelessRadioManagerd

> `/usr/sbin/WirelessRadioManagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17171c` | `0x17172c` | **`+0x10`** |
| `__TEXT.__cstring` | `0x5a21d` | `0x5a227` | **`+0xa`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1939.2.0.0.0
+1939.3.0.0.0
Functions:
~ sub_100057384 : 2620 -> 2636
CStrings:
+ "evaluateGenericCellularScore RRC connected with dLQM:%d, vLQM:%d, sLQM:%d, stall:%d, isMav:%d, criticalFailure:%d"
- "evaluateGenericCellularScore RRC connected with dLQM:%d, vLQM:%d, sLQM:%d, stall:%d, criticalFailure:%d"
```
