## DriverKit

> `/System/Library/Frameworks/DriverKit.framework/DriverKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37d48` | `0x37d34` | **`-0x14`** |

### Other Changes

```diff

-509.0.3.0.0
+509.2.1.0.0
Functions:
~ __ZN15OSMetaClassBase6InvokeE5IORPC : 1548 -> 1468
~ __ZN15IODispatchQueue15DispatchAsync_fEPvPFvS0_E : 124 -> 192
~ __ZN15IODispatchQueue13DispatchAsyncEU13block_pointerFvvE : 156 -> 80
~ ____ZN15IODispatchQueue15DispatchAsync_fEPvPFvS0_E_block_invoke : 192 -> 236
~ __ZN8OSAction6CancelEU13block_pointerFvvE : 208 -> 232
```
