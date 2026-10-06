## com.apple.driver.AppleSEPCredentialManager

> `com.apple.driver.AppleSEPCredentialManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x4e214` | `0x4edf0` | **`+0xbdc`** |
| `__TEXT.__cstring` | `0x13342` | `0x13802` | **`+0x4c0`** |

### Other Changes

```diff

-949.0.13.0.0
-  Functions: 1019
+949.0.17.0.0
+  Functions: 1021

-  CStrings:  1981
+  CStrings:  2009
CStrings:
+ "!memcmp(state->cache.header.tag, (uint8_t[3])ACM_TRM_COMPACT_CACHE_TAG, sizeof(state->cache.header.tag))"
+ "!memcmp(state->policy.header.tag, (uint8_t[3])ACM_TRM_COMPACT_POLICY_TAG, sizeof(state->policy.header.tag))"
+ "%s: %s: *%s* replaced (size=%u->%u).\n"
+ "%s: %s: *acc-cache* saved (records=%u skipped=%u).\n"
+ "%s: %s: *config* saved (ver=%u size=%u).\n"
+ "%s: %s: *policy* saved (ver=%u size=%u).\n"
+ "%s: %s: [loaded] inSize=%u -> policyRead=%s configRead=NO accCacheRead=%s.\n"
+ "%s: %s: [replaced] bufSize=%u policyReplaced=%s configReplaced=%s.\n"
+ "%s: %s: [saved] outSize=%u policySaved=%s configSaved=%s accCacheSaved=%s.\n"
+ "*bufInOutSize <= bufCapacity"
+ "21:51:09"
+ "Aug  5 2026"
+ "TRMMultiState_ReplaceInBuffer"
+ "buf"
+ "bufInOutSize"
+ "copied == srcLen"
+ "multiStateVersion || guardedStateVersion"
+ "newTotalSize <= bufCapacity"
+ "numRecords <= kACMTRMLegacyAccessoryCache_CacheSize"
+ "originalSize == sizeof(acm_command_t)"
+ "payloadOffset + oldPayloadSize <= curSize"
+ "payloadPos <= bufLen"
+ "pos + sizeof(ItemTag) <= curSize"
+ "pos == curSize"
+ "readPos + itemTag.payloadSize <= inBufferSize"
+ "remaining >= cmdSize"
+ "remaining >= respSize"
+ "remaining >= sizeof(uint32_t)"
+ "replaceInMultiStateBuffer"
+ "sizeof(accCacheRecordItem) + accCacheRecordItem.hashLen + accCacheRecordItem.dataLen + accCacheRecordItem.groupLen <= itemTag.payloadSize"
+ "srcLen > 0"
+ "srcRec->dataLen <= kACMTRMLegacyAccessoryCache_MaxDataSize"
+ "srcRec->hashLen <= kACMTRMLegacyAccessoryCache_MaxHashSize"
- "%s: %s: [loaded] inSize=%u -> policyRead=%s configRead=%s accCacheRead=%s.\n"
- "21:20:00"
- "Jul 14 2026"
- "size > originalSize"
- "state->cache.body.numRecords <= kACMTRMLegacyAccessoryCache_CacheSize"
```
