## AppleThunderboltSAT

> `/System/Library/Extensions/AppleThunderboltSAT.kext/AppleThunderboltSAT`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x23744` | `0x23fe0` | **`+0x89c`** |
| `__TEXT.__cstring` | `0x10b31` | `0x10dcf` | **`+0x29e`** |
| `__TEXT_EXEC.__auth_stubs` | `0x540` | `0x570` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x2a0` | `0x2b8` | **`+0x18`** |
| `__DATA.__bss` | `0x28` | `0x3c` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`

### Other Changes

```diff

-109.0.0.0.1
-  Functions: 552
-  Symbols:   1106
-  CStrings:  1019
+112.0.0.0.0
+  Functions: 557
+  Symbols:   1117
+  CStrings:  1026
Symbols:
+ __Z20sat_push_msg_to_userPKcz
+ __Z22sat_clear_msgs_to_userv
+ __Z22sat_get_msg_to_user_atjR15sat_msg_to_user
+ __Z26sat_get_msgs_to_user_countR21sat_msg_to_user_count
+ __ZL14gSatMsgsToUser
+ __ZL17gSatMsgToUserLock
+ __ZL23gSatMsgsToUserTruncated
+ __ZN7OSArray12withCapacityEj
+ __ZNK23AppleThunderboltSATPort18getTBTRouterNumberEv
+ __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_809
+ __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_819
+ __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_883
+ _strlcpy
+ _vsnprintf
- __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_804
- __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_814
- __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_878
CStrings:
+ "1.0.101"
+ "112"
+ "21:03:53"
+ "Jun 30 2026"
+ "LinkDevice: routerID %d portID %d - remote ring mask is invalid, looks like sat-vsa=1 boot-arg missing on the capturing side"
+ "SATLinkDevice<%p>::activateInternal WARNING: looks like sat-vsa=1 boot-arg missing on the capturing side. routerID %d, portID %d, remote_tx_mask=%u, remote_rx_mask=%u"
+ "SATUserClient<%p>::externalMethod - kSAT_ClearMsgsToUser\n"
+ "SATUserClient<%p>::externalMethod - kSAT_GetMsgToUserByIndex - index = %llu\n"
+ "SATUserClient<%p>::externalMethod - kSAT_GetMsgToUserByIndex ERROR: sanitization check failed\n"
+ "SATUserClient<%p>::externalMethod - kSAT_GetMsgsToUserCount\n"
+ "SATUserClient<%p>::externalMethod - kSAT_GetMsgsToUserCount ERROR: sanitization check failed\n"
- "1.0.99"
- "109.0.0.0.1"
- "19:38:50"
- "Jun 18 2026"
```
