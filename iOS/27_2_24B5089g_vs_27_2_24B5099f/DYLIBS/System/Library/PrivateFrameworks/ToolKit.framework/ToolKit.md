## ToolKit

> `/System/Library/PrivateFrameworks/ToolKit.framework/ToolKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5079ec` | `0x509f38` | **`+0x254c`** |
| `__DATA.__bss` | `0x93dd0` | `0x949d0` | **`+0xc00`** |
| `__TEXT.__const` | `0x7b9a8` | `0x7bef8` | **`+0x550`** |
| `__AUTH_CONST.__const` | `0x2dd10` | `0x2df58` | **`+0x248`** |
| `__TEXT.__eh_frame` | `0x34d90` | `0x34f58` | **`+0x1c8`** |
| `__TEXT.__oslogstring` | `0x4e8c` | `0x502c` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0x1bce0` | `0x1bdf0` | **`+0x110`** |
| `__DATA.__data` | `0xfc90` | `0xfd90` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x14230` | `0x14314` | **`+0xe4`** |
| `__TEXT.__constg_swiftt` | `0xf168` | `0xf220` | **`+0xb8`** |
| `__TEXT.__swift5_typeref` | `0x14a20` | `0x14ad6` | **`+0xb6`** |
| `__TEXT.__cstring` | `0x9834` | `0x98e4` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x9947` | `0x99d7` | **`+0x90`** |
| `__AUTH.__data` | `0x2b00` | `0x2b60` | **`+0x60`** |
| `__TEXT.__swift5_proto` | `0x6f1c` | `0x6f7c` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x2a18` | `0x2a60` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x3fd4` | `0x3fa4` | **`-0x30`** |
| `__TEXT.__swift5_types` | `0x18ac` | `0x18c4` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2838` | `0x2848` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x348` | `0x338` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x12fe8` | `0x12fd8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xdb8` | `0xdc0` | **`+0x8`** |

### Other Changes

```diff

-5111.0.2.0.0
+5113.0.1.1.1

-  Functions: 46042
-  Symbols:   10383
-  CStrings:  1790
+  Functions: 46138
+  Symbols:   10406
+  CStrings:  1796
Symbols:
+ _OBJC_CLASS_$_LNUserIdentity
+ _associated conformance 7ToolKit0A8DatabaseC12ContentScopeOSHAASQ
+ _associated conformance 7ToolKit0A8DatabaseC21RemoteToolsVersionKeyV10CodingKeys33_CC8D17C906DF1313971A4F51583F6C3BLLOs0hG0AAs23CustomStringConvertible
+ _associated conformance 7ToolKit0A8DatabaseC21RemoteToolsVersionKeyV10CodingKeys33_CC8D17C906DF1313971A4F51583F6C3BLLOs0hG0AAs28CustomDebugStringConvertible
+ _associated conformance 7ToolKit0A8DatabaseC21RemoteToolsVersionKeyVAA0ac8MetadataG0AA5ValueAaFP_AA0achI0
+ _associated conformance 7ToolKit0A8DatabaseC21RemoteToolsVersionKeyVSHAASQ
+ _associated conformance 7ToolKit0A8DatabaseC31LastRemoteReconciliationDateKeyV10CodingKeys33_CC8D17C906DF1313971A4F51583F6C3BLLOs0iH0AAs23CustomStringConvertible
+ _associated conformance 7ToolKit0A8DatabaseC31LastRemoteReconciliationDateKeyV10CodingKeys33_CC8D17C906DF1313971A4F51583F6C3BLLOs0iH0AAs28CustomDebugStringConvertible
+ _associated conformance 7ToolKit0A8DatabaseC31LastRemoteReconciliationDateKeyVAA0ac8MetadataH0AA5ValueAaFP_AA0aciJ0
+ _associated conformance 7ToolKit0A8DatabaseC31LastRemoteReconciliationDateKeyVSHAASQ
+ _associated conformance 7ToolKit21EntityResolutionDepthOSHAASQ
+ _symbolic _____ 7ToolKit0A8DatabaseC12ContentScopeO
+ _symbolic _____ 7ToolKit0A8DatabaseC21RemoteToolsVersionKeyV
+ _symbolic _____ 7ToolKit0A8DatabaseC21RemoteToolsVersionKeyV10CodingKeys33_CC8D17C906DF1313971A4F51583F6C3BLLO
+ _symbolic _____ 7ToolKit0A8DatabaseC31LastRemoteReconciliationDateKeyV
+ _symbolic _____ 7ToolKit0A8DatabaseC31LastRemoteReconciliationDateKeyV10CodingKeys33_CC8D17C906DF1313971A4F51583F6C3BLLO
+ _symbolic _____ 7ToolKit21EntityResolutionDepthO
+ _symbolic _____m 7ToolKit0A8DatabaseC21RemoteToolsVersionKeyV
+ _symbolic _____y_____G 7ToolKit0A22DatabaseMetadataRecordV AA0aC0C21RemoteToolsVersionKeyV
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7ToolKit0D8DatabaseC21RemoteToolsVersionKeyV10CodingKeys33_CC8D17C906DF1313971A4F51583F6C3BLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7ToolKit0D8DatabaseC31LastRemoteReconciliationDateKeyV10CodingKeys33_CC8D17C906DF1313971A4F51583F6C3BLLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 7ToolKit0D29CascadeSharedIdentifierRecordV
+ _symbolic _____y_____GSg 7ToolKit0A22DatabaseMetadataRecordV AA0aC0C21RemoteToolsVersionKeyV
CStrings:
+ "Could not resolve the shared resources directory for the ToolKit data vault (CPSharedResourcesDirectory returned nil)."
+ "entityResolutionDepth"
+ "failed to bump RemoteToolsVersionKey after clearing remote tools; rolling this transaction back so remote content and its version stay consistent: %@"
+ "identifiersOnly"
+ "pull: failed to bump RemoteToolsVersionKey after reaping remote tools; rolling this transaction back so remote content and its version stay consistent — will retry on the next full pull: %@"
+ "pull: reaping %ld remote tool(s) no longer donated by any peer"
```
