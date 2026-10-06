## CoreDuet

> `/System/Library/PrivateFrameworks/CoreDuet.framework/CoreDuet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18f800` | `0x18fce8` | **`+0x4e8`** |
| `__AUTH_CONST.__objc_const` | `0x22df8` | `0x22ec0` | **`+0xc8`** |
| `__TEXT.__objc_methlist` | `0x1168c` | `0x11734` | **`+0xa8`** |
| `__DATA.__data` | `0x19e0` | `0x1a40` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x5450` | `0x54a8` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x8048` | `0x8080` | **`+0x38`** |
| `__TEXT.__cstring` | `0x15cd7` | `0x15d00` | **`+0x29`** |
| `__AUTH_CONST.__const` | `0x1b00` | `0x1b20` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x3ca0` | `0x3cc0` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x22b0` | `0x22c8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1198` | `0x11a0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x218` | `0x220` | **`+0x8`** |

### Other Changes

```diff

-1967.0.0.0.0
+1971.0.0.0.0

-  Functions: 8782
-  Symbols:   13348
-  CStrings:  4650
+  Functions: 8792
+  Symbols:   13366
+  CStrings:  4651
Symbols:
+ +[NSNumber(_CDCompactDoubleNumber) _cd_compactNumberWithDouble:]
+ -[NSDate(_CDCompactDoubleNumber) _cd_compactValue]
+ -[NSDate(_CDCompactDoubleNumber) _cd_doubleValue]
+ -[NSDate(_CDCompactDoubleNumber) _cd_numberValue]
+ -[NSNumber(_CDCompactDoubleNumber) _cd_compactValue]
+ -[NSNumber(_CDCompactDoubleNumber) _cd_doubleValue]
+ -[NSNumber(_CDCompactDoubleNumber) _cd_numberValue]
+ -[_CDInteraction strippedCopy]
+ -[_CDInteractionStore deleteUnreferencedAttachments]
+ GCC_except_table110
+ GCC_except_table117
+ _RPOptionStatusFlags
+ __OBJC_$_CLASS_METHODS_NSNumber(_DKDeduping|_CDCompactDoubleNumber)
+ __OBJC_$_INSTANCE_METHODS_NSDate(CDRound|_DKAdditions|_DKDeduping|_CDCompactDoubleNumber)
+ __OBJC_$_INSTANCE_METHODS_NSNumber(_DKDeduping|_CDCompactDoubleNumber)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS__CDCompactDoubleNumber
+ __OBJC_$_PROTOCOL_METHOD_TYPES__CDCompactDoubleNumber
+ __OBJC_$_PROTOCOL_REFS__CDCompactDoubleNumber
+ __OBJC_CLASS_PROTOCOLS_$_NSDate(CDRound|_DKAdditions|_DKDeduping|_CDCompactDoubleNumber)
+ __OBJC_CLASS_PROTOCOLS_$_NSNumber(_DKDeduping|_CDCompactDoubleNumber)
+ __OBJC_LABEL_PROTOCOL_$__CDCompactDoubleNumber
+ __OBJC_PROTOCOL_$__CDCompactDoubleNumber
+ ___block_descriptor_32_e40_"_CDInteraction"16?0"_CDInteraction"8l
- GCC_except_table108
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSNumber_$__DKDeduping
- __OBJC_$_INSTANCE_METHODS_NSDate(CDRound|_DKAdditions|_DKDeduping)
- __OBJC_CATEGORY_PROTOCOLS_$_NSNumber_$__DKDeduping
- __OBJC_CLASS_PROTOCOLS_$_NSDate(CDRound|_DKAdditions|_DKDeduping)
CStrings:
+ "@\"_CDInteraction\"16@?0@\"_CDInteraction\"8"
```
