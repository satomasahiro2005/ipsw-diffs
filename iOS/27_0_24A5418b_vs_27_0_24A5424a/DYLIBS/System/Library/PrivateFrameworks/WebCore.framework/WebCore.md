## WebCore

> `/System/Library/PrivateFrameworks/WebCore.framework/WebCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37581f0` | `0x375840c` | **`+0x21c`** |
| `__TEXT.__cstring` | `0x3359e9` | `0x33594d` | **`-0x9c`** |
| `__TEXT.__gcc_except_tab` | `0x36e1c` | `0x36e34` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x77120` | `0x77118` | **`-0x8`** |

### Other Changes

```diff

-625.1.29.10.25
+625.1.29.10.28

-  Functions: 125572
-  Symbols:   156724
-  CStrings:  33281
+  Functions: 125568
+  Symbols:   156718
+  CStrings:  33280
Symbols:
+ __ZN3WTF9HashTableINS_3RefIN7WebCore4FontENS_12RawPtrTraitsIS3_EENS_21DefaultRefDerefTraitsIS3_EEEES8_NS_17IdentityExtractorENS_11DefaultHashIS8_EENS_10HashTraitsIS8_EESD_NS_10FastMallocEE3addILNS_17ShouldValidateKeyE1EEENS_18HashTableAddResultINS_17HashTableIteratorISF_S8_S8_S9_SB_SD_SD_EEEEOS8_
- __ZN3WTF6VectorIN7WebCore10FloatPointELm64ENS_15CrashOnOverflowELm16ENS_10FastMallocEE15reserveCapacityILNS_13FailureActionE0EEEbm
- __ZN3WTF6VectorIN7WebCore9FloatSizeELm64ENS_15CrashOnOverflowELm16ENS_10FastMallocEE15reserveCapacityILNS_13FailureActionE0EEEbm
- __ZN3WTF6VectorIN7WebCore9FloatSizeELm64ENS_15CrashOnOverflowELm16ENS_10FastMallocEEC2IK6CGSizeLm18446744073709551615EEENSt3__14spanIT_XT0_EEE
- __ZN3WTF6VectorINS_6RefPtrIN7WebCore21ComplexTextController14ComplexTextRunENS_12RawPtrTraitsIS4_EENS_21DefaultRefDerefTraitsIS4_EEEELm16ENS_15CrashOnOverflowELm16ENS_10FastMallocEE15reserveCapacityILNS_13FailureActionE0EEEbm
- __ZN3WTF6VectorIlLm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEE8growImplILNS_13FailureActionE0EEEbm
- __ZN3WTF6VectorItLm64ENS_15CrashOnOverflowELm16ENS_10FastMallocEE8growImplILNS_13FailureActionE0EEEbm
- __ZN7WebCore16FontPlatformData22objectForEqualityCheckEPK8__CTFont
CStrings:
- "bool WTF::Vector<long>::growImpl(size_t) [T = long, inlineCapacity = 0, OverflowHandler = WTF::CrashOnOverflow, minCapacity = 16, Malloc = WTF::FastMalloc]"
```
