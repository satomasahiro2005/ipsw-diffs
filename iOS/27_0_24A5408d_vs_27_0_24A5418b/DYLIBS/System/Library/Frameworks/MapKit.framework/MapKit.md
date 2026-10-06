## MapKit

> `/System/Library/Frameworks/MapKit.framework/MapKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28ff04` | `0x28fef0` | **`-0x14`** |
| `__TEXT.__gcc_except_tab` | `0x61bc` | `0x61c0` | **`+0x4`** |

### Other Changes

```diff

-2552.30.6.12.9
+2552.30.6.12.12
Symbols:
+ +[MKPolygon _polygonWithCoordinates:count:interiorPolygons:vectorOverlayStyle:]
+ GCC_except_table9913
+ GCC_except_table9917
- -[MKPolygon _initWithCoordinates:count:interiorPolygons:vectorOverlayStyle:]
- GCC_except_table9911
- GCC_except_table9916
Functions:
~ -[MKPolygon _initWithCoordinates:count:interiorPolygons:vectorOverlayStyle:] -> +[MKPolygon _polygonWithCoordinates:count:interiorPolygons:vectorOverlayStyle:] : 256 -> 244
~ +[MKPolygon polygonWithCoordinates:count:] : 80 -> 72
```
