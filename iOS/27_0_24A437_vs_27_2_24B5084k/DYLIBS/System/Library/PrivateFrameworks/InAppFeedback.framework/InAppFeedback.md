## InAppFeedback

> `/System/Library/PrivateFrameworks/InAppFeedback.framework/InAppFeedback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x460e0` | `0x50300` | **`+0xa220`** |
| `__DATA.__bss` | `0x5a80` | `0x5f80` | **`+0x500`** |
| `__TEXT.__eh_frame` | `0x20b8` | `0x2518` | **`+0x460`** |
| `__TEXT.__const` | `0x39f8` | `0x3d28` | **`+0x330`** |
| `__TEXT.__swift5_typeref` | `0xe35` | `0x1013` | **`+0x1de`** |
| `__TEXT.__unwind_info` | `0x1368` | `0x14e8` | **`+0x180`** |
| `__DATA.__data` | `0xdf0` | `0xee0` | **`+0xf0`** |
| `__AUTH.__data` | `0xfe0` | `0x10c8` | **`+0xe8`** |
| `__TEXT.__swift5_fieldmd` | `0xfc4` | `0x10a8` | **`+0xe4`** |
| `__AUTH_CONST.__const` | `0x1f00` | `0x1fb8` | **`+0xb8`** |
| `__TEXT.__swift5_reflstr` | `0x85d` | `0x8bd` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0xd68` | `0xdbc` | **`+0x54`** |
| `__AUTH_CONST.__auth_got` | `0xb78` | `0xbc0` | **`+0x48`** |
| `__TEXT.__swift5_proto` | `0x2e8` | `0x310` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0xe08` | `0xde8` | **`-0x20`** |
| `__TEXT.__cstring` | `0x452` | `0x472` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x218` | `0x230` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x14c` | `0x134` | **`-0x18`** |
| `__TEXT.__swift5_types` | `0x108` | `0x114` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x74` | `0x80` | **`+0xc`** |
| `__TEXT.__swift5_capture` | `0x1ec` | `0x1f4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x88` | `0x90` | **`+0x8`** |

### Other Changes

```diff

-1.4.17.0.0
+1.4.18.0.0
+  - /System/Library/Frameworks/Accounts.framework/Accounts

-  Functions: 1554
-  Symbols:   652
-  CStrings:  57
+  Functions: 1653
+  Symbols:   684
+  CStrings:  58
Symbols:
+ _OBJC_CLASS_$_ACAccountStore
+ ___swift_closure_destructor.64Tm
+ ___swift_memcpy104_8
+ ___swift_memcpy128_8
+ ___swift_memcpy152_8
+ ___swift_memcpy96_8
+ _associated conformance 13InAppFeedback11SaltHistoryV10CodingKeys33_DDDBBA0DE5F505287650B1F9EB794FBFLLOSHAASQ
+ _associated conformance 13InAppFeedback11SaltHistoryV10CodingKeys33_DDDBBA0DE5F505287650B1F9EB794FBFLLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 13InAppFeedback11SaltHistoryV10CodingKeys33_DDDBBA0DE5F505287650B1F9EB794FBFLLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 13InAppFeedback11SaltHistoryVSHAASQ
+ _swift_release_x22
+ _swift_release_x26
+ _swift_release_x9
+ _swift_retain_x25
+ _swift_retain_x28
+ _symbolic SDySSSay_____GG 13InAppFeedback10SaltWindowV
+ _symbolic SDySS_____G 13InAppFeedback11AreaHoldoutV
+ _symbolic SS4salt______4fromt 10Foundation4DateV
+ _symbolic SSSg4salt______4fromt 10Foundation4DateV
+ _symbolic SS______t 13InAppFeedback11AreaHoldoutV
+ _symbolic SaySSGSg
+ _symbolic Say_____G 13InAppFeedback11SaltHistoryV
+ _symbolic Si6offset______4from_SS8areaSaltSSSg07holdoutD0t7elementt 10Foundation4DateV
+ _symbolic Si6offset______7elementt 13InAppFeedback10SaltWindowV
+ _symbolic _____ 13InAppFeedback10SaltWindowV
+ _symbolic _____ 13InAppFeedback11SaltHistoryV
+ _symbolic _____ 13InAppFeedback11SaltHistoryV10CodingKeys33_DDDBBA0DE5F505287650B1F9EB794FBFLLO
+ _symbolic _____4from_SS8areaSaltSSSg07holdoutC0t 10Foundation4DateV
+ _symbolic _____Sg 13InAppFeedback11SaltHistoryV
+ _symbolic _____ySS4salt______4fromtG s23_ContiguousArrayStorageC 10Foundation4DateV
+ _symbolic _____ySSSay_____GG s18_DictionaryStorageC 13InAppFeedback10SaltWindowV
+ _symbolic _____ySSSg4salt______4fromtG s23_ContiguousArrayStorageC 10Foundation4DateV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 13InAppFeedback11AreaHoldoutV
+ _symbolic _____y_____4from_SS8areaSaltSSSg07holdoutC0tG s23_ContiguousArrayStorageC 10Foundation4DateV
+ _symbolic _____y_____G s11_SetStorageC 13InAppFeedback9TreatmentV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 13InAppFeedback11SaltHistoryV10CodingKeys33_DDDBBA0DE5F505287650B1F9EB794FBFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 13InAppFeedback11SaltHistoryV10CodingKeys33_DDDBBA0DE5F505287650B1F9EB794FBFLLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 13InAppFeedback10SaltWindowV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 13InAppFeedback11SaltHistoryV
- ___swift_closure_destructor.61Tm
- ___swift_memcpy120_8
- ___swift_memcpy136_8
- ___swift_memcpy80_8
- ___swift_memcpy89_8
- _swift_retain_x8
- _symbolic _____y_____G s23_ContiguousArrayStorageC 13InAppFeedback11AreaHoldoutV
CStrings:
+ "resolveAllTreatments(provider:identifier:storefrontKey:timeout:)"
+ "storefronts"
- "resolveAllTreatments(provider:identifier:timeout:)"
```
