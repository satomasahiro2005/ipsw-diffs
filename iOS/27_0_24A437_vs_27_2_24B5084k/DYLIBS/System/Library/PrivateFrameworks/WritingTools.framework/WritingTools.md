## WritingTools

> `/System/Library/PrivateFrameworks/WritingTools.framework/WritingTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa518` | `0xa8c0` | **`+0x3a8`** |
| `__AUTH_CONST.__objc_const` | `0x1340` | `0x1520` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0x8a4` | `0x96c` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x647` | `0x6f7` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x5c0` | `0x640` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x140` | `0x190` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x500` | `0x528` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x388` | `0x3a0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x78` | `0x88` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x40` | `0x48` | **`+0x8`** |

### Other Changes

```diff

-149.104.0.0.0
+151.1.4.0.0

-  Functions: 274
-  Symbols:   536
-  CStrings:  75
+  Functions: 289
+  Symbols:   565
+  CStrings:  79
Symbols:
+ +[WTPrecomputedData supportsBSXPCSecureCoding]
+ +[WTPrecomputedData supportsSecureCoding]
+ -[WTPrecomputedData .cxx_destruct]
+ -[WTPrecomputedData copyWithZone:]
+ -[WTPrecomputedData encodeWithBSXPCCoder:]
+ -[WTPrecomputedData encodeWithCoder:]
+ -[WTPrecomputedData encodeWithGeneralCoder:]
+ -[WTPrecomputedData initWithBSXPCCoder:]
+ -[WTPrecomputedData initWithCoder:]
+ -[WTPrecomputedData initWithGeneralCoder:]
+ -[WTPrecomputedData initWithPrecomputedResultText:precomputedCitationsJSON:precomputedContentAdvisoriesJSON:precomputedResultReplacesExisting:]
+ -[WTPrecomputedData precomputedCitationsJSON]
+ -[WTPrecomputedData precomputedContentAdvisoriesJSON]
+ -[WTPrecomputedData precomputedResultReplacesExisting]
+ -[WTPrecomputedData precomputedResultText]
+ _OBJC_CLASS_$_WTPrecomputedData
+ _OBJC_IVAR_$_WTPrecomputedData._precomputedCitationsJSON
+ _OBJC_IVAR_$_WTPrecomputedData._precomputedContentAdvisoriesJSON
+ _OBJC_IVAR_$_WTPrecomputedData._precomputedResultReplacesExisting
+ _OBJC_IVAR_$_WTPrecomputedData._precomputedResultText
+ _OBJC_METACLASS_$_WTPrecomputedData
+ __OBJC_$_CLASS_METHODS_WTPrecomputedData
+ __OBJC_$_CLASS_PROP_LIST_WTPrecomputedData
+ __OBJC_$_INSTANCE_METHODS_WTPrecomputedData
+ __OBJC_$_INSTANCE_VARIABLES_WTPrecomputedData
+ __OBJC_$_PROP_LIST_WTPrecomputedData
+ __OBJC_CLASS_PROTOCOLS_$_WTPrecomputedData
+ __OBJC_CLASS_RO_$_WTPrecomputedData
+ __OBJC_METACLASS_RO_$_WTPrecomputedData
CStrings:
+ "WTPrecomputedDataCodingKeyCitationsJSON"
+ "WTPrecomputedDataCodingKeyContentAdvisoriesJSON"
+ "WTPrecomputedDataCodingKeyResultReplacesExisting"
+ "WTPrecomputedDataCodingKeyResultText"
```
