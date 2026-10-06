## AccessibilityUIUtilities

> `/System/Library/PrivateFrameworks/AccessibilityUIUtilities.framework/AccessibilityUIUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x618d4` | `0x61f48` | **`+0x674`** |
| `__AUTH_CONST.__objc_const` | `0xa218` | `0xa2a8` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x64cc` | `0x655c` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x5160` | `0x51c8` | **`+0x68`** |
| `__TEXT.__dlopen_cstrs` | `0x3ec` | `0x450` | **`+0x64`** |
| `__AUTH_CONST.__cfstring` | `0x6a20` | `0x6a60` | **`+0x40`** |
| `__TEXT.__cstring` | `0x5cbc` | `0x5cf1` | **`+0x35`** |
| `__TEXT.__gcc_except_tab` | `0x810` | `0x838` | **`+0x28`** |
| `__DATA_CONST.__const` | `0xdd0` | `0xde8` | **`+0x18`** |
| `__DATA.__bss` | `0xa50` | `0xa60` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x58c` | `0x598` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x11f0` | `0x11f8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1198` | `0x11a0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1978` | `0x1980` | **`+0x8`** |

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Functions: 2401
-  Symbols:   4645
-  CStrings:  1073
+  Functions: 2415
+  Symbols:   4665
+  CStrings:  1077
Symbols:
+ -[AXUIPasscodeViewController _acquireSecureIndicatorElevation]
+ -[AXUIPasscodeViewController _acquireSystemApertureInertRestriction]
+ -[AXUIPasscodeViewController _relinquishSecureIndicatorElevation]
+ -[AXUIPasscodeViewController _relinquishSystemApertureInertRestriction]
+ -[AXUIPasscodeViewController dealloc]
+ -[AXUIPasscodeViewController secureIndicatorElevationAssertion]
+ -[AXUIPasscodeViewController setSecureIndicatorElevationAssertion:]
+ -[AXUIPasscodeViewController setSystemApertureInertAssertion:]
+ -[AXUIPasscodeViewController setSystemApertureRestrictionService:]
+ -[AXUIPasscodeViewController systemApertureInertAssertion]
+ -[AXUIPasscodeViewController systemApertureRestrictionService]
+ -[AXUIReachabilityHelper dampingRatioForPayload:]
+ -[AXUIReachabilityHelper responseForPayload:]
+ GCC_except_table1157
+ GCC_except_table1158
+ GCC_except_table1159
+ GCC_except_table1201
+ GCC_except_table1257
+ GCC_except_table1407
+ GCC_except_table1521
+ GCC_except_table1632
+ GCC_except_table1839
+ GCC_except_table1840
+ GCC_except_table1841
+ GCC_except_table1864
+ GCC_except_table1872
+ GCC_except_table1885
+ GCC_except_table1888
+ GCC_except_table1895
+ GCC_except_table1920
+ GCC_except_table629
+ GCC_except_table674
+ GCC_except_table679
+ GCC_except_table690
+ GCC_except_table712
+ GCC_except_table752
+ GCC_except_table753
+ GCC_except_table754
+ GCC_except_table764
+ GCC_except_table784
+ GCC_except_table786
+ GCC_except_table791
+ GCC_except_table977
+ _AXDeviceShouldShowEnhancedSiri
+ _OBJC_CLASS_$_AXSecureIndicatorElevationAssertion
+ _OBJC_IVAR_$_AXUIPasscodeViewController._secureIndicatorElevationAssertion
+ _OBJC_IVAR_$_AXUIPasscodeViewController._systemApertureInertAssertion
+ _OBJC_IVAR_$_AXUIPasscodeViewController._systemApertureRestrictionService
+ ___getSBSSystemApertureRestrictionServiceClass_block_invoke
+ _getSBSSystemApertureRestrictionServiceClass.softClass
- -[AXUIDaemonApplication _frontMostAppOrientation]
- GCC_except_table1145
- GCC_except_table1146
- GCC_except_table1147
- GCC_except_table1189
- GCC_except_table1245
- GCC_except_table1395
- GCC_except_table1509
- GCC_except_table1620
- GCC_except_table1825
- GCC_except_table1826
- GCC_except_table1827
- GCC_except_table1850
- GCC_except_table1858
- GCC_except_table1871
- GCC_except_table1874
- GCC_except_table1881
- GCC_except_table1906
- GCC_except_table661
- GCC_except_table666
- GCC_except_table677
- GCC_except_table699
- GCC_except_table738
- GCC_except_table739
- GCC_except_table740
- GCC_except_table741
- GCC_except_table771
- GCC_except_table773
- GCC_except_table778
- GCC_except_table964
CStrings:
+ "'"
+ "AXPasscode"
+ "SBSSystemApertureRestrictionService"
+ "siri"
+ "siri.gen1"
+ "softlink:o:path:/System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices"
- "$"
- "IconSiri"
```
