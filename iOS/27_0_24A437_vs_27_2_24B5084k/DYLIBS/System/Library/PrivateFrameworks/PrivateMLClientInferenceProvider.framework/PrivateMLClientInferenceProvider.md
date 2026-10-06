## PrivateMLClientInferenceProvider

> `/System/Library/PrivateFrameworks/PrivateMLClientInferenceProvider.framework/PrivateMLClientInferenceProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x958d8` | `0x9fb9c` | **`+0xa2c4`** |
| `__TEXT.__eh_frame` | `0x2b48` | `0x2f78` | **`+0x430`** |
| `__AUTH_CONST.__auth_got` | `0x1ac8` | `0x1ca8` | **`+0x1e0`** |
| `__TEXT.__unwind_info` | `0xdc8` | `0xf48` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x3e8b` | `0x3f1b` | **`+0x90`** |
| `__TEXT.__cstring` | `0xe6b` | `0xef1` | **`+0x86`** |
| `__DATA.__data` | `0x518` | `0x560` | **`+0x48`** |
| `__DATA_DIRTY.__data` | `0x920` | `0x8e8` | **`-0x38`** |
| `__TEXT.__swift5_typeref` | `0xb6e` | `0xba2` | **`+0x34`** |
| `__AUTH_CONST.__const` | `0x1a38` | `0x1a60` | **`+0x28`** |
| `__DATA.__common` | `0x8` | `0x30` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xe0` | `0xb8` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0x24c` | `0x270` | **`+0x24`** |
| `__TEXT.__swift_as_ret` | `0x110` | `0x124` | **`+0x14`** |
| `__TEXT.__const` | `0x1ff8` | `0x1fe8` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x7ac` | `0x7b4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x104` | `0x10c` | **`+0x8`** |

### Other Changes

```diff

-215.2.0.0.0
+218.5.0.0.0

-  Functions: 960
+  Functions: 1044

-  CStrings:  388
+  CStrings:  395
Symbols:
+ ___swift_closure_destructor.37Tm
+ ___swift_closure_destructor.41Tm
+ ___swift_closure_destructor.55Tm
+ ___swift_closure_destructor.7Tm
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ __swiftEmptySetSingleton
+ _objc_retain_x23
+ _symbolic _____Sg 20ModelManagerServices10ClientDataV
+ _symbolic _____XDXMT 32PrivateMLClientInferenceProvider03NewcD0C
+ _symbolic ___________t 29GenerativeFunctionsFoundation0A5ErrorV06PromptD0V0D4TypeO0e17InjectionRejectedD4InfoV 15TokenGeneration0jkD0O7ContextV
+ _symbolic _____ySSG s11_SetStorageC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 15PrivateMLClient30Tie_CloudGuardrailsInputPolicyV26UntrustedToolResultContentV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 29GenerativeFunctionsFoundation0D5ErrorV06PromptG0V0G4TypeO0h17InjectionRejectedG4InfoV17UnverifiedContentV
- _OBJC_CLASS_$_RBSAssertion
- _OBJC_CLASS_$_RBSAttribute
- _OBJC_CLASS_$_RBSDomainAttribute
- _OBJC_CLASS_$_RBSTarget
- ___swift_closure_destructor.140Tm
- ___swift_closure_destructor.185Tm
- ___swift_closure_destructor.19Tm
- _objc_retain_x19
- _objc_retain_x21
- _objc_retain_x24
- _swift_deallocBox
- _symbolic _____yyXlG s23_ContiguousArrayStorageC
- _symbolic _____z_Xx 15TokenGeneration23StreamingRequestPayloadO
CStrings:
+ " requestOneShot replay write"
+ " requestOneShot transparency reporter"
+ " requestStream replay write"
+ " streaming replay write"
+ "%s donation locale source: %{public}s count: %{public}ld"
+ "%s failed to materialize image surfaces for request payload: %@"
+ "%s failed to materialize image surfaces for streaming payload: %@"
+ "%s max tokens not set will be overridden."
+ "%s prewarm failed. sessionUUID=%s modelBundleIdentifier=%s featureIdentifier=%s bundleIdentifier=%s error=%@"
+ "%{private}s failed due to prompt injection rejection"
+ "%{public}s"
+ "Dropping incomplete media candidate; no last chunk received. media_id=%{private}s"
+ "Prompt injection rejected: "
+ "cloudGuardrailsEnvelope: unrecognized untrusted-content case, sending no IPI coverage"
+ "networkPayload"
+ "none (donation will use the device locale)"
+ "sessionHint status `terminated` failed for sessionID:%s"
- "%s max tokens not set will be overriden."
- "%s prewarm failed. sessionUUID=%s modelBundleIdentifier=%s featureIdentifier=%s bundleIdentifier=%s"
- "%s: Failed to acquire RBS assertion for requestOneShot replay write: %@"
- "%s: Failed to acquire RBS assertion for requestOneShot transparency reporter: %@"
- "%s: Failed to acquire RBS assertion for requestStream replay write: %@"
- "%s: Failed to acquire RBS assertion for streaming replay write: %@"
- "FinishTaskUninterruptable"
- "PrivateMLClient post-request tasks"
- "com.apple.common"
- "sessionHint status `terminated` failed for sessionID:%s "
```
