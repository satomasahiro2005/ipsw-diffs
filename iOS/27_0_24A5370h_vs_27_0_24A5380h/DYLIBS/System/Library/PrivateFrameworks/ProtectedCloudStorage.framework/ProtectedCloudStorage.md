## ProtectedCloudStorage

> `/System/Library/PrivateFrameworks/ProtectedCloudStorage.framework/ProtectedCloudStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `0x2e0` | `0x13a8` | **`+0x10c8`** |
| `__DATA_DIRTY.__data` | `0x1108` | `0x40` | **`-0x10c8`** |
| `__TEXT.__text` | `0x6d568` | `0x6ddc8` | **`+0x860`** |
| `__AUTH.__objc_data` | `0x280` | `0x370` | **`+0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x870` | `0x780` | **`-0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x36e8` | `0x3630` | **`-0xb8`** |
| `__DATA_CONST.__const` | `0x2e80` | `0x2f20` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x3fd2` | `0x4024` | **`+0x52`** |
| `__AUTH_CONST.__const` | `0x980` | `0x9a0` | **`+0x20`** |
| `__DATA.__bss` | `0x388` | `0x3a8` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x98` | `0x78` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x18b0` | `0x18d0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x678` | `0x688` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2018` | `0x2028` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1650` | `0x1658` | **`+0x8`** |

### Other Changes

```diff

-1303.0.1.0.0
+1303.0.3.0.0

-  Functions: 2115
-  Symbols:   3646
-  CStrings:  3791
+  Functions: 2125
+  Symbols:   3659
+  CStrings:  3795
Symbols:
+ +[PCSAccountsModel inducedFailureEnabled:]
+ _PCSDBRGetWrappingKey
+ _PCSDBRRepairWrappingKeyFromEscrowIdentity
+ _PCSDBRRepairWrappingKeyFromEscrowIdentityOuterBlob
+ __DeleteWrappingKeyAndFail
+ __ValidateInnerBlob
+ ___PCSDBRGetWrappingKey_block_invoke
+ ___PCSDBRRepairWrappingKeyFromEscrowIdentityOuterBlob_block_invoke
+ ___PCSDBRUnwrapKeys_block_invoke_2
+ ____DeleteWrappingKeyAndFail_block_invoke
+ ____ValidateInnerBlob_block_invoke
+ ____ValidateInnerBlob_block_invoke_2
+ ___block_descriptor_48_e8_32s40bs_e61_v48?0"NSData"8"NSData"16"NSData"24"NSData"32"NSError"40ls32l8s40l8
+ ___block_descriptor_56_e8_32s40r48r_e23_v32?0q8q16"NSError"24lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32s40s48bs_e34_v40?0"NSData"8q16q24"NSError"32ls48l8s32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e61_v48?0"NSData"8"NSData"16"NSData"24"NSData"32"NSError"40ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48r56r64r_e34_v40?0"NSData"8q16q24"NSError"32lr48l8r56l8r64l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40s48r56r64r_e34_v40?0"NSData"8q16q24"NSError"32lr48l8s32l8r56l8s40l8r64l8
- __PCSDBRGetWrappingKey
- ____PCSDBRGetWrappingKey_block_invoke
- ____PCSDBRRepairWrappingKeyFromEscrowIdentity_block_invoke
- ___block_descriptor_56_e8_32r40r48r_e34_v40?0"NSData"8q16q24"NSError"32lr32l8r40l8r48l8
- ___block_descriptor_64_e8_32s40r48r56r_e34_v40?0"NSData"8q16q24"NSError"32lr40l8r48l8r56l8s32l8
CStrings:
+ "Failure %@ induced (defaults %@/%@)"
+ "PCSIdentityGenerateBlobForPasswordChange"
+ "error while attempting to get wrapping key: %@"
+ "failed to unwrap inner blob: %@"
+ "failed to unwrap inner blob: %@, retrying"
+ "unwrapped inner blob"
- "Disallowing repair with escrow identity operation (due to %@/%@)"
- "error while attempting to repair wrapping key using escrow identity: %@"
```
