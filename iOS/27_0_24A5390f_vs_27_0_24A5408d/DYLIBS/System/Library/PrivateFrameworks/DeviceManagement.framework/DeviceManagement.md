## DeviceManagement

> `/System/Library/PrivateFrameworks/DeviceManagement.framework/DeviceManagement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39260` | `0x39b14` | **`+0x8b4`** |
| `__DATA_CONST.__objc_selrefs` | `0x1dc8` | `0x1e08` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x75c4` | `0x75ec` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x370` | `0x378` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xfa0` | `0xfa8` | **`+0x8`** |

### Other Changes

```diff

-260.0.0.0.0
+261.2.5.0.0

-  Functions: 2395
-  Symbols:   4895
+  Functions: 2398
+  Symbols:   4899
Symbols:
+ -[DMFEffectivePolicy excludesIdentifier:]
+ -[DMFEffectivePolicy policyByAddingExcludedIdentifiers:]
+ -[DMFEffectivePolicy policyByRemovingIdentifiers:minimumPriority:]
+ GCC_except_table20
+ ___kCFBooleanTrue
- GCC_except_table17
```
