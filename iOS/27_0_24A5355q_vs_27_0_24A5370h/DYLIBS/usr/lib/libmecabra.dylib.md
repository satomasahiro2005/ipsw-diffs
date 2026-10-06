## libmecabra.dylib

> `/usr/lib/libmecabra.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27e3ac` | `0x278568` | **`-0x5e44`** |
| `__TEXT.__gcc_except_tab` | `0x1b464` | `0x1a8d8` | **`-0xb8c`** |
| `__TEXT.__cstring` | `0x1eda4` | `0x1ef3f` | **`+0x19b`** |
| `__TEXT.__oslogstring` | `0x4acd` | `0x49d3` | **`-0xfa`** |
| `__AUTH.__thread_bss` | `0x550` | `0x618` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0xd0f0` | `0xd058` | **`-0x98`** |
| `__DATA.__common` | `0x9a0` | `0xa28` | **`+0x88`** |
| `__DATA.__bss` | `0x1cc0` | `0x1c40` | **`-0x80`** |
| `__TEXT.__const` | `0x3009c` | `0x3001c` | **`-0x80`** |
| `__AUTH_CONST.__const` | `0x43590` | `0x435c8` | **`+0x38`** |
| `__AUTH.__thread_vars` | `0x408` | `0x438` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x9260` | `0x9240` | **`-0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x1f8` | `0x210` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x330` | `0x348` | **`+0x18`** |
| `__DATA.__data` | `0x1bfc` | `0x1bec` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x13e0` | `0x13e8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x168a0` | `0x16898` | **`-0x8`** |
| `__TEXT.__ustring` | `0x32b4` | `0x32ae` | **`-0x6`** |

### Other Changes

```diff

-1146.0.0.0.0
+1148.0.0.0.0

-  Functions: 11216
-  Symbols:   1088
-  CStrings:  4461
+  Functions: 11208
+  Symbols:   1094
+  CStrings:  4460
Symbols:
+ _MecabraCreateInputStringForSubwords
+ _MecabraCreateSubwordTokenIDsForCandidate
+ _MecabraCreateSubwordsForCandidate
+ _MecabraIsNeuralLMAvailable
+ _kMecabraContextOptionUseStringContext
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
- _CFSetCreate
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__expected/expected.h:1624: libc++ Hardening assertion !this->__has_val() failed: expected::error requires the expected to contain an error\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1171: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:434: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:438: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:509: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
+ "Cannot set the NoPruning context option"
+ "Failed to set the context option: %s"
+ "Invalid type of value for key "
+ "Neural LM is not available; skipping LM setup."
+ "The key of the context option must not be NULL"
+ "The value of the context option must not be NULL"
+ "Unsupported context option key: "
+ "Using string context: %@"
+ "[E5Runner] Set left context from %s: '%s' (%zu chars)"
+ "[E5Runner] failed to truncate context from %s"
+ "[JapaneseRNNLMScorer] stringContext surface/words length mismatch (%zu vs %zu), falling back to history"
+ "[TransformerLanguageModel::~TransformerLanguageModel] destroyed e5Runner=%p"
+ "candidateSurface"
+ "stringContext"
+ "unknown"
+ "useStringContext"
+ "啥"
- "## Sorted ##"
- "(null)"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1146: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1156: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:413: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:418: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:433: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:437: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:441: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:445: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:494: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
- "Neural LM is not available."
- "Pruning %@ (kind:%c) (after reranking)"
- "Pruning %@ (n-gram expansion)"
- "[ChineseResource] Started async Transformer reload (OTA), path: %@"
- "[E5Runner] Set left context: '%s' (%zu chars)"
- "[MJ::%s] updating neural language model: %@"
- "[MJNP::expandPhrasesWithLanguageModel] Handling n-gram expansion from"
- "[MJNP::getAndCheckContextSurfaceAndReadingFromCandidate] %@ %@ is an invalid context word."
- "[makeCandidateFromExpandedSequence]"
- "assetDictionariesDidChange"
- "expandTokenSequence: %@ %@ is blocklisted."
- "getAndCheckContextSurfaceAndReadingFromHistory: %@ %@ (attr: %d) is an invalid context word."
- "index: %lu, surface: %@, cost: %d, dynamic-score: %lf, static-score: %lf"
- "makeCandidateFromExpandedSequence: matching inputStr:%@ predictedReading:%@ matchResult:%d incompleteLength:%ld"
- "v48@?0r^I8q16d24q32^B40"
- "お"
- "まし"
```
