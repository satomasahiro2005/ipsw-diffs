## PosterBoardUIServices

> `/System/Library/PrivateFrameworks/PosterBoardUIServices.framework/PosterBoardUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87ec8` | `0x889b0` | **`+0xae8`** |
| `__AUTH_CONST.__objc_const` | `0x14a00` | `0x14fe8` | **`+0x5e8`** |
| `__TEXT.__objc_methlist` | `0x6490` | `0x65a0` | **`+0x110`** |
| `__AUTH.__objc_data` | `0x1408` | `0x14a8` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x3000` | `0x3080` | **`+0x80`** |
| `__TEXT.__cstring` | `0x3b49` | `0x3b99` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1250` | `0x1298` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x23a0` | `0x23e8` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x3a68` | `0x3aa0` | **`+0x38`** |
| `__DATA_CONST.__got` | `0xd98` | `0xdc8` | **`+0x30`** |
| `__DATA.__data` | `0x2e00` | `0x2e20` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x9b4b` | `0x9b67` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0x768` | `0x778` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x358` | `0x368` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x228` | `0x238` | **`+0x10`** |
| `__TEXT.__const` | `0x33d8` | `0x33e8` | **`+0x10`** |

### Other Changes

```diff

-341.0.3.0.0
+344.0.101.0.0

-  Functions: 3528
-  Symbols:   5012
-  CStrings:  832
+  Functions: 3549
+  Symbols:   5055
+  CStrings:  836
Symbols:
+ +[PRUISModalEntryPointGalleryAcceptResponse supportsBSXPCSecureCoding]
+ +[PRUISPortalInfo supportsBSXPCSecureCoding]
+ -[PRUISAmbientPosterViewController setSupportsInteractablePressFeedback:]
+ -[PRUISAmbientPosterViewController supportsInteractablePressFeedback]
+ -[PRUISModalEntryPointGalleryAcceptResponse .cxx_destruct]
+ -[PRUISModalEntryPointGalleryAcceptResponse copyWithZone:]
+ -[PRUISModalEntryPointGalleryAcceptResponse encodeWithBSXPCCoder:]
+ -[PRUISModalEntryPointGalleryAcceptResponse initWithBSXPCCoder:]
+ -[PRUISModalEntryPointGalleryAcceptResponse initWithPortalInfo:]
+ -[PRUISModalEntryPointGalleryAcceptResponse portalInfo]
+ -[PRUISPortalInfo copyWithZone:]
+ -[PRUISPortalInfo description]
+ -[PRUISPortalInfo encodeWithBSXPCCoder:]
+ -[PRUISPortalInfo hash]
+ -[PRUISPortalInfo initWithBSXPCCoder:]
+ -[PRUISPortalInfo initWithSourceLayerRenderID:sourceContextID:]
+ -[PRUISPortalInfo isEqual:]
+ -[PRUISPortalInfo sourceContextID]
+ -[PRUISPortalInfo sourceLayerRenderID]
+ GCC_except_table100
+ GCC_except_table110
+ GCC_except_table118
+ GCC_except_table149
+ GCC_except_table150
+ _OBJC_CLASS_$_PRUISModalEntryPointGalleryAcceptResponse
+ _OBJC_CLASS_$_PRUISPortalInfo
+ _OBJC_IVAR_$_PRUISAmbientPosterViewController._supportsInteractablePressFeedback
+ _OBJC_IVAR_$_PRUISModalEntryPointGalleryAcceptResponse._portalInfo
+ _OBJC_IVAR_$_PRUISPortalInfo._sourceContextID
+ _OBJC_IVAR_$_PRUISPortalInfo._sourceLayerRenderID
+ _OBJC_METACLASS_$_PRUISModalEntryPointGalleryAcceptResponse
+ _OBJC_METACLASS_$_PRUISPortalInfo
+ __OBJC_$_CLASS_METHODS_PRUISModalEntryPointGalleryAcceptResponse
+ __OBJC_$_CLASS_METHODS_PRUISPortalInfo
+ __OBJC_$_INSTANCE_METHODS_PRUISModalEntryPointGalleryAcceptResponse
+ __OBJC_$_INSTANCE_METHODS_PRUISPortalInfo
+ __OBJC_$_INSTANCE_VARIABLES_PRUISModalEntryPointGalleryAcceptResponse
+ __OBJC_$_INSTANCE_VARIABLES_PRUISPortalInfo
+ __OBJC_$_PROP_LIST_PRUISModalEntryPointGalleryAcceptResponse
+ __OBJC_$_PROP_LIST_PRUISPortalInfo
+ __OBJC_CLASS_PROTOCOLS_$_PRUISPortalInfo
+ __OBJC_CLASS_RO_$_PRUISModalEntryPointGalleryAcceptResponse
+ __OBJC_CLASS_RO_$_PRUISPortalInfo
+ __OBJC_METACLASS_RO_$_PRUISModalEntryPointGalleryAcceptResponse
+ __OBJC_METACLASS_RO_$_PRUISPortalInfo
+ __swiftEmptySetSingleton
+ _objc_retain_x10
+ _symbolic _____y_____G s11_SetStorageC 10Foundation8CalendarV9ComponentO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation8CalendarV9ComponentO
- GCC_except_table109
- GCC_except_table117
- GCC_except_table147
- GCC_except_table148
- GCC_except_table66
- GCC_except_table99
CStrings:
+ "<PRUISPortalInfo: renderID=%llu, contextID=%u>"
+ "contextID"
+ "portalInfo"
+ "renderID"
```
