## StoreKit

> `/System/Library/Frameworks/StoreKit.framework/StoreKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e1be0` | `0x1e9e78` | **`+0x8298`** |
| `__DATA_DIRTY.__bss` | `0x740` | `0x3648` | **`+0x2f08`** |
| `__DATA.__bss` | `0x277b0` | `0x24930` | **`-0x2e80`** |
| `__DATA_DIRTY.__data` | `0x6d8` | `0x1db0` | **`+0x16d8`** |
| `__AUTH_CONST.__const` | `0x168c0` | `0x17590` | **`+0xcd0`** |
| `__TEXT.__eh_frame` | `0x10e30` | `0x11a38` | **`+0xc08`** |
| `__AUTH.__data` | `0x3348` | `0x27f0` | **`-0xb58`** |
| `__DATA.__data` | `0x7050` | `0x6680` | **`-0x9d0`** |
| `__AUTH_CONST.__objc_const` | `0x16600` | `0x16d10` | **`+0x710`** |
| `__TEXT.__swift5_capture` | `0x33d0` | `0x3a3c` | **`+0x66c`** |
| `__TEXT.__swift5_typeref` | `0x5cac` | `0x627a` | **`+0x5ce`** |
| `__TEXT.__const` | `0x18084` | `0x182f4` | **`+0x270`** |
| `__AUTH.__objc_data` | `0x2450` | `0x21e8` | **`-0x268`** |
| `__DATA_DIRTY.__objc_data` | `0x370` | `0x5d8` | **`+0x268`** |
| `__TEXT.__unwind_info` | `0x95a8` | `0x97e8` | **`+0x240`** |
| `__TEXT.__swift_as_cont` | `0x112c` | `0x10c0` | **`-0x6c`** |
| `__TEXT.__swift_as_entry` | `0x67c` | `0x6d8` | **`+0x5c`** |
| `__DATA.__common` | `0xb0` | `0x60` | **`-0x50`** |
| `__DATA_DIRTY.__common` | `0x28` | `0x78` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x4564` | `0x458c` | **`+0x28`** |
| `__TEXT.__cstring` | `0x84a1` | `0x84c1` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x3af4` | `0x3b04` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x5788` | `0x5794` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x71c` | `0x728` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1998` | `0x19a0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xb78` | `0xb80` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1540` | `0x1544` | **`+0x4`** |

### Other Changes

