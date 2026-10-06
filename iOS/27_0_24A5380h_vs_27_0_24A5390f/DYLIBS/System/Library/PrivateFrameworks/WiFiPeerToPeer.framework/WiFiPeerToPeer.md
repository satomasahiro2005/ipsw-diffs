## WiFiPeerToPeer

> `/System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/WiFiPeerToPeer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f2ec` | `0x3ff34` | **`+0xc48`** |
| `__AUTH_CONST.__objc_const` | `0x9b88` | `0x9ef8` | **`+0x370`** |
| `__TEXT.__cstring` | `0x9780` | `0x9969` | **`+0x1e9`** |
| `__TEXT.__objc_methlist` | `0x54a4` | `0x565c` | **`+0x1b8`** |
| `__AUTH_CONST.__cfstring` | `0x6a80` | `0x6ba0` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x48` | `0xe8` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2238` | `0x22c8` | **`+0x90`** |
| `__DATA.__data` | `0xc80` | `0xce0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xf60` | `0xfa8` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x13e8` | `0x1410` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x4a8` | `0x4c8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x724` | `0x744` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x328` | `0x348` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x260` | `0x270` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x240` | `0x250` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x70` | `0x80` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x100` | `0x108` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xd0` | `0xd8` | **`+0x8`** |

### Other Changes

