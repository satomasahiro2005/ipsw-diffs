## BusinessChatService

> `/System/Library/PrivateFrameworks/BusinessChatService.framework/BusinessChatService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d21c` | `0x6ddb8` | **`+0xb9c`** |
| `__TEXT.__gcc_except_tab` | `0x650` | `0x728` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x4f4c` | `0x4fe7` | **`+0x9b`** |
| `__DATA_CONST.__const` | `0x1d00` | `0x1d50` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xfdb0` | `0xfdd8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x795c` | `0x797c` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1548` | `0x1560` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2778` | `0x2788` | **`+0x10`** |

### Other Changes

```diff

-30123.30.6.2.1
+30123.31.8.11.3

-  Functions: 2384
-  Symbols:   4898
-  CStrings:  1319
+  Functions: 2388
+  Symbols:   4904
+  CStrings:  1321
Symbols:
+ -[BCSBusinessEmailItemIdentifier itemIdentifiers]
+ -[BCSBusinessLookupResult initWithHasBusiness:matchingTruncatedHash:itemIdentifier:config:]
+ GCC_except_table100
+ GCC_except_table71
+ GCC_except_table75
+ GCC_except_table82
+ ___block_descriptor_48_e8_32r40r_e54_B32?0"<BCSItemIdentifying>"8"BCSItem"16"NSError"24lr32l8r40l8
+ ___block_descriptor_56_e8_32bs40r48r_e17_v16?0"NSError"8lr40l8r48l8s32l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s64l8s40l8s48l8s56l8
- GCC_except_table80
- GCC_except_table98
- ___block_descriptor_64_e8_32s40s48s56bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s56l8s40l8s48l8
CStrings:
+ "%s Expected shardItem that conforms to BCSFilterShardItemProtocol protocol but got %@"
+ "Extracting all matching shards for %lu keys for multi-key identifier"
```
