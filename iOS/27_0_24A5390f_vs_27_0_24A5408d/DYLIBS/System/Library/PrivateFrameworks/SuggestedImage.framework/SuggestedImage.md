## SuggestedImage

> `/System/Library/PrivateFrameworks/SuggestedImage.framework/SuggestedImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xefe0c` | `0xf8060` | **`+0x8254`** |
| `__TEXT.__eh_frame` | `0xbdd8` | `0xc508` | **`+0x730`** |
| `__TEXT.__unwind_info` | `0x4230` | `0x4390` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x207d` | `0x21c8` | **`+0x14b`** |
| `__TEXT.__const` | `0x7925` | `0x7a6d` | **`+0x148`** |
| `__TEXT.__cstring` | `0x595a` | `0x5a06` | **`+0xac`** |
| `__AUTH_CONST.__const` | `0x4b00` | `0x4b70` | **`+0x70`** |
| `__TEXT.__swift_as_ret` | `0x618` | `0x678` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x161c` | `0x1678` | **`+0x5c`** |
| `__TEXT.__swift_as_cont` | `0xae0` | `0xb34` | **`+0x54`** |
| `__TEXT.__constg_swiftt` | `0x1c38` | `0x1c74` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x12f8` | `0x1330` | **`+0x38`** |
| `__DATA.__data` | `0xc70` | `0xca8` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x1bcc` | `0x1bf4` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x5c0` | `0x59c` | **`-0x24`** |
| `__TEXT.__swift_as_entry` | `0x37c` | `0x39c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x630` | `0x648` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x1a70` | `0x1a88` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xc8` | `0xdc` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0x17b7` | `0x17c7` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x78` | `0x80` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x200` | `0x204` | **`+0x4`** |

### Other Changes

```diff

-194.1.0.0.0
+198.1.0.0.0

-  Functions: 3819
-  Symbols:   1686
-  CStrings:  451
+  Functions: 3875
+  Symbols:   1695
+  CStrings:  459
Symbols:
+ ___swift_allocate_boxed_opaque_existential_0
+ ___swift_closure_destructor.276Tm
+ ___swift_project_boxed_opaque_existential_0
+ _get_enum_tag_for_layout_string 14SuggestedImage17UseCaseAuthorizerV24AuthorizationRequirementO
+ _symbolic SS6reason_t
+ _symbolic SS______6reasont 16VisualGeneration15RejectionReasonO
+ _symbolic ScCyyt______pG s5ErrorP
+ _symbolic _____ 14SuggestedImage30PosterBoardDescriptorRefresherO
+ _symbolic _____17rejectionCategory______6reasont 16VisualGeneration17ImageCheckerErrorO17RejectionCategoryO AA0F6ReasonO
+ _type_layout_string 14SuggestedImage17UseCaseAuthorizerV24AuthorizationRequirementO
- ___swift_closure_destructor.271Tm
CStrings:
+ "Could not prune deleted-source-asset requests for %s: %@"
+ "Error refreshing poster descriptors: %@"
+ "Failed to mark asset request %s as refused after a safety failure: %@"
+ "Outside this device's generation window; deferring personalization production until next slot at %{public}s."
+ "Refreshed poster descriptors"
+ "_createCheckedThrowingContinuation(_:)"
+ "com.apple.Posters.ImagePlaygroundPosterApp.ImagePlaygroundPoster"
+ "commonPhrases pre-generation is disabled"
```
