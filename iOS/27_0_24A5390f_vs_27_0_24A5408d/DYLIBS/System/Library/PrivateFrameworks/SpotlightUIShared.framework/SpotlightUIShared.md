## SpotlightUIShared

> `/System/Library/PrivateFrameworks/SpotlightUIShared.framework/SpotlightUIShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe1424` | `0xe1d48` | **`+0x924`** |
| `__AUTH_CONST.__const` | `0x6d91` | `0x6e39` | **`+0xa8`** |
| `__AUTH_CONST.__cfstring` | `0x700` | `0x7a0` | **`+0xa0`** |
| `__DATA.__bss` | `0xe730` | `0xe7b0` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x15c0` | `0x1610` | **`+0x50`** |
| `__TEXT.__cstring` | `0x33b8` | `0x3408` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x37b0` | `0x37fc` | **`+0x4c`** |
| `__AUTH.__data` | `0x37f8` | `0x3828` | **`+0x30`** |
| `__TEXT.__const` | `0xa25c` | `0xa28c` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x3c` | `0x18` | **`-0x24`** |
| `__AUTH_CONST.__auth_got` | `0x1d18` | `0x1d30` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1000` | `0x1018` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xf00` | `0xf18` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x2194` | `0x21a4` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x7b4` | `0x7b8` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x328` | `0x32c` | **`+0x4`** |

### Other Changes

```diff

-236.0.11.100.0
+236.0.21.100.0

-  Functions: 5181
-  Symbols:   2259
-  CStrings:  427
+  Functions: 5199
+  Symbols:   2268
+  CStrings:  432
Symbols:
+ +[SUICompletionViewController shouldUseNeutralAskForExtensionString:isAskSiri:queryAddressesExternalProvider:]
+ +[SUIUtilities stringForAuthenticationState:]
+ -[SUICompletionViewController overlayTextViewBoundingRectForCharacterRange:lastSegmentOnly:]
+ -[SUITextView calculateLayoutSizeFittingSize:]
+ GCC_except_table13
+ _CGRectIsEmpty
+ _CGRectUnion
+ _NSParagraphStyleAttributeName
+ _OBJC_CLASS_$_NSParagraphStyle
+ _OBJC_CLASS_$_NSTextRange
+ ___92-[SUICompletionViewController overlayTextViewBoundingRectForCharacterRange:lastSegmentOnly:]_block_invoke
+ ___block_descriptor_48_e8_32r40r_e78_B64?0"NSTextRange"8{CGRect={CGPoint=dd}{CGSize=dd}}16d48"NSTextContainer"56lr32l8r40l8
+ _access
+ _symbolic _____ 17SpotlightUIShared19WindowDisplayPolicyC0cE8DefaultsO
- -[SUICompletionViewController clearAttachmentsFromAttributedString:]
- GCC_except_table10
- _NSIntersectionRange
- ___52-[SUICompletionViewController viewDidLayoutSubviews]_block_invoke
- ___block_descriptor_40_e8_32r_e113_v104?0{CGRect={CGPoint=dd}{CGSize=dd}}8{CGRect={CGPoint=dd}{CGSize=dd}}40"NSTextContainer"72{_NSRange=QQ}80^B96lr32l8
CStrings:
+ "Ask"
+ "B64@?0@\"NSTextRange\"8{CGRect={CGPoint=dd}{CGSize=dd}}16d48@\"NSTextContainer\"56"
+ "BiometryLockout"
+ "Failed to find path for capturedPhotosIndexInfo, /bin/bash is not accessible"
+ "PasscodeLocked"
+ "Unlocked"
- "v104@?0{CGRect={CGPoint=dd}{CGSize=dd}}8{CGRect={CGPoint=dd}{CGSize=dd}}40@\"NSTextContainer\"72{_NSRange=QQ}80^B96"
```
