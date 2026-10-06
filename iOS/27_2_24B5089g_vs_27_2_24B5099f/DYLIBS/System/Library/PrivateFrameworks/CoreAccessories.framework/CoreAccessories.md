## CoreAccessories

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/CoreAccessories`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x274b0` | `0x27540` | **`+0x90`** |
| `__TEXT.__cstring` | `0x3dbf` | `0x3e08` | **`+0x49`** |
| `__AUTH_CONST.__cfstring` | `0x3c00` | `0x3c40` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x2370` | `0x23a0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2058` | `0x2078` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x19cc` | `0x19e4` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xf60` | `0xf70` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xdc` | `0xe0` | **`+0x4`** |

### Other Changes

```diff

-1219.40.7.0.0
+1219.40.10.502.1

-  Functions: 842
-  Symbols:   1906
-  CStrings:  883
+  Functions: 844
+  Symbols:   1912
+  CStrings:  885
Symbols:
+ -[_ACCExternalAccessoryInfo ppidVersionUID]
+ -[_ACCExternalAccessoryInfo setPpidVersionUID:]
+ GCC_except_table58
+ GCC_except_table97
+ _OBJC_IVAR_$__ACCExternalAccessoryInfo._ppidVersionUID
+ _kACCExternalAccessoryPPIDVersionUIDKey
+ _kACCInfo_PPIDVersionUID
+ _kCFACCExternalAccessoryPPIDVersionUIDKey
+ _kCFACCInfo_PPIDVersionUID
- GCC_except_table38
- GCC_except_table42
- GCC_except_table51
Functions:
~ -[_ACCExternalAccessoryInfo initWithAccessoryInfoDictionary:] : 596 -> 632
~ -[_ACCExternalAccessoryInfo description] : 320 -> 352
~ -[_ACCExternalAccessoryInfo updateAccessoryInfo:] : 712 -> 756
+ -[_ACCExternalAccessoryInfo productID]
+ -[_ACCExternalAccessoryInfo setDestinationSharingOptions:]
~ -[_ACCExternalAccessoryInfo .cxx_destruct] : 212 -> 224
CStrings:
+ "<_ACCExternalAccessoryInfo>[%@ name='%@' manu='%@' model='%@' serial='%@' fw(active)='%@', fw(pending)='%@', hw='%@' ppid='%@' ppidVersionUID='%@']"
+ "ACCExternalAccessoryPPIDVersionUIDKey"
+ "PPIDVersionUID"
- "<_ACCExternalAccessoryInfo>[%@ name='%@' manu='%@' model='%@' serial='%@' fw(active)='%@', fw(pending)='%@', hw='%@' ppid='%@']"
```
