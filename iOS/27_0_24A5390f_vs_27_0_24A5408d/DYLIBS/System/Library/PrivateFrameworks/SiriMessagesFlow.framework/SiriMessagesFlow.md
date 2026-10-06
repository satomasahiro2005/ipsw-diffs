## SiriMessagesFlow

> `/System/Library/PrivateFrameworks/SiriMessagesFlow.framework/SiriMessagesFlow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x395c28` | `0x3981ac` | **`+0x2584`** |
| `__TEXT.__unwind_info` | `0xce80` | `0xcaa8` | **`-0x3d8`** |
| `__TEXT.__oslogstring` | `0x2626f` | `0x2638f` | **`+0x120`** |
| `__TEXT.__swift5_fieldmd` | `0x9b6c` | `0x9c50` | **`+0xe4`** |
| `__TEXT.__eh_frame` | `0x25168` | `0x25208` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x15369` | `0x153e1` | **`+0x78`** |
| `__AUTH.__data` | `0x11d20` | `0x11d90` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x48f8` | `0x4928` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0xd2f4` | `0xd31c` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x846b` | `0x848b` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x47e8` | `0x47f8` | **`+0x10`** |
| `__DATA.__data` | `0x4b50` | `0x4b60` | **`+0x10`** |
| `__TEXT.__const` | `0x147e4` | `0x147d4` | **`-0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3600.47.13.0.0
+3600.47.22.11.2

-  Functions: 18314
-  Symbols:   3862
-  CStrings:  3087
+  Functions: 18345
+  Symbols:   3861
+  CStrings:  3091
Symbols:
+ ___swift_closure_destructor.117Tm
+ ___swift_get_extra_inhabitant_index.198Tm
+ ___swift_get_extra_inhabitant_index.81Tm
+ ___swift_store_extra_inhabitant_index.199Tm
+ ___swift_store_extra_inhabitant_index.82Tm
- _INIntentSlotValueTransformToContactValue
- ___swift_closure_destructor.106Tm
- ___swift_get_extra_inhabitant_index.197Tm
- ___swift_get_extra_inhabitant_index.80Tm
- ___swift_store_extra_inhabitant_index.198Tm
- ___swift_store_extra_inhabitant_index.81Tm
CStrings:
+ "#BannerPreprocessing Creating banner preprocessing assistant utterance view..."
+ "#BannerPreprocessing attaching notificationId to empty utterance view"
+ "#BannerPreprocessing feature flag is enabled"
+ "#INPerson decoded search-candidate ContactQuery from customIdentifier"
+ "#MessagesFlowDelegatePlugin LW 3pFallback enriching recipients via CRR (target app %s) with queries: %s"
+ "#MessagesFlowDelegatePlugin LW 3pFallback rewrote recipient %@ to %@"
+ "doneAssociatedEntitiesData"
- "#MessagesFlowDelegatePlugin LW 3pFallback enriching recipients via CRR with queries: %s"
- "#MessagesFlowDelegatePlugin LW 3pFallback rewrote flat recipient %@ to hollow parent %@"
- "contactHandle://"
```
