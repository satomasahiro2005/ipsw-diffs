## PrivateMLClientInferenceProvider

> `/System/Library/PrivateFrameworks/PrivateMLClientInferenceProvider.framework/PrivateMLClientInferenceProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8d268` | `0x8f73c` | **`+0x24d4`** |
| `__TEXT.__eh_frame` | `0x2120` | `0x27e8` | **`+0x6c8`** |
| `__TEXT.__oslogstring` | `0x39db` | `0x3d6b` | **`+0x390`** |
| `__TEXT.__unwind_info` | `0xbb0` | `0xcc8` | **`+0x118`** |
| `__TEXT.__cstring` | `0xceb` | `0xd9b` | **`+0xb0`** |
| `__TEXT.__swift_as_cont` | `0x1b8` | `0x210` | **`+0x58`** |
| `__TEXT.__const` | `0x1de8` | `0x1e38` | **`+0x50`** |
| `__TEXT.__swift_as_ret` | `0xbc` | `0xf0` | **`+0x34`** |
| `__AUTH_CONST.__const` | `0x1380` | `0x13a8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xa8` | `0xd0` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1948` | `0x1960` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x324` | `0x33c` | **`+0x18`** |
| `__DATA.__data` | `0x558` | `0x568` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xaf6` | `0xb02` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0xd8` | `0xe4` | **`+0xc`** |

### Other Changes

```diff

-201.0.2.0.0
+204.0.2.0.0

-  Functions: 831
-  Symbols:   498
-  CStrings:  359
+  Functions: 874
+  Symbols:   504
+  CStrings:  377
Symbols:
+ _OBJC_CLASS_$_RBSAssertion
+ _OBJC_CLASS_$_RBSAttribute
+ _OBJC_CLASS_$_RBSDomainAttribute
+ _OBJC_CLASS_$_RBSTarget
+ ___swift_closure_destructor.155Tm
+ _objc_retain_x19
+ _objc_retain_x25
+ _symbolic _____yyXlG s23_ContiguousArrayStorageC
- ___swift_closure_destructor.147Tm
- _objc_retain_x26
CStrings:
+ "%s Image cache miss, retrying with original image data"
+ "%s: Failed to acquire RBS assertion for requestOneShot replay write: %@"
+ "%s: Failed to acquire RBS assertion for requestOneShot transparency reporter: %@"
+ "%s: Failed to acquire RBS assertion for requestStream replay write: %@"
+ "%s: Failed to acquire RBS assertion for streaming replay write: %@"
+ "FinishTaskUninterruptable"
+ "PrivateMLClient post-request tasks"
+ "PrivateMLRequestError.com.apple.pccagent.imagecache"
+ "Writing CompletePrompt to disk complete."
+ "[end] resolveImages: completePrompt - oneShot"
+ "[end] resolveImages: completePrompt - streaming"
+ "[end] resolveImages: completePromptTemplate - oneShot"
+ "[end] resolveImages: completePromptTemplate - streaming"
+ "[start] resolveImages: completePrompt - oneShot"
+ "[start] resolveImages: completePrompt - streaming"
+ "[start] resolveImages: completePromptTemplate - oneShot"
+ "[start] resolveImages: completePromptTemplate - streaming"
+ "com.apple.common"
```
