## RealityKit

> `/System/Library/Frameworks/RealityKit.framework/RealityKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7aec4` | `0x7ae08` | **`-0xbc`** |
| `__TEXT.__objc_methlist` | `0x119c` | `0x11ac` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x2f70` | `0x2f78` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xea8` | `0xeb0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1a10` | `0x1a18` | **`+0x8`** |

### Other Changes

```diff

-453.0.4.0.2
+453.0.5.502.1
Symbols:
+ _$s10RealityKit5SceneC7raycast4from2to5query4mask10relativeTo18requireInputTargetSayAA16CollisionCastHitVGs5SIMD3VySfG_ApA0nO9QueryTypeOAA0N5GroupVAA6EntityCSgSbtF
- _$s10RealityKit5SceneC7raycast6origin9direction6length5query4mask10relativeToSayAA16CollisionCastHitVGs5SIMD3VySfG_APSfAA0lM9QueryTypeOAA0L5GroupVAA6EntityCSgtF
Functions:
~ _$s10RealityKit6ARViewC16handleTapAtPoint5pointySo7CGPointV_tF : 1556 -> 1472
~ _$s10RealityKit6ARViewC7hitTest_5query4maskSayAA16CollisionCastHitVGSo7CGPointV_AA0hI9QueryTypeOAA0H5GroupVtF : 156 -> 196
~ _$s10RealityKit6ARViewC7hitTest_18requireInputTarget5query4maskSayAA16CollisionCastHitVGSo7CGPointV_SbAA0kL9QueryTypeOAA0K5GroupVtF : 1752 -> 1852
~ _$s10RealityKit6ARViewC6entity2atAA6EntityCSgSo7CGPointV_tF : 764 -> 676
~ _$s10RealityKit6ARViewC8entities2atSayAA6EntityCGSo7CGPointV_tF : 744 -> 660
~ _$s10RealityKit10RKARSystemC20cachedGestureHitTestyAA013CollisionCastF0VSgSo7CGPointVF : 1264 -> 1192
```
