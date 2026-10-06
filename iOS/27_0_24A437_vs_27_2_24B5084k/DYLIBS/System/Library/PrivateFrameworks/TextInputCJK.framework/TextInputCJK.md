## TextInputCJK

> `/System/Library/PrivateFrameworks/TextInputCJK.framework/TextInputCJK`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f270` | `0x1f518` | **`+0x2a8`** |
| `__AUTH_CONST.__cfstring` | `0x2860` | `0x2880` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x260` | `0x280` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1f00` | `0x1f20` | **`+0x20`** |
| `__DATA.__bss` | `0x110` | `0x120` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c98` | `0x1ca8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x420` | `0x428` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6c0` | `0x6c8` | **`+0x8`** |
| `__TEXT.__ustring` | `0x4fa` | `0x502` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3567.0.0.0.0
+3568.1.4.0.0

-  Functions: 695
-  Symbols:   1430
-  CStrings:  373
+  Functions: 698
+  Symbols:   1436
+  CStrings:  374
Symbols:
+ +[TIChineseExtras stringContainsOffensiveCharacter:]
+ -[TIWordSearchChinesePhonetic chaiziCandidatesWithOperation:candidateResultSet:useDictionaryReadingForFirstCandidate:]
+ -[TIWordSearchChinesePhonetic dictionaryReadingForCandidate:candidateResultSet:]
+ _OBJC_CLASS_$_TIMecabraComposedCharacterCandidate
+ ___52+[TIChineseExtras stringContainsOffensiveCharacter:]_block_invoke
+ _stringContainsOffensiveCharacter:.offensiveCharacterSet
+ _stringContainsOffensiveCharacter:.onceToken
- -[TIWordSearchChinesePhonetic chaiziCandidatesWithOperation:candidateResultSet:]
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "屄屌肏"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
```
