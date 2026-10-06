## TelephonyRPC

> `/System/Library/PrivateFrameworks/TelephonyRPC.framework/TelephonyRPC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cc84` | `0x1ccd4` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xac0` | `0xae0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xbf8` | `0xc08` | **`+0x10`** |
| `__TEXT.__cstring` | `0x18c4` | `0x18d4` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x950` | `0x958` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3a0` | `0x3a8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x788` | `0x790` | **`+0x8`** |

### Other Changes

```diff

-1151.2.0.0.0
+1155.0.0.0.0

-  Symbols:   971
-  CStrings:  275
+  Symbols:   973
+  CStrings:  276
Symbols:
+ _OBJC_CLASS_$_NSLocale
+ _objc_retain_x25
Functions:
~ -[NSArray(Filtering) max:] : 368 -> 364
~ -[NSArray(Filtering) nph_map:] : 360 -> 356
~ _ListOfVoicemailsToSyncWithManager : 464 -> 460
~ -[VoicemailCompanionReplication syncSession:applyChanges:completion:] : 924 -> 920
~ -[VoicemailCompanionReplication setRemoteVoicemails:] : 408 -> 404
~ +[NPHFeatureFlags isContextCardsEnabled] : 20 -> 124
~ sub_2a6d73d88 -> sub_2a87d8ddc : 2888 -> 2876
~ sub_2a6d76e48 -> sub_2a87dbe90 : 200 -> 216
~ ___swift_closure_destructor.57 : 280 -> 272
~ sub_2a6d7f1cc -> sub_2a87e421c : 992 -> 996
~ sub_2a6d840c8 -> sub_2a87e911c : 280 -> 276
CStrings:
+ "en"
```