```diff

-816.0.34.0.0
+816.0.38.0.0

-  Functions: 15375
-  Symbols:   7107
-  CStrings:  1370
+  Functions: 15437
+  Symbols:   7167
+  CStrings:  1371
Symbols:
+ _OUTLINED_FUNCTION_593
+ __DATA__TtC8StoreKitP33_78258BA0158490785E5A10CC788EA55A16DaemonConnection
+ __IVARS__TtC8StoreKitP33_78258BA0158490785E5A10CC788EA55A16DaemonConnection
+ __METACLASS_DATA__TtC8StoreKitP33_78258BA0158490785E5A10CC788EA55A16DaemonConnection
+ ___swift_closure_destructor.10Tm
+ ___swift_closure_destructor.164Tm
+ ___swift_closure_destructor.184Tm
+ ___swift_closure_destructor.18Tm
+ ___swift_closure_destructor.208Tm
+ ___swift_closure_destructor.33Tm
+ ___swift_closure_destructor.36Tm
+ ___swift_closure_destructor.47Tm
+ ___swift_closure_destructor.63Tm
+ ___swift_closure_destructor.76Tm
+ ___swift_closure_destructor.97Tm
+ ___unnamed_6
+ _swift_task_localValuePop
+ _swift_task_localValuePush
+ _symbolic So15NSXPCConnectionCSg
+ _symbolic _____ 8StoreKit16DaemonConnection33_78258BA0158490785E5A10CC788EA55ALLC
+ _symbolic _____SgXw 8StoreKit16DaemonConnection33_78258BA0158490785E5A10CC788EA55ALLC
+ _symbolic _____SgXwz_Xx 8StoreKit16DaemonConnection33_78258BA0158490785E5A10CC788EA55ALLC
+ _symbolic _____XDXMT 8StoreKit16DaemonConnection33_78258BA0158490785E5A10CC788EA55ALLC
+ _symbolic ______pSay_____GSg______pSgIeghng_Iegng_ So22ExternalGatewayServiceP 10Foundation3URLV s5ErrorP
+ _symbolic ______pScCySay_____G______pGIegnn_ So22ExternalGatewayServiceP 10Foundation3URLV s5ErrorP
+ _symbolic ______pScCy___________pGIegnn_ So13PolicyServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______pScCy___________pGIegnn_ So14PaymentServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______pScCy___________pGIegnn_ So16SKAccountServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______pScCy___________pGIegnn_ So17StorefrontServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______pScCy___________pGIegnn_ So19InAppBindingServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______pScCy___________pGIegnn_ So21OctaneServiceProtocolP 10Foundation4DataV s5ErrorP
+ _symbolic ______pScCy___________pGIegnn_ So21PurchaseIntentServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______pScCy___________pGIegnn_ So22ExternalGatewayServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______pScCy___________pGIegnn_ So22PartnerReferralServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______pScCyyt______pGIegnn_ So13ReviewServiceP s5ErrorP
+ _symbolic ______pScCyyt______pGIegnn_ So14PaymentServiceP s5ErrorP
+ _symbolic ______pScCyyt______pGIegnn_ So14ProductServiceP s5ErrorP
+ _symbolic ______pScCyyt______pGIegnn_ So15OverrideServiceP s5ErrorP
+ _symbolic ______pScCyyt______pGIegnn_ So19InAppBindingServiceP s5ErrorP
+ _symbolic ______pScCyyt______pGIegnn_ So21PurchaseIntentServiceP s5ErrorP
+ _symbolic ______pScCyyt______pGIegnn_ So22PartnerReferralServiceP s5ErrorP
+ _symbolic ______pScCyyt______pGIegnn_ So23TransactionCacheServiceP s5ErrorP
+ _symbolic ______p_____ABSg______pSgIeghng_Iegngg_ So13PolicyServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____ABSg______pSgIeghng_Iegngg_ So14PaymentServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____ABSg______pSgIeghng_Iegngg_ So16SKAccountServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____ABSg______pSgIeghng_Iegngg_ So17StorefrontServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____ABSg______pSgIeghng_Iegngg_ So19InAppBindingServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____ABSg______pSgIeghng_Iegngg_ So21OctaneServiceProtocolP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____ABSg______pSgIeghng_Iegngg_ So21PurchaseIntentServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____ABSg______pSgIeghng_Iegngg_ So22ExternalGatewayServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____Sg______pSgIeghng_Iegng_ So21OctaneServiceProtocolP 10Foundation4DataV s5ErrorP
+ _symbolic ______p_____Sg______pSgIeghng_Iegng_ So22PartnerReferralServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p___________pSgIeghg_Iegngg_ So13ReviewServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p___________pSgIeghg_Iegngg_ So14PaymentServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p___________pSgIeghg_Iegngg_ So14ProductServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p___________pSgIeghg_Iegngg_ So15OverrideServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p___________pSgIeghg_Iegngg_ So19InAppBindingServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p___________pSgIeghg_Iegngg_ So21PurchaseIntentServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p___________pSgIeghg_Iegngg_ So23TransactionCacheServiceP 10Foundation4DataV s5ErrorP
+ _symbolic ______p______pSgIeghg_Iegng_ So21PurchaseIntentServiceP s5ErrorP
+ _symbolic ______p______pSgIeghg_Iegng_ So22PartnerReferralServiceP s5ErrorP
+ _symbolic _____y______pG 8StoreKit23ClientServiceConnectionV So010StorefrontD0P
+ _symbolic _____y______pG 8StoreKit23ClientServiceConnectionV So012InAppBindingD0P
+ _symbolic _____y______pG 8StoreKit23ClientServiceConnectionV So014PurchaseIntentD0P
+ _symbolic _____y______pG 8StoreKit23ClientServiceConnectionV So015ExternalGatewayD0P
+ _symbolic _____y______pG 8StoreKit23ClientServiceConnectionV So015PartnerReferralD0P
+ _symbolic _____y______pG 8StoreKit23ClientServiceConnectionV So06OctaneD8ProtocolP
+ _symbolic _____y______pG 8StoreKit23ClientServiceConnectionV So06PolicyD0P
+ _symbolic _____y______pG 8StoreKit23ClientServiceConnectionV So06ReviewD0P
+ _symbolic _____y______pG 8StoreKit23ClientServiceConnectionV So07PaymentD0P
+ _symbolic _____y______pG 8StoreKit23ClientServiceConnectionV So08OverrideD0P
+ _symbolic _____y______pG 8StoreKit23ClientServiceConnectionV So09SKAccountD0P
- __DATA__TtC8StoreKitP33_78258BA0158490785E5A10CC788EA55A13XPCConnection
- __IVARS__TtC8StoreKitP33_78258BA0158490785E5A10CC788EA55A13XPCConnection
- __METACLASS_DATA__TtC8StoreKitP33_78258BA0158490785E5A10CC788EA55A13XPCConnection
- ___swift_closure_destructor.112Tm
- ___swift_closure_destructor.159Tm
- ___swift_closure_destructor.32Tm
- ___swift_closure_destructor.46Tm
- ___swift_closure_destructor.60Tm
- _symbolic So15NSXPCConnectionC
- _symbolic _____ 8StoreKit13XPCConnection33_78258BA0158490785E5A10CC788EA55ALLC
- _symbolic _____XDXMT 8StoreKit13XPCConnection33_78258BA0158490785E5A10CC788EA55ALLC
- _symbolic _____y_____G 8StoreKit11WeakFactoryC AA13XPCConnection33_78258BA0158490785E5A10CC788EA55ALLC
CStrings:
+ "23:17:36"
+ "AMSUIEngagementTaskErrorDomain"
+ "Jun 27 2026"
- "10:00:23"
- "Jun 13 2026"
```
