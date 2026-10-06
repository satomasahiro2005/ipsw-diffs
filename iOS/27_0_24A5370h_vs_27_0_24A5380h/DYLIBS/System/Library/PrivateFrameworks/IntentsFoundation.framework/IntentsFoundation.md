## IntentsFoundation

> `/System/Library/PrivateFrameworks/IntentsFoundation.framework/IntentsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `—` | `0x230` | **`+0x230`** |
| `__DATA_DIRTY.__objc_data` | `0x320` | `0xf0` | **`-0x230`** |
| `__DATA_CONST.__got` | `0x168` | `0x170` | **`+0x8`** |

### Other Changes

```diff

-4016.0.42.4.0
+4016.0.43.5.0
Functions:
~ -[NSCoder(IntentsFoundation) if_decodeBytesNoCopyForKey:] -> -[_IFValueTransformer initWithForwardTransformation:reverseTransformation:] : 112 -> 180
~ -[_IFValueTransformer initWithForwardTransformation:reverseTransformation:] -> __IFSetTransform : 180 -> 424
~ __IFSetTransform -> -[NSSet(IntentsFoundation) if_compactMap:] : 424 -> 8
~ -[NSSet(IntentsFoundation) if_compactMap:] -> -[NSString(IntentsFoundation) if_stringByUppercasingFirstCharacter] : 8 -> 256
~ -[NSString(IntentsFoundation) if_stringByUppercasingFirstCharacter] -> -[NSCoder(IntentsFoundation) if_decodeBytesNoCopyForKey:] : 256 -> 112
```
