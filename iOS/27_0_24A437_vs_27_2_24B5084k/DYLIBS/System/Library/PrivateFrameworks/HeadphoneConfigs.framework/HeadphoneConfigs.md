## HeadphoneConfigs

> `/System/Library/PrivateFrameworks/HeadphoneConfigs.framework/HeadphoneConfigs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xca3e4` | `0xca458` | **`+0x74`** |
| `__TEXT.__cstring` | `0x9723` | `0x9773` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x96c0` | `0x9700` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x36c0` | `0x36c8` | **`+0x8`** |

### Other Changes

```diff

-2700.17.1.1.0
+2701.2.0.0.0

-  CStrings:  2264
+  CStrings:  2266
Functions:
~ -[BTSDeviceLE isApplePencil:] : 144 -> 152
~ -[HPSSpatialProfileManagementController presentProfileEnrollmentController:] : 1152 -> 1208
~ -[HPSSpatialProfileSingeStepEnrollmentController showNonLandscapeLeftAlert] : 548 -> 600
CStrings:
+ "/System/Library/PrivateFrameworks/HeadphoneAssets.framework"
+ "V68-iOS-Localizable"
```
