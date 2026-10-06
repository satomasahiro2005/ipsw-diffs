## CoreODIEssentials

> `/System/Library/PrivateFrameworks/CoreODIEssentials.framework/CoreODIEssentials`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fa980` | `0x1fc820` | **`+0x1ea0`** |
| `__DATA.__bss` | `0x16e90` | `0x17190` | **`+0x300`** |
| `__AUTH_CONST.__const` | `0x10ab0` | `0x10cb0` | **`+0x200`** |
| `__TEXT.__const` | `0x26f50` | `0x270e0` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x14ba0` | `0x14cc8` | **`+0x128`** |
| `__TEXT.__cstring` | `0x12b1f` | `0x12c2f` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x7c90` | `0x7d70` | **`+0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x8eb8` | `0x8f78` | **`+0xc0`** |
| `__DATA.__data` | `0x21c8` | `0x2268` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0xb5d3` | `0xb633` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x5c40` | `0x5c9c` | **`+0x5c`** |
| `__TEXT.__swift5_typeref` | `0x4b6f` | `0x4ba7` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x58e0` | `0x5910` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xd44` | `0xd74` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x152c` | `0x1500` | **`-0x2c`** |
| `__DATA_CONST.__objc_selrefs` | `0xc20` | `0xc38` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xfec` | `0x1004` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x210` | `0x224` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x660` | `0x66c` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0xb0` | `0xb8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x68c` | `0x688` | **`-0x4`** |

### Other Changes

```diff

-27.0.52.0.0
+27.0.60.0.0

-  Functions: 8568
-  Symbols:   2977
-  CStrings:  1550
+  Functions: 8595
+  Symbols:   2996
+  CStrings:  1557
Symbols:
+ -[Lt10zus2DOk3OfFf authenticateMessage:completion:]
+ -[ODNServices authenticateMessage:withOptions:completion:]
+ GCC_except_table84
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ASServicing
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_qZgDzsH6tZxglfVB
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ASServicing
+ __OBJC_$_PROTOCOL_METHOD_TYPES_qZgDzsH6tZxglfVB
+ __OBJC_$_PROTOCOL_REFS_ASServicing
+ __OBJC_LABEL_PROTOCOL_$_ASServicing
+ __OBJC_LABEL_PROTOCOL_$_qZgDzsH6tZxglfVB
+ __OBJC_PROTOCOL_$_ASServicing
+ __OBJC_PROTOCOL_$_qZgDzsH6tZxglfVB
+ __OBJC_PROTOCOL_REFERENCE_$_qZgDzsH6tZxglfVB
+ ___51-[Lt10zus2DOk3OfFf authenticateMessage:completion:]_block_invoke
+ ___51-[Lt10zus2DOk3OfFf authenticateMessage:completion:]_block_invoke_2
+ ___51-[Lt10zus2DOk3OfFf authenticateMessage:completion:]_block_invoke_3
+ _associated conformance 17CoreODIEssentials18RateLimitedRequestV10CodingKeys33_3469A297348E547E97244CB42239FEE6LLOSHAASQ
+ _associated conformance 17CoreODIEssentials18RateLimitedRequestV10CodingKeys33_3469A297348E547E97244CB42239FEE6LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 17CoreODIEssentials18RateLimitedRequestV10CodingKeys33_3469A297348E547E97244CB42239FEE6LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _symbolic _____ 17CoreODIEssentials18RateLimitedRequestV
+ _symbolic _____ 17CoreODIEssentials18RateLimitedRequestV10CodingKeys33_3469A297348E547E97244CB42239FEE6LLO
+ _symbolic _____ 17CoreODIEssentials26DaemonInternalDefaultsKeysV
+ _symbolic _____y_____G s22KeyedEncodingContainerV 17CoreODIEssentials18RateLimitedRequestV10CodingKeys33_3469A297348E547E97244CB42239FEE6LLO
+ _type_layout_string 17CoreODIEssentials18RateLimitedRequestV
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_zClr2kpkWWOzbRnw
- __OBJC_$_PROTOCOL_METHOD_TYPES_zClr2kpkWWOzbRnw
- __OBJC_LABEL_PROTOCOL_$_zClr2kpkWWOzbRnw
- __OBJC_PROTOCOL_$_zClr2kpkWWOzbRnw
- __OBJC_PROTOCOL_REFERENCE_$_zClr2kpkWWOzbRnw
CStrings:
+ "Detected installType for auditToken: "
+ "X-Request-Signature"
+ "com.apple.idv.migrate"
+ "com.apple.odi.appStoreLoginUpdated"
+ "limitWindowSeconds"
+ "rate-limit-accounting"
+ "trustinsights.disableClientRateLimiting"
```
