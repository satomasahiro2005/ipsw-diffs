## UniformTypeIdentifiers

> `/System/Library/Frameworks/UniformTypeIdentifiers.framework/UniformTypeIdentifiers`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc260` | `0xc2d4` | **`+0x74`** |
| `__TEXT.__cstring` | `0x247f` | `0x24cd` | **`+0x4e`** |

### Other Changes

```diff

-  CStrings:  407
+  CStrings:  413
Functions:
~ sub_18ffac754 -> sub_18ff59754 : 184 -> 220
~ +[UTType(Accessory) _typeWithBluetoothProductID:vendorID:] : 1360 -> 1432
~ +[_UTConstantType _validateThisClass] : 1300 -> 1304
~ __ZNSt3__115__inplace_mergeINS_17_ClassicAlgPolicyERZ37+[_UTConstantType _validateThisClass]E3$_0NS_11__wrap_iterIPP9objc_ivarEEEEvT1_S9_S9_OT0_NS_15iterator_traitsIS9_E15difference_typeESE_PNSD_10value_typeEl : 1404 -> 1408
CStrings:
+ "Device1,8240"
+ "Device1,8242"
+ "Device1,8245"
+ "Device1,8246"
+ "Device1,8247"
+ "Device1,8248"
```
