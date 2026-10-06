## ScreenTimeCore

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfecac` | `0xff1ec` | **`+0x540`** |
| `__AUTH_CONST.__objc_const` | `0x13450` | `0x135b0` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0xa368` | `0xa420` | **`+0xb8`** |
| `__AUTH_CONST.__cfstring` | `0x99e0` | `0x9a60` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0xc2ca` | `0xc32a` | **`+0x60`** |
| `__DATA_DIRTY.__objc_data` | `0x1ef0` | `0x1f40` | **`+0x50`** |
| `__DATA_DIRTY.__data` | `0x268` | `0x2a8` | **`+0x40`** |
| `__TEXT.__cstring` | `0xa8dc` | `0xa91c` | **`+0x40`** |
| `__AUTH.__data` | `0x510` | `0x4e0` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x54c0` | `0x54f0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x40c8` | `0x40f8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1f18` | `0x1f40` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x37a8` | `0x37c8` | **`+0x20`** |
| `__DATA.__data` | `0x2230` | `0x2210` | **`-0x20`** |
| `__DATA.__bss` | `0x3f90` | `0x3fa0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x7d4` | `0x7e0` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x6e8` | `0x6f0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x4c8` | `0x4d0` | **`+0x8`** |

### Other Changes

```diff

-655.1.6.1.0
+655.1.9.1.0

-  Functions: 6029
-  Symbols:   6831
-  CStrings:  2289
+  Functions: 6048
+  Symbols:   6865
+  CStrings:  2294
Symbols:
+ +[STExpressIntroductionUserObjC localUser]
+ +[STExpressIntroductionUserObjC remoteUserWithDSID:]
+ +[STExpressIntroductionUserObjC supportsSecureCoding]
+ -[STExpressIntroductionSettingsDefaultsObjC managementHasStrictPolicy]
+ -[STExpressIntroductionSettingsDefaultsObjC managementIsManaged]
+ -[STExpressIntroductionSettingsDefaultsObjC setManagementHasStrictPolicy:]
+ -[STExpressIntroductionSettingsDefaultsObjC setManagementIsManaged:]
+ -[STExpressIntroductionUserObjC .cxx_destruct]
+ -[STExpressIntroductionUserObjC dsid]
+ -[STExpressIntroductionUserObjC encodeWithCoder:]
+ -[STExpressIntroductionUserObjC initWithCoder:]
+ -[STExpressIntroductionUserObjC initWithDSID:]
+ -[STManagementState saveExpressIntroductionSettingsDefaults:forUser:completionHandler:]
+ GCC_except_table207
+ GCC_except_table210
+ GCC_except_table216
+ _OBJC_CLASS_$_STExpressIntroductionUserObjC
+ _OBJC_IVAR_$_STExpressIntroductionSettingsDefaultsObjC._managementHasStrictPolicy
+ _OBJC_IVAR_$_STExpressIntroductionSettingsDefaultsObjC._managementIsManaged
+ _OBJC_IVAR_$_STExpressIntroductionUserObjC._dsid
+ _OBJC_METACLASS_$_STExpressIntroductionUserObjC
+ _OUTLINED_FUNCTION_11
+ _STChinaSKUHiddenBundleIdentifiers
+ _STChinaSKUHiddenBundleIdentifiers.bundleIdentifiers
+ _STChinaSKUHiddenBundleIdentifiers.onceToken
+ _STIsChinaSKUHiddenBundleIdentifier
+ __OBJC_$_CLASS_METHODS_STExpressIntroductionUserObjC
+ __OBJC_$_CLASS_PROP_LIST_STExpressIntroductionUserObjC
+ __OBJC_$_INSTANCE_METHODS_STExpressIntroductionUserObjC
+ __OBJC_$_INSTANCE_VARIABLES_STExpressIntroductionUserObjC
+ __OBJC_$_PROP_LIST_STExpressIntroductionUserObjC
+ __OBJC_CLASS_PROTOCOLS_$_STExpressIntroductionUserObjC
+ __OBJC_CLASS_RO_$_STExpressIntroductionUserObjC
+ __OBJC_METACLASS_RO_$_STExpressIntroductionUserObjC
+ ___87-[STManagementState saveExpressIntroductionSettingsDefaults:forUser:completionHandler:]_block_invoke
+ ___STChinaSKUHiddenBundleIdentifiers_block_invoke
+ ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
- GCC_except_table205
- GCC_except_table208
- GCC_except_table214
CStrings:
+ "DSID"
+ "ManagementHasStrictPolicy"
+ "ManagementIsManaged"
+ "Saving Express Introduction settings defaults for a remote user is not supported yet"
+ "com.apple.campo"
```
