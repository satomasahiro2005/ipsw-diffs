## AppleTV

> `/private/var/staged_system_apps/AppleTV.app/AppleTV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x2395` | `0x24b3` | **`+0x11e`** |
| `__TEXT.__objc_stubs` | `0x1360` | `0x13e0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0xa54` | `0xacc` | **`+0x78`** |
| `__DATA.__objc_const` | `0x2990` | `0x29f8` | **`+0x68`** |
| `__DATA.__data` | `0x5d8` | `0x638` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0xf39` | `0xf79` | **`+0x40`** |
| `__TEXT.__text` | `0xb168` | `0xb1a0` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x8a0` | `0x8c8` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x206` | `0x226` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x820` | `0x828` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x78` | `0x80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1145.0.6.0.0
+1145.1.1.0.0

+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 269
-  Symbols:   340
-  CStrings:  497
+  Functions: 273
+  Symbols:   341
+  CStrings:  507
Symbols:
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
CStrings:
+ "@\"NSArray\"16@0:8"
+ "@\"NSString\"24@0:8@\"NSString\"16"
+ "T@\"NSArray\",R,N"
+ "UIGuidedAccessRestrictionDelegate"
+ "detailTextForGuidedAccessRestrictionWithIdentifier:"
+ "guidedAccessRestrictionIdentifiers"
+ "guidedAccessRestrictionWithIdentifier:didChangeState:"
+ "handleGuidedAccessRestrictionChangeWithIdentifier:denied:"
+ "textForGuidedAccessRestrictionWithIdentifier:"
+ "v32@0:8@\"NSString\"16q24"
```