```diff

-885.69.4.1.0
+885.77.0.0.0

-  Functions: 1722
-  Symbols:   3395
-  CStrings:  1183
+  Functions: 1754
+  Symbols:   3463
+  CStrings:  1194
Symbols:
+ +[WiFiAwarePairingPasswordVoucher supportsSecureCoding]
+ -[WiFiAwarePairingConfig passwordVoucherToken]
+ -[WiFiAwarePairingConfig setPasswordVoucherToken:]
+ -[WiFiAwarePairingPasswordVoucher .cxx_destruct]
+ -[WiFiAwarePairingPasswordVoucher copyWithZone:]
+ -[WiFiAwarePairingPasswordVoucher description]
+ -[WiFiAwarePairingPasswordVoucher encodeWithCoder:]
+ -[WiFiAwarePairingPasswordVoucher expiration]
+ -[WiFiAwarePairingPasswordVoucher initWithCoder:]
+ -[WiFiAwarePairingPasswordVoucher initWithToken:pairingMode:password:usageCount:expiration:]
+ -[WiFiAwarePairingPasswordVoucher pairingMode]
+ -[WiFiAwarePairingPasswordVoucher password]
+ -[WiFiAwarePairingPasswordVoucher setExpiration:]
+ -[WiFiAwarePairingPasswordVoucher setPairingMode:]
+ -[WiFiAwarePairingPasswordVoucher setPassword:]
+ -[WiFiAwarePairingPasswordVoucher setToken:]
+ -[WiFiAwarePairingPasswordVoucher setUsageCount:]
+ -[WiFiAwarePairingPasswordVoucher token]
+ -[WiFiAwarePairingPasswordVoucher usageCount]
+ -[WiFiAwarePairingPasswordVoucherStore .cxx_destruct]
+ -[WiFiAwarePairingPasswordVoucherStore activate]
+ -[WiFiAwarePairingPasswordVoucherStore deactivate]
+ -[WiFiAwarePairingPasswordVoucherStore generateVoucherForPairingMode:completionHandler:]
+ -[WiFiAwarePairingPasswordVoucherStore init]
+ -[WiFiAwarePairingPasswordVoucherStore remoteObjectInterface]
+ -[WiFiAwarePairingPasswordVoucherStore startConnectionUsingProxy:completionHandler:]
+ -[WiFiAwareStateMonitor realtimeModeUpdatedHandler]
+ -[WiFiAwareStateMonitor setRealtimeModeUpdatedHandler:]
+ -[WiFiAwareStateMonitor updatedNANRealtimeMode:]
+ -[WiFiP2PNANStateMonitor updatedNANRealtimeMode:]
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_NSTimeZone
+ _OBJC_CLASS_$_WiFiAwarePairingPasswordVoucher
+ _OBJC_CLASS_$_WiFiAwarePairingPasswordVoucherStore
+ _OBJC_IVAR_$_WiFiAwarePairingConfig._passwordVoucherToken
+ _OBJC_IVAR_$_WiFiAwarePairingPasswordVoucher._expiration
+ _OBJC_IVAR_$_WiFiAwarePairingPasswordVoucher._pairingMode
+ _OBJC_IVAR_$_WiFiAwarePairingPasswordVoucher._password
+ _OBJC_IVAR_$_WiFiAwarePairingPasswordVoucher._token
+ _OBJC_IVAR_$_WiFiAwarePairingPasswordVoucher._usageCount
+ _OBJC_IVAR_$_WiFiAwarePairingPasswordVoucherStore._xpcConnection
+ _OBJC_IVAR_$_WiFiAwareStateMonitor._realtimeModeUpdatedHandler
+ _OBJC_METACLASS_$_WiFiAwarePairingPasswordVoucher
+ _OBJC_METACLASS_$_WiFiAwarePairingPasswordVoucherStore
+ __OBJC_$_CLASS_METHODS_WiFiAwarePairingPasswordVoucher
+ __OBJC_$_CLASS_PROP_LIST_WiFiAwarePairingPasswordVoucher
+ __OBJC_$_INSTANCE_METHODS_WiFiAwarePairingPasswordVoucher
+ __OBJC_$_INSTANCE_METHODS_WiFiAwarePairingPasswordVoucherStore
+ __OBJC_$_INSTANCE_VARIABLES_WiFiAwarePairingPasswordVoucher
+ __OBJC_$_INSTANCE_VARIABLES_WiFiAwarePairingPasswordVoucherStore
+ __OBJC_$_PROP_LIST_WiFiAwarePairingPasswordVoucher
+ __OBJC_$_PROP_LIST_WiFiAwarePairingPasswordVoucherStore
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_WiFiP2PNANStateMonitorXPCDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_WiFiAwarePairingPasswordXPC
+ __OBJC_$_PROTOCOL_METHOD_TYPES_WiFiAwarePairingPasswordXPC
+ __OBJC_$_PROTOCOL_REFS_WiFiAwarePairingPasswordXPC
+ __OBJC_CLASS_PROTOCOLS_$_WiFiAwarePairingPasswordVoucher
+ __OBJC_CLASS_PROTOCOLS_$_WiFiAwarePairingPasswordVoucherStore
+ __OBJC_CLASS_RO_$_WiFiAwarePairingPasswordVoucher
+ __OBJC_CLASS_RO_$_WiFiAwarePairingPasswordVoucherStore
+ __OBJC_LABEL_PROTOCOL_$_WiFiAwarePairingPasswordXPC
+ __OBJC_METACLASS_RO_$_WiFiAwarePairingPasswordVoucher
+ __OBJC_METACLASS_RO_$_WiFiAwarePairingPasswordVoucherStore
+ __OBJC_PROTOCOL_$_WiFiAwarePairingPasswordXPC
+ __OBJC_PROTOCOL_REFERENCE_$_WiFiAwarePairingPasswordXPC
+ ___46-[WiFiAwarePairingPasswordVoucher description]_block_invoke
+ ___88-[WiFiAwarePairingPasswordVoucherStore generateVoucherForPairingMode:completionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32bs_e39_v16?0"<WiFiAwarePairingPasswordXPC>"8ls32l8
CStrings:
+ "(nil)"
+ "<%@: %p> pairingMode=%@, pairingMetadata=%@, pairSetupMode=%@, userID=%u, passwordVoucherToken=%@"
+ "<%@: %p> token=%@, pairingMode=%@, password=%@, usageCount=%lu, expiration=%@>"
+ "WiFiAwarePairingConfig.passwordVoucherToken"
+ "WiFiAwarePairingPasswordVoucher.expiration"
+ "WiFiAwarePairingPasswordVoucher.pairingMode"
+ "WiFiAwarePairingPasswordVoucher.password"
+ "WiFiAwarePairingPasswordVoucher.token"
+ "WiFiAwarePairingPasswordVoucher.usageCount"
+ "com.apple.wifip2p.WiFiAwarePairingPasswordVoucherStore"
+ "v16@?0@\"<WiFiAwarePairingPasswordXPC>\"8"
+ "yyyy-MM-dd HH:mm:ss zzz"
- "<%@: %p> pairingMode=%@, pairingMetadata=%@, pairSetupMode=%@, userID=%u"
```
