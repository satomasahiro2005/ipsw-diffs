## AppStoreComponents

> `/System/Library/PrivateFrameworks/AppStoreComponents.framework/AppStoreComponents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90a64` | `0x90e94` | **`+0x430`** |
| `__AUTH_CONST.__objc_const` | `0xf960` | `0xfab0` | **`+0x150`** |
| `__TEXT.__objc_methlist` | `0x8bbc` | `0x8c54` | **`+0x98`** |
| `__AUTH.__objc_data` | `0x1168` | `0x11b8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2758` | `0x2780` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x4ce0` | `0x4d00` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3941` | `0x3961` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ec8` | `0x3ed8` | **`+0x10`** |
| `__TEXT.__const` | `0x2384` | `0x2394` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x19e0` | `0x19e8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x498` | `0x4a0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x428` | `0x430` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x880` | `0x884` | **`+0x4`** |

### Other Changes

```diff

-27.0.45.0.0
+27.0.46.2.1

-  Functions: 3814
-  Symbols:   5943
-  CStrings:  972
+  Functions: 3825
+  Symbols:   5966
+  CStrings:  973
Symbols:
+ +[ASCLockupFeatureContentDescriptors supportsSecureCoding]
+ -[ASCLockup(ContentDescriptors) contentDescriptors]
+ -[ASCLockupFeatureContentDescriptors .cxx_destruct]
+ -[ASCLockupFeatureContentDescriptors contentDescriptors]
+ -[ASCLockupFeatureContentDescriptors copyWithZone:]
+ -[ASCLockupFeatureContentDescriptors description]
+ -[ASCLockupFeatureContentDescriptors encodeWithCoder:]
+ -[ASCLockupFeatureContentDescriptors hash]
+ -[ASCLockupFeatureContentDescriptors initWithCoder:]
+ -[ASCLockupFeatureContentDescriptors initWithContentDescriptors:]
+ -[ASCLockupFeatureContentDescriptors isEqual:]
+ _OBJC_CLASS_$_ASCLockupFeatureContentDescriptors
+ _OBJC_IVAR_$_ASCLockupFeatureContentDescriptors._contentDescriptors
+ _OBJC_METACLASS_$_ASCLockupFeatureContentDescriptors
+ __ASCLockupKeyContentDescriptors
+ __OBJC_$_CLASS_METHODS_ASCLockupFeatureContentDescriptors
+ __OBJC_$_CLASS_PROP_LIST_ASCLockupFeatureContentDescriptors
+ __OBJC_$_INSTANCE_METHODS_ASCLockup(Ad|AgeRatingValue|AppDistribution|AppDistributionInstall|BundleID|BuyParams|ContentDescriptors|DeveloperName|DisplayContext|ExtendedAttributes|Genre|Media|Metadata|MiniProductPage|ProductVariants|SafariExtension|ShortName|ASCSignpostTags|SingleSignOn|ASCDeprecated)
+ __OBJC_$_INSTANCE_METHODS_ASCLockupFeatureContentDescriptors
+ __OBJC_$_INSTANCE_VARIABLES_ASCLockupFeatureContentDescriptors
+ __OBJC_$_PROP_LIST_ASCLockupFeatureContentDescriptors
+ __OBJC_CLASS_PROTOCOLS_$_ASCLockupFeatureContentDescriptors
+ __OBJC_CLASS_RO_$_ASCLockupFeatureContentDescriptors
+ __OBJC_METACLASS_RO_$_ASCLockupFeatureContentDescriptors
- __OBJC_$_INSTANCE_METHODS_ASCLockup(Ad|AgeRatingValue|AppDistribution|AppDistributionInstall|BundleID|BuyParams|DeveloperName|DisplayContext|ExtendedAttributes|Genre|Media|Metadata|MiniProductPage|ProductVariants|SafariExtension|ShortName|ASCSignpostTags|SingleSignOn|ASCDeprecated)
CStrings:
+ "contentDescriptors"
```
