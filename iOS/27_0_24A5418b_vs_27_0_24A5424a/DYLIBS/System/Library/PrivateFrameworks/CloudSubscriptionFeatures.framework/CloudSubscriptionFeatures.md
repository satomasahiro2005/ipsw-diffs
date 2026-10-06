## CloudSubscriptionFeatures

> `/System/Library/PrivateFrameworks/CloudSubscriptionFeatures.framework/CloudSubscriptionFeatures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x114c0c` | `0x11db78` | **`+0x8f6c`** |
| `__TEXT.__eh_frame` | `0xaca8` | `0xb838` | **`+0xb90`** |
| `__AUTH_CONST.__const` | `0x93f0` | `0x9800` | **`+0x410`** |
| `__DATA.__bss` | `0xc640` | `0xc9c0` | **`+0x380`** |
| `__TEXT.__const` | `0xb874` | `0xbbd4` | **`+0x360`** |
| `__TEXT.__unwind_info` | `0x4170` | `0x4478` | **`+0x308`** |
| `__TEXT.__swift5_capture` | `0x16bc` | `0x18b4` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x749d` | `0x767d` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x4751` | `0x4861` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x2ab4` | `0x2b80` | **`+0xcc`** |
| `__TEXT.__swift_as_cont` | `0x878` | `0x940` | **`+0xc8`** |
| `__TEXT.__swift5_fieldmd` | `0x2e6c` | `0x2ed4` | **`+0x68`** |
| `__TEXT.__swift_as_entry` | `0x390` | `0x3e4` | **`+0x54`** |
| `__DATA.__data` | `0x1790` | `0x17e0` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x2bf4` | `0x2c44` | **`+0x50`** |
| `__TEXT.__swift_as_ret` | `0x3b0` | `0x3fc` | **`+0x4c`** |
| `__TEXT.__swift5_reflstr` | `0x2641` | `0x2681` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xe6c` | `0xea4` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x35a8` | `0x35d0` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x870` | `0x88c` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x1118` | `0x1130` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x438` | `0x428` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x938` | `0x948` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x1f90` | `0x1fa0` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0xf18` | `0xf28` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x570` | `0x578` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x364` | `0x36c` | **`+0x8`** |

### Other Changes

```diff

-301.24.0.29.0
+301.24.0.31.0

-  Functions: 4899
-  Symbols:   1809
-  CStrings:  957
+  Functions: 5052
+  Symbols:   1824
+  CStrings:  971
Symbols:
+ ___swift_closure_destructor.33Tm
+ ___swift_closure_destructor.72Tm
+ _associated conformance 25CloudSubscriptionFeatures23WaitlistMessageResponseV10CodingKeys33_982D898D1F78F2AC231FDFB8F991F47ALLOSHAASQ
+ _associated conformance 25CloudSubscriptionFeatures23WaitlistMessageResponseV10CodingKeys33_982D898D1F78F2AC231FDFB8F991F47ALLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 25CloudSubscriptionFeatures23WaitlistMessageResponseV10CodingKeys33_982D898D1F78F2AC231FDFB8F991F47ALLOs0G3KeyAAs28CustomDebugStringConvertible
+ _symbolic S2SSg______pIegHgozo_ s5ErrorP
+ _symbolic SSSgSo7NSErrorCSgIeggg_
+ _symbolic SSSg______pIeghHrzo_ s5ErrorP
+ _symbolic ScCySSSg______pG s5ErrorP
+ _symbolic ScTySSSg______pG s5ErrorP
+ _symbolic So8NSStringCSgSo7NSErrorCSgIeyByy_
+ _symbolic _____ 25CloudSubscriptionFeatures23WaitlistMessageResponseV
+ _symbolic _____ 25CloudSubscriptionFeatures23WaitlistMessageResponseV10CodingKeys33_982D898D1F78F2AC231FDFB8F991F47ALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 25CloudSubscriptionFeatures23WaitlistMessageResponseV10CodingKeys33_982D898D1F78F2AC231FDFB8F991F47ALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 25CloudSubscriptionFeatures23WaitlistMessageResponseV10CodingKeys33_982D898D1F78F2AC231FDFB8F991F47ALLO
+ _type_layout_string 25CloudSubscriptionFeatures23WaitlistMessageResponseV
- ___swift_closure_destructor.25Tm
CStrings:
+ "/v1/devices/{udId}/features/{featureKey}/waitlist/message"
+ "Failed to create %s URL from base: %s"
+ "Getting waitlist message for %{public}s"
+ "Starting network fetch for waitlist message for %{public}s"
+ "Unable to fetch wait time message for %{public}s: %{public}s"
+ "Using account bag baseURLString for %{public}s: %{public}s"
+ "Using hardcoded baseURL for %{public}s: %{public}s"
+ "Waitlist message response has showMessage true but no message to display. Hiding the message."
+ "WaitlistMessage_"
+ "device readiness"
+ "received %s response, hasMessage: %{bool}d, error: %s"
+ "waitlist message"
+ "waitlistMessage failed with error: %{public}s"
+ "waitlistMessage network fetch finished for %{public}s. Has message to display? %{bool,public}d"
+ "waitlistMessage(featureID:deviceCapabilities:)"
+ "waitlistMessage."
+ "waitlistMessage_"
- "Failed to create device readiness URL from base: %s"
- "Using account bag baseURLString for DR: %{public}s"
- "Using hardcoded baseURL for DR: %{public}s"
```
