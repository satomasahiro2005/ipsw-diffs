## com.apple.accessoryd.matching

> `/System/Library/UserEventPlugins/com.apple.accessoryd.matching.plugin/com.apple.accessoryd.matching`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37c3c` | `0x37c8c` | **`+0x50`** |
| `__DATA.__cfstring` | `0x3960` | `0x39a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x4f5a` | `0x4f8e` | **`+0x34`** |
| `__DATA.__got` | `0x358` | `0x380` | **`+0x28`** |
| `__DATA.__const` | `0x10c0` | `0x10e0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xa50` | `0xa58` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_arraydata`
- `__DATA.__objc_arrayobj`
- `__DATA.__objc_catlist`
- `__DATA.__objc_classlist`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_dictobj`
- `__DATA.__objc_intobj`
- `__DATA.__objc_protolist`
- `__DATA.__objc_protorefs`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Functions: 1495
-  Symbols:   3140
-  CStrings:  2501
+  Functions: 1496
+  Symbols:   3144
+  CStrings:  2503
Symbols:
+ _ACCUserDefaultsKey_EnableManager2ForTransport
+ _ACCUserDefaultsKey_OverrideMPPAuthSupported
+ _CFDictionaryCopyKeys
+ _kCFACCUserDefaultsKey_EnableManager2ForTransport
+ _kCFACCUserDefaultsKey_OverrideMPPAuthSupported
- _CFDictionaryGetKeys
Functions:
~ -[NSData(CKUtilsAdditions) CKHexString] : 416 -> 420
~ _acc_userNotifications_unlockToUseAccessories : 308 -> 324
~ _OUTLINED_FUNCTION_12 : 12 -> 16
~ _OUTLINED_FUNCTION_13 : 16 -> 12
~ _OUTLINED_FUNCTION_16 : 16 -> 20
~ _OUTLINED_FUNCTION_17 : 20 -> 16
+ _OUTLINED_FUNCTION_57
~ _OUTLINED_FUNCTION_59 : 20 -> 12
~ _systemInfo_copyProductType : 72 -> 96
~ _systemInfo_copyProductVersion : 72 -> 96
~ -[accessorydMatchingPlugin initWithModule:] : 2264 -> 2248
~ _LibCall_ACMContextVerifyPolicyAndCopyRequirementEx : 704 -> 716
~ _LibCall_ACMKernDoubleClickNotify : 172 -> 180
~ _LibCall_ACMContextVerifyPolicyEx : 196 -> 192
~ _LibCall_ACMSecContextVerifyPolicyAndCopyRequirementEx : 200 -> 196
~ _LibCall_ACMContextLoadFromImage : 464 -> 460
~ _LibCall_ACMSecSetBuiltinBiometry : 164 -> 172
CStrings:
+ "EnableManager2ForTransport"
+ "OverrideMPPAuthSupported"
```
