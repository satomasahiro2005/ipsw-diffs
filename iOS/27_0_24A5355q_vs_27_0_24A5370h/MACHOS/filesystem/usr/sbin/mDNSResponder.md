## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x108410` | `0x1099d4` | **`+0x15c4`** |
| `__DATA_CONST.__const` | `0x62c8` | `0x6238` | **`-0x90`** |
| `__TEXT.__cstring` | `0x17912` | `0x179a2` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x20d66` | `0x20d1e` | **`-0x48`** |
| `__DATA.__bss` | `0x16e50` | `0x16e40` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x2fa0` | `0x2fb0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x17e0` | `0x17e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3066.0.0.502.1
+3085.0.0.0.1

-  Functions: 1869
-  Symbols:   4153
-  CStrings:  4757
+  Functions: 1868
+  Symbols:   4149
+  CStrings:  4753
Symbols:
+ GCC_except_table1248
+ GCC_except_table1254
+ GCC_except_table1417
+ GCC_except_table1600
+ GCC_except_table1831
+ GCC_except_table486
+ _dnssd_analytics_update_assist_discovery
+ _mDNSDisableInternalRedactionWithID
+ _mDNSEnableInternalRedaction
+ _mDNS_RedactedLogCategoriesEnableCount
+ _nw_resolver_config_get_oblivious_proxy_url
+ _os_variant_has_internal_content
+ _sDiscoverWin_0_1s
+ _sDiscoverWin_1_5s
+ _sDiscoverWin_5_15s
+ _sDiscoverWin_gt15s
+ _sPresenceDiscoverWin_0_1s
+ _sPresenceDiscoverWin_1_5s
+ _sPresenceDiscoverWin_5_15s
+ _sPresenceDiscoverWin_gt15s
+ _sPresence_Qhashes
+ _sPresence_Qhashes_MulticastWon
+ _sPresence_Qhashes_Unanswered
+ _sPresence_Qhashes_UnicastWon
+ _sPresence_SubscribedSecs
+ _sRevalidate_MulticastWon
+ _sRevalidate_UnicastWon
+ _unicast_assist_addr_state
- GCC_except_table1250
- GCC_except_table1256
- GCC_except_table1418
- GCC_except_table1601
- GCC_except_table1832
- GCC_except_table488
- _DNSQuestionNeedsSensitiveLogging
- _ResourceRecordGetRDataBytesPointer
- ____post_unicast_assist_presence_block_invoke
- _mDNSDisableSensitiveLoggingForQuestion
- _mDNSEnableSensitiveLoggingForQuestion
- _mDNS_SensitiveLoggingEnableCount
- _objc_retain_x10
- _sNonUnicastAssist_MulticastCount
- _sNonUnicastAssist_UnicastCount
- _sUAPresence_Count_addrs
- _sUAPresence_Count_addrs_invalid
- _sUAPresence_Count_assert
- _sUAPresence_Count_assert_addrs
- _sUAPresence_Count_assert_hashes
- _sUAPresence_Count_enabled
- _sUAPresence_Count_qhashes
- _sUAPresence_Count_qhashes_found_multicast
- _sUAPresence_Count_qhashes_found_unicast
- _sUAPresence_Count_qhashes_not_found
- _sUAPresence_Count_update
- _sUAPresence_Count_update_devices
- _sUAPresence_Count_update_devices_invalid
- _sUAPresence_Count_update_devices_missing
- _sUAPresence_Count_update_devices_old
- _sUnicastAssist_MulticastCount
- _sUnicastAssist_UnicastCount
CStrings:
+ "----    Unicast Assist Discovery Wins"
+ "----    Unicast Assist Discovery Wins (Presence-Seeded)"
+ "----    Unicast Assist Revalidation"
+ "Discover win 0-1s: %llu"
+ "Discover win 1-5s: %llu"
+ "Discover win 15s+: %llu"
+ "Discover win 5-15s: %llu"
+ "Multicast won: %llu"
+ "Presence discover win 0-1s: %llu"
+ "Presence discover win 1-5s: %llu"
+ "Presence discover win 15s+: %llu"
+ "Presence discover win 5-15s: %llu"
+ "Qhashes multicast won: %llu"
+ "Qhashes unanswered: %llu"
+ "Qhashes unicast won: %llu"
+ "Subscribed seconds: %llu"
+ "Unicast won: %llu"
+ "[Q%u] redacted logging disabled"
+ "[Q%u] redacted logging enable count decreased: %u"
+ "[Q%u] redacted logging enable count increased: %u"
+ "[Q%u] redacted logging enabled"
+ "discover_win_0_1s"
+ "discover_win_1_5s"
+ "discover_win_5_15s"
+ "discover_win_gt15s"
+ "mDNSResponder-3085.0.0.0.1"
+ "presence_discover_win_0_1s"
+ "presence_discover_win_1_5s"
+ "presence_discover_win_5_15s"
+ "presence_discover_win_gt15s"
+ "presence_qhashes"
+ "presence_qhashes_multicast_won"
+ "presence_qhashes_unanswered"
+ "presence_qhashes_unicast_won"
+ "presence_subscribed_secs"
+ "revalidate_multicast_won"
+ "revalidate_unicast_won"
- "----    Unicast Assist"
- "Addrs: %llu"
- "Assert addrs: %llu"
- "Assert hashes: %llu"
- "Asserts: %llu"
- "Assist Multicast: %llu"
- "Assist Unicast: %llu"
- "Enabled: %llu"
- "Invalid addrs: %llu"
- "Non-assist Multicast: %llu"
- "Non-assist Unicast: %llu"
- "Qhashes found via multicast: %llu"
- "Qhashes found via unicast: %llu"
- "Qhashes not found: %llu"
- "TSR"
- "Update devices invalid: %llu"
- "Update devices missing: %llu"
- "Update devices old: %llu"
- "Update devices: %llu"
- "Updates received: %llu"
- "[Q%u] sensitive logging disabled"
- "[Q%u] sensitive logging enable count decreased: %u"
- "[Q%u] sensitive logging enable count increased: %u"
- "[Q%u] sensitive logging enabled"
- "addrs"
- "addrs_invalid"
- "assert"
- "assert_addrs"
- "assert_hashes"
- "com.apple.mDNSResponder.unicastassist_presence"
- "com.apple.mDNSResponder.unicastassist_presence: Analytic not posted"
- "mDNSResponder-3066.0.0.502.1"
- "non_multicast"
- "non_unicast"
- "qhashes_found_multicast"
- "qhashes_found_unicast"
- "qhashes_not_found"
- "update_devices"
- "update_devices_invalid"
- "update_devices_missing"
- "update_devices_old"
```
