## GAXClient

> `/System/Library/AccessibilityBundles/GAXClient.bundle/GAXClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa284` | `0xa7a0` | **`+0x51c`** |
| `__TEXT.__cstring` | `0x2aa6` | `0x2c51` | **`+0x1ab`** |
| `__DATA_CONST.__cfstring` | `0x2a00` | `0x2b40` | **`+0x140`** |
| `__DATA.__objc_const` | `0x2248` | `0x2368` | **`+0x120`** |
| `__DATA.__objc_data` | `0x11d0` | `0x1270` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0xcd0` | `0xd40` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x1c7f` | `0x1ce0` | **`+0x61`** |
| `__TEXT.__objc_classname` | `0x897` | `0x8ef` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0xa4c` | `0xa8c` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x398` | `0x3b8` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x3b6` | `0x3c8` | **`+0x12`** |
| `__DATA.__objc_selrefs` | `0x868` | `0x878` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xc0` | `0xc8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1064.0.0.0.0
+1067.3.0.0.0

-  Functions: 253
-  Symbols:   468
-  CStrings:  761
+  Functions: 262
+  Symbols:   476
+  CStrings:  775
Symbols:
+ _GAXIPCPayloadKeyHostedApplicationCornerRadii
+ _GAXProfileOverridesFromConfigurationDictionary
+ _GAXUIMessageKeyHostedApplicationCornerRadii
+ _OBJC_CLASS_$_GAXSKStoreProductViewControllerOverride
+ _OBJC_CLASS_$___GAXSKStoreProductViewControllerOverride_super
+ _OBJC_METACLASS_$_GAXSKStoreProductViewControllerOverride
+ _OBJC_METACLASS_$___GAXSKStoreProductViewControllerOverride_super
+ _deserializeGAXBackboardState
CStrings:
+ "Fullscreen App Store Presentations are unavailable while Guided Access is active."
+ "GAX StoreKit Product Page Bundle"
+ "GAXIPCPayloadKeyHostedApplicationCornerRadii"
+ "GAXSKStoreProductViewControllerOverride"
+ "Guided StoreKit Product Page"
+ "SKStoreProductViewController"
+ "__GAXSKStoreProductViewControllerOverride_super"
+ "com.apple.accessibility.GuidedAccess"
+ "hosted application corner radii"
+ "loadProductWithParameters: completionBlock:"
+ "loadProductWithParameters: impression: completionBlock:"
+ "loadProductWithParameters:completionBlock:"
+ "loadProductWithParameters:impression:completionBlock:"
+ "v40@0:8@16@24@?32"
```
