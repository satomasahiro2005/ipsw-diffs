## ProtectedCloudStorage

> `/System/Library/PrivateFrameworks/ProtectedCloudStorage.framework/ProtectedCloudStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6cafc` | `0x6d568` | **`+0xa6c`** |
| `__TEXT.__oslogstring` | `0x3d98` | `0x3fd2` | **`+0x23a`** |
| `__TEXT.__gcc_except_tab` | `0x35e8` | `0x36e8` | **`+0x100`** |
| `__TEXT.__cstring` | `0xe06e` | `0xe0b4` | **`+0x46`** |
| `__AUTH_CONST.__cfstring` | `0x188e0` | `0x18920` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x3878` | `0x38a8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2e58` | `0x2e80` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x960` | `0x980` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2000` | `0x2018` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1898` | `0x18b0` | **`+0x18`** |
| `__DATA.__data` | `0x908` | `0x918` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1640` | `0x1650` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x10f8` | `0x1108` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xc50` | `0xc58` | **`+0x8`** |
| `__TEXT.__const` | `0x3c0` | `0x3c8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x29c` | `0x2a0` | **`+0x4`** |

### Other Changes

```diff

-1296.0.0.0.0
+1303.0.1.0.0

-  Functions: 2107
-  Symbols:   3633
-  CStrings:  3779
+  Functions: 2115
+  Symbols:   3646
+  CStrings:  3791
Symbols:
+ -[PCSMigrationState primaryRecordUpdateDict]
+ -[PCSMigrationState setPrimaryRecordUpdateDict:]
+ GCC_except_table138
+ GCC_except_table160
+ GCC_except_table161
+ GCC_except_table165
+ GCC_except_table168
+ GCC_except_table173
+ GCC_except_table183
+ GCC_except_table198
+ GCC_except_table222
+ GCC_except_table233
+ GCC_except_table245
+ GCC_except_table251
+ GCC_except_table256
+ GCC_except_table260
+ GCC_except_table268
+ _OBJC_IVAR_$_PCSMigrationState._primaryRecordUpdateDict
+ _PCSPublicIdentityCopyCompactPublicID
+ _PCSPublicIdentityIsCompact
+ ___PCSDBRRepairIdentities_block_invoke_2
+ ___block_descriptor_56_e8_32s40r_e40_v40?0q8q16"NSDictionary"24"NSError"32lr40l8s32l8
+ ___block_descriptor_64_e8_32s40r48r56r_e23_v32?0q8q16"NSError"24lr40l8r48l8r56l8s32l8
+ ___validateForRepair_block_invoke
+ _ccec_compact_export_pub
+ _kPCSMetadataiCDPDBRv2
+ _kPCSSettingDBRFailBlobGeneration
+ _validateForRepair
- GCC_except_table158
- GCC_except_table159
- GCC_except_table163
- GCC_except_table166
- GCC_except_table171
- GCC_except_table181
- GCC_except_table196
- GCC_except_table220
- GCC_except_table231
- GCC_except_table243
- GCC_except_table249
- GCC_except_table254
- GCC_except_table258
- GCC_except_table266
- ___block_descriptor_56_e8_32s40r48r_e40_v40?0q8q16"NSDictionary"24"NSError"32lr40l8r48l8s32l8
CStrings:
+ "Attempting to fetch escrow identity from keychain..."
+ "DBR-FailBlobGeneration"
+ "Injecting error into blob generation (due to %@/%@)"
+ "Missing iCDP, presumably using SA account"
+ "Repair: No DBR Primary Record to decode. Attempting to recreate"
+ "Repair: couldn't create new DBR records: %@"
+ "Repair: finished our attempt to re-create primary record"
+ "found identity %@ using compact representation"
+ "kPCSMetadataiCDPDBRv2"
+ "newly created identity set is %@"
+ "skipping repair after record re-creation because we are already in a good state"
+ "storeLRCHSM: Ensuring that we have LRC keys in memory before checking if LRC records need re-creation..."
+ "storeLRCHSM: OuterBlob from cached update dict: %@"
+ "storeLRCHSM: OuterBlob: %@"
+ "storeLRCHSM: no record in cached result, in need of repair."
+ "\xf0y"
- "Using SA account"
- "outerBlob = %@"
- "storeLRCHSM: LRC Record(s) need recreation, ensuring that we have LRC keys in memory..."
- "\xf0x"
```
