## icloudmailagent

> `/usr/libexec/icloudmailagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42d48` | `0x42eb8` | **`+0x170`** |
| `__TEXT.__objc_stubs` | `0xb60` | `0xbe0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x805` | `0x845` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x1697` | `0x16d7` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x1718` | `0x1750` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x4f0` | `0x510` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x580` | `0x588` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2027.1.1.0.0
+2027.1.2.0.0

-  Functions: 1243
-  Symbols:   3613
-  CStrings:  503
+  Functions: 1244
+  Symbols:   3619
+  CStrings:  508
Symbols:
+ _$s15icloudmailagent10APIManagerC40purgeCachedAuthenticatedRequestsIfNeeded33_D65B718F5C28AC3F7B0CC41A5A0186BCLLyyFZTf4d_n
+ _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_s17_NativeDictionaryVySSSo8NSNumberCG_s5NeverOTg506$ss13_ab8V013withd36B08capacity4bodyxSi_xABq_YKXEtq_YKs5i9R_r0_lFZxs12_YKXEfU_s17_kl7VySSSo8m5CG_s5N4OTG5ABq_xRi_zRi0_zRi__Ri0__r0_lyApNIsgyrzr_Tf1nc_n06$ss17_kl47V6filteryAByxq_GSbx3key_q_5valuet_tqd__YKXEqd__ui12Rd__lFADs13_ab5Vqd__x8U_SS_So8m3Cs5N4OTG5ANxq_Sbq0_Ri_zRi0_zRi__Ri0__Ri_0_Ri0_0_r1_lySSAmPIsgnndzr_Tf1nc_n
+ _OBJC_CLASS_$_NSURLCache
+ _objc_msgSend$removeAllCachedResponses
+ _objc_msgSend$setRequestCachePolicy:
+ _objc_msgSend$setURLCache:
+ _objc_msgSend$sharedURLCache
- _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_s17_NativeDictionaryVySSSo8NSNumberCG_s5NeverOTg506$ss17_kl51V6filteryAByxq_GSbx3key_q_5valuet_tqd__YKXEqd__YKs5i12Rd__lFADs13_ab18Vqd__YKXEfU_SS_So8m3Cs5N4OTG5ANxq_Sbq0_Ri_zRi0_zRi__Ri0__Ri_0_Ri0_0_r1_lySSAmPIsgnndzr_Tf1nc_n
CStrings:
+ "com.apple.icloudmailagent.didPurgeCachedAuthenticatedRequests"
+ "removeAllCachedResponses"
+ "setRequestCachePolicy:"
+ "setURLCache:"
+ "sharedURLCache"
```
