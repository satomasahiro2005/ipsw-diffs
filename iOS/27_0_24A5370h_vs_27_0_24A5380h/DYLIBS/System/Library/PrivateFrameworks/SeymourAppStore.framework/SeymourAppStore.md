## SeymourAppStore

> `/System/Library/PrivateFrameworks/SeymourAppStore.framework/SeymourAppStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10850` | `0x128c0` | **`+0x2070`** |
| `__TEXT.__cstring` | `0x177` | `0x377` | **`+0x200`** |
| `__TEXT.__eh_frame` | `0x7cc` | `0x944` | **`+0x178`** |
| `__TEXT.__oslogstring` | `0x74a` | `0x81a` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x730` | `0x7f0` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x428` | `0x498` | **`+0x70`** |
| `__TEXT.__const` | `0x6e0` | `0x740` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x238` | `0x270` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x6f8` | `0x728` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x218` | `0x248` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x780` | `0x7a0` | **`+0x20`** |
| `__DATA.__data` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x168` | `0x188` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x50` | `0x70` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x444` | `0x460` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x2bc` | `0x2d8` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x38` | `0x48` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x598` | `0x59e` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x34` | `0x38` | **`+0x4`** |

### Other Changes

```diff

-2027.0.117.0.2
+2027.0.124.0.3

-  Functions: 283
-  Symbols:   334
-  CStrings:  34
+  Functions: 316
+  Symbols:   337
+  CStrings:  45
Symbols:
+ _OBJC_CLASS_$_AMSAcknowledgePrivacyTask
+ _OBJC_CLASS_$_AMSDefaults
+ ___swift_closure_destructorTm
+ _symbolic _____ 15SeymourAppStore28PrivacyAcknowledgementSystemV
- _os_proc_available_memory
CStrings:
+ "AppStoreListener.approvePrivacyAcknowledgement"
+ "AppStoreListener.rejectPrivacyAcknowledgement"
+ "AppStoreListener.resolveNoticePrivacyPreference"
+ "AppStoreListener.resolveOptInPrivacyPreference"
+ "SeymourAppStore/PrivacyAcknowledgementSystem.swift"
+ "[%{public}s] %{public}s begin footprint=%{public}fKB"
+ "[PrivacyAcknowledgementSystem] approvePrivacyAcknowledgement completed result = %{bool}d"
+ "[PrivacyAcknowledgementSystem] rejectPrivacyAcknowledgement completed result = %{bool}d"
+ "approvePrivacyAcknowledgement(privacyIdentifier:)"
+ "rejectPrivacyAcknowledgement(privacyIdentifier:)"
+ "resolveNoticePrivacyPreference(privacyIdentifier:)"
+ "resolveOptInPrivacyPreference(privacyIdentifier:)"
- "[%{public}s] %{public}s begin mem=%{public}fKB"
```
