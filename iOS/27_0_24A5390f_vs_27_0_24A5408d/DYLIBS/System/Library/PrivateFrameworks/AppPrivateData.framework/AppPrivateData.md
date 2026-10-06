## AppPrivateData

> `/System/Library/PrivateFrameworks/AppPrivateData.framework/AppPrivateData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8898c` | `0x8f188` | **`+0x67fc`** |
| `__TEXT.__eh_frame` | `0x5318` | `0x57e0` | **`+0x4c8`** |
| `__TEXT.__oslogstring` | `0x8b8` | `0xb18` | **`+0x260`** |
| `__DATA.__data` | `0x2868` | `0x2a10` | **`+0x1a8`** |
| `__TEXT.__unwind_info` | `0x2150` | `0x22e8` | **`+0x198`** |
| `__TEXT.__cstring` | `0x8f7` | `0x9f6` | **`+0xff`** |
| `__AUTH_CONST.__const` | `0x5920` | `0x5848` | **`-0xd8`** |
| `__AUTH_CONST.__objc_const` | `0x1100` | `0x11b0` | **`+0xb0`** |
| `__AUTH_CONST.__auth_got` | `0xf50` | `0xfe0` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0xdc4` | `0xe47` | **`+0x83`** |
| `__TEXT.__swift5_typeref` | `0x1161` | `0x11c1` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x528` | `0x580` | **`+0x58`** |
| `__TEXT.__const` | `0x6290` | `0x62d8` | **`+0x48`** |
| `__DATA.__common` | `0x58` | `0x90` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x168` | `0x18c` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x150` | `0x170` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1b54` | `0x1b74` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x6c8` | `0x6e0` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0xd8` | `0xec` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x23e0` | `0x23d0` | **`-0x10`** |
| `__AUTH.__data` | `0x820` | `0x828` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x234` | `0x22c` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x4c` | `0x50` | **`+0x4`** |

### Other Changes

```diff

-3.0.0.0.0
+5.1.0.0.0

+  - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices

-  Functions: 2746
-  Symbols:   834
-  CStrings:  135
+  Functions: 2841
+  Symbols:   851
+  CStrings:  150
Symbols:
+ _OBJC_CLASS_$_OS_dispatch_source
+ _OBJC_CLASS_$_RBSAcquisitionCompletionAttribute
+ _OBJC_CLASS_$_RBSAssertion
+ _OBJC_CLASS_$_RBSAttribute
+ _OBJC_CLASS_$_RBSDomainAttribute
+ _OBJC_CLASS_$_RBSTarget
+ __OBJC_$_PROTOCOL_REFS_OS_dispatch_source
+ __OBJC_$_PROTOCOL_REFS_OS_dispatch_source_timer
+ __OBJC_LABEL_PROTOCOL_$_OS_dispatch_source
+ __OBJC_LABEL_PROTOCOL_$_OS_dispatch_source_timer
+ __OBJC_PROTOCOL_$_OS_dispatch_source
+ __OBJC_PROTOCOL_$_OS_dispatch_source_timer
+ ___swift_destroy_boxed_opaque_existential_1Tm
+ ___unnamed_101
+ ___unnamed_119
+ ___unnamed_126
+ ___unnamed_128
+ ___unnamed_133
+ ___unnamed_156
+ ___unnamed_162
+ ___unnamed_164
+ ___unnamed_207
+ ___unnamed_208
+ ___unnamed_209
+ ___unnamed_216
+ ___unnamed_221
+ ___unnamed_252
+ ___unnamed_254
+ ___unnamed_259
+ ___unnamed_260
+ ___unnamed_261
+ ___unnamed_308
+ ___unnamed_309
+ ___unnamed_310
+ ___unnamed_311
+ ___unnamed_94
+ ___unnamed_97
+ _objc_retain_x10
+ _objc_retain_x13
+ _symbolic $s14AppPrivateData0bC21EncryptionKeyProviderP
+ _symbolic So12RBSAssertionC
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 14AppPrivateData9AssertionC07RunningD033_71F0380C070762253E2CA2CE65BEFC45LLV
+ _symbolic _____XMT 14AppPrivateData9AssertionC
+ _symbolic ______pSg 14AppPrivateData0bC21EncryptionKeyProviderP
+ _symbolic yyYbc
+ _type_layout_string 14AppPrivateData9AssertionC07RunningD033_71F0380C070762253E2CA2CE65BEFC45LLV
- __OBJC_$_PROTOCOL_REFS_CKRecordValue
- __OBJC_LABEL_PROTOCOL_$_CKRecordValue
- __OBJC_PROTOCOL_$_CKRecordValue
- ___unnamed_100
- ___unnamed_118
- ___unnamed_125
- ___unnamed_127
- ___unnamed_129
- ___unnamed_152
- ___unnamed_154
- ___unnamed_160
- ___unnamed_203
- ___unnamed_204
- ___unnamed_205
- ___unnamed_212
- ___unnamed_217
- ___unnamed_248
- ___unnamed_250
- ___unnamed_251
- ___unnamed_256
- ___unnamed_257
- ___unnamed_301
- ___unnamed_302
- ___unnamed_303
- ___unnamed_304
- ___unnamed_93
- ___unnamed_96
- _symbolic _____ 14AppPrivateData8CKSchemaO
- _symbolic _____ 14AppPrivateData8CKSchemaO14SecureSentinelO
- _symbolic _____ 14AppPrivateData8CKSchemaO14SecureSentinelO6FieldsO
CStrings:
+ "Acquired RBSAssertion. Name=%{public}s"
+ "Acquiring RBSAssertion. Name=%{public}s"
+ "Assertion no longer has interest; invalidating assertion. Name=%{public}s"
+ "Attempting to invalidate an missing assertion"
+ "Decreasing interest in assertion. Name=%{public}s, New Interest Count=%{public}ld"
+ "Dropping table due to entity version change, table=%{public}s, oldVersion=%{public}s, newVersion=%{public}s"
+ "Error acquiring RBSAssertion. Name=%{public}s, Error=%{public}@"
+ "Error trying to acquire an RBAssertion; error=%{public}s"
+ "FinishTaskUninterruptable"
+ "Increasing interest in assertion. Name=%{public}s, New Interest Count=%{public}ld"
+ "TeaDB sqlite statement execution"
+ "_lastFetchChangesDate"
+ "com.apple.common"
+ "com.apple.teadb.assertion_invalidation"
+ "lastFetchChangesDate"
```
