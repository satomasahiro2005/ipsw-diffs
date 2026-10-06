## CoreRealityIO

> `/System/Library/PrivateFrameworks/CoreRealityIO.framework/CoreRealityIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c4e78` | `0x2c4f6c` | **`+0xf4`** |
| `__TEXT.__oslogstring` | `0x3e74` | `0x3f37` | **`+0xc3`** |
| `__TEXT.__gcc_except_tab` | `0x360c0` | `0x36128` | **`+0x68`** |
| `__AUTH_CONST.__auth_got` | `0x3498` | `0x34a0` | **`+0x8`** |

### Other Changes

```diff

-235.0.3.0.0
+235.0.4.0.0

-  Symbols:   21052
-  CStrings:  2176
+  Symbols:   21053
+  CStrings:  2179
Symbols:
+ __ZN32pxrInternal__aapl__pxrReserved__14UsdGeomPrimvarC1ERKS0_
Functions:
~ __ZN9realityio41addSkeletonJointBindingsToModelDescriptorEP21REGeomModelDescriptorRKN32pxrInternal__aapl__pxrReserved__17UsdSkelBindingAPIERKNS2_15UsdSkelSkeletonERKNS2_7UsdPrimE : 3824 -> 4068
CStrings:
+ "Out-of-range joint element size in '%s'; skipping skinning data."
+ "Out-of-range joint index in '%s'; skipping skinning data."
+ "Out-of-range joint weight element size in '%s'; skipping skinning data."
```
