## LimitedModeShieldApp

> `/Applications/LimitedModeShieldApp.app/LimitedModeShieldApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcf40` | `0xdcfc` | **`+0xdbc`** |
| `__DATA_CONST.__const` | `0x258` | `0x390` | **`+0x138`** |
| `__TEXT.__const` | `0x7b4` | `0x8b4` | **`+0x100`** |
| `__TEXT.__constg_swiftt` | `0x370` | `0x44c` | **`+0xdc`** |
| `__DATA.__data` | `0x888` | `0x938` | **`+0xb0`** |
| `__DATA.__objc_data` | `0x430` | `0x4e0` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x61b` | `0x6a7` | **`+0x8c`** |
| `__DATA.__bss` | `0x400` | `0x480` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x790` | `0x7f8` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x330` | `0x388` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0xfe0` | `0x1030` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x1fd6` | `0x2020` | **`+0x4a`** |
| `__DATA.__objc_const` | `0x830` | `0x878` | **`+0x48`** |
| `__TEXT.__objc_methname` | `0x14f7` | `0x1537` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x130` | `0x16c` | **`+0x3c`** |
| `__DATA_CONST.__auth_ptr` | `0x2d0` | `0x300` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x1e4` | `0x214` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xceb` | `0xd1a` | **`+0x2f`** |
| `__DATA_CONST.__auth_got` | `0x7f8` | `0x820` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x131` | `0x159` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x4a0` | `0x4c0` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x48` | `0x60` | **`+0x18`** |
| `__DATA.__common` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x248` | `0x258` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x1c` | `0x28` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1c` | `0x20` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-46.0.7.0.0
+46.0.15.0.0

-  Functions: 234
-  Symbols:   439
-  CStrings:  336
+  Functions: 262
+  Symbols:   449
+  CStrings:  346
Symbols:
+ _$s18AppManagedFeatures18ManagementProviderV4nameSSvg
+ _$s18AppManagedFeatures18ManagementProviderV8longNameSSvg
+ _$s7SwiftUI19UIHostingControllerC5coder8rootViewACyxGSgSo7NSCoderC_xtcfCTq
+ _$s7SwiftUI19UIHostingControllerC5coder8rootViewACyxGSgSo7NSCoderC_xtcfc
+ _$s7SwiftUI19UIHostingControllerC8rootViewACyxGx_tcfCTq
+ _$s7SwiftUI4ViewPAAE19allowsSecureDrawingyQrSbF
+ _$s7SwiftUI4ViewPAAE19allowsSecureDrawingyQrSbFQOMQ
+ _OBJC_METACLASS_$_UIWindow
+ _objc_release_x9
+ _swift_allocateGenericClassMetadata
+ _swift_getGenericMetadata
+ _swift_initClassMetadata2
+ _swift_isaMask
- _$s20AppManagedFeaturesUI23ManagementProviderStoreC04longF4NameSSvg
- _$s20AppManagedFeaturesUI23ManagementProviderStoreC05shortF4NameSSvg
- _objc_release_x25
CStrings:
+ " for assistance."
+ " has restricted access to this app. Contact "
+ "@48@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16"
+ "App is Restricted"
+ "LimitedModeShieldApp/SecureShieldWindow.swift"
+ "_TtC20LimitedModeShieldApp18SecureShieldWindow"
+ "_canShowWhileLocked"
+ "_isSecure"
+ "initWithCoder:"
+ "initWithFrame:"
+ "” is Restricted"
- " has restricted access to this app."
```
