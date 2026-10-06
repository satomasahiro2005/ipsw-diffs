## safarifetcherd

> `/usr/libexec/safarifetcherd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x57ff` | `0x580d` | **`+0xe`** |
| `__TEXT.__text` | `0x94bc` | `0x94c0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.2.5.10.1
+7625.2.7.1.0
Functions:
~ sub_100008110 : 604 -> 608
CStrings:
+ "setUpReaderWebViewIfNeededWithTimeout:completionHandler:"
- "setUpReaderWebViewIfNeededAndPerformBlock:"
```
