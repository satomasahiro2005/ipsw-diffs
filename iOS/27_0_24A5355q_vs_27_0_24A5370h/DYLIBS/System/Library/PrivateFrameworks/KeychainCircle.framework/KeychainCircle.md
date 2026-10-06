## KeychainCircle

> `/System/Library/PrivateFrameworks/KeychainCircle.framework/KeychainCircle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28884` | `0x298f4` | **`+0x1070`** |
| `__TEXT.__cstring` | `0x3481` | `0x35a8` | **`+0x127`** |
| `__AUTH_CONST.__cfstring` | `0x3880` | `0x39a0` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0x11a0` | `0x1200` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1208` | `0x1250` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x838` | `0x840` | **`+0x8`** |

### Other Changes

```diff

-62426.0.0.0.4
+62460.0.22.0.0

-  Symbols:   1836
-  CStrings:  781
+  Symbols:   1846
+  CStrings:  790
Symbols:
+ __OctagonSignpostLogMetricDeltas
+ ___block_descriptor_104_e8_32s40bs48r_e17_v16?0"NSError"8lr48l8s32l8s40l8
+ ___block_descriptor_104_e8_32s40bs48r_e37_v28?0B8"NSDictionary"12"NSError"20lr48l8s32l8s40l8
+ ___block_descriptor_112_e8_32s40s48bs56r_e20_v20?0B8"NSError"12ls32l8r56l8s40l8s48l8
+ ___block_descriptor_112_e8_32s40s48bs56r_e29_v24?0"NSArray"8"NSError"16lr56l8s32l8s40l8s48l8
+ ___block_descriptor_120_e8_32s40s48bs56r64w_e28_v24?0"NSData"8"NSError"16lr56l8s32l8s40l8s48l8w64l8
+ ___block_descriptor_144_e8_32s40s48r56r64r72r80w_e17_v16?0"NSError"8ls32l8r48l8s40l8r56l8r64l8w80l8r72l8
+ ___block_descriptor_160_e8_32s40bs48r56r_e17_v16?0"NSError"8lr48l8r56l8s32l8s40l8
+ ___block_descriptor_176_e8_32s40s48bs56r64r72w_e20_v20?0B8"NSError"12lr56l8s32l8r64l8s40l8s48l8w72l8
+ ___block_descriptor_176_e8_32s40s48s56bs64r72r_e20_v20?0B8"NSError"12lr64l8s32l8r72l8s40l8s56l8s48l8
+ ___block_descriptor_192_e8_32s40s48s56bs64r72r80r88w_e28_v24?0"NSData"8"NSError"16lr64l8s32l8r72l8s40l8r80l8s48l8s56l8w88l8
+ ___block_descriptor_192_e8_32s40s48s56s64bs72r80r88w_e28_v24?0"NSData"8"NSError"16lr72l8s32l8s40l8s48l8r80l8s56l8s64l8w88l8
+ ___block_descriptor_96_e8_32bs40r_e17_v16?0"NSError"8lr40l8s32l8
+ _kSecurityRTCEventNameTDLDuplicateMIDRecord
+ _kSecurityRTCEventNameTDLDuplicateStableID
+ _kSecurityRTCEventNameTDLMembershipCheckFailed
+ _kSecurityRTCEventNameTDLMembershipMultipleRecords
+ _kSecurityRTCEventNameTDLSilentDrop
+ _kSecurityRTCEventNameTDLStableIDDivergenceDisallow
+ _kSecurityRTCFieldIsDemoAccount
+ _kSecurityRTCFieldLookupKeyType
+ _kSecurityRTCFieldRecordCount
- ___block_descriptor_112_e8_32s40s48bs56r64r72w_e20_v20?0B8"NSError"12lr56l8s32l8r64l8s40l8s48l8w72l8
- ___block_descriptor_112_e8_32s40s48r56r64r72r80w_e17_v16?0"NSError"8ls32l8r48l8s40l8r56l8r64l8w80l8r72l8
- ___block_descriptor_112_e8_32s40s48s56bs64r72r_e20_v20?0B8"NSError"12lr64l8s32l8r72l8s40l8s56l8s48l8
- ___block_descriptor_128_e8_32s40s48s56bs64r72r80r88w_e28_v24?0"NSData"8"NSError"16lr64l8s32l8r72l8s40l8r80l8s48l8s56l8w88l8
- ___block_descriptor_128_e8_32s40s48s56s64bs72r80r88w_e28_v24?0"NSData"8"NSError"16lr72l8s32l8s40l8s48l8r80l8s56l8s64l8w88l8
- ___block_descriptor_64_e8_32bs40r_e17_v16?0"NSError"8lr40l8s32l8
- ___block_descriptor_72_e8_32s40bs48r_e17_v16?0"NSError"8lr48l8s32l8s40l8
- ___block_descriptor_72_e8_32s40bs48r_e37_v28?0B8"NSDictionary"12"NSError"20lr48l8s32l8s40l8
- ___block_descriptor_80_e8_32s40s48bs56r_e20_v20?0B8"NSError"12ls32l8r56l8s40l8s48l8
- ___block_descriptor_80_e8_32s40s48bs56r_e29_v24?0"NSArray"8"NSError"16lr56l8s32l8s40l8s48l8
- ___block_descriptor_88_e8_32s40s48bs56r64w_e28_v24?0"NSData"8"NSError"16lr56l8s32l8s40l8s48l8w64l8
- ___block_descriptor_96_e8_32s40bs48r56r_e17_v16?0"NSError"8lr48l8r56l8s32l8s40l8
Functions:
~ -[KCPairingChannel initiatorFirstPacket:complete:] : 3624 -> 4052
~ -[KCPairingChannel initiatorSecondPacket:complete:] : 2244 -> 2392
~ ___51-[KCPairingChannel initiatorSecondPacket:complete:]_block_invoke : 652 -> 756
~ ___51-[KCPairingChannel initiatorSecondPacket:complete:]_block_invoke.224 : 1116 -> 1260
~ ___51-[KCPairingChannel initiatorSecondPacket:complete:]_block_invoke.225 : 440 -> 496
~ ___51-[KCPairingChannel initiatorSecondPacket:complete:]_block_invoke.227 : 440 -> 496
~ ___51-[KCPairingChannel initiatorSecondPacket:complete:]_block_invoke.229 : 440 -> 496
~ -[KCPairingChannel initiatorCompleteSecondPacketWithSOS:complete:] : 964 -> 1048
~ ___66-[KCPairingChannel initiatorCompleteSecondPacketWithSOS:complete:]_block_invoke : 368 -> 416
~ ___66-[KCPairingChannel initiatorCompleteSecondPacketWithSOS:complete:]_block_invoke.230 : 856 -> 916
~ -[KCPairingChannel join:voucher:eventS:setupPairingChannelSignPost:finishPairing:error:] : 784 -> 792
~ ___88-[KCPairingChannel join:voucher:eventS:setupPairingChannelSignPost:finishPairing:error:]_block_invoke : 2040 -> 2296
~ -[KCPairingChannel initiatorThirdPacket:complete:] : 3584 -> 4008
~ ___50-[KCPairingChannel initiatorThirdPacket:complete:]_block_invoke : 652 -> 756
~ ___50-[KCPairingChannel initiatorThirdPacket:complete:]_block_invoke.243 : 2572 -> 2852
~ -[KCPairingChannel initiatorFourthPacket:complete:] : 2100 -> 2232
~ ___51-[KCPairingChannel initiatorFourthPacket:complete:]_block_invoke.247 : 384 -> 440
~ ___51-[KCPairingChannel initiatorFourthPacket:complete:]_block_invoke.248 : 1264 -> 1376
~ -[KCPairingChannel acceptorFirstPacket:complete:] : 4248 -> 4596
~ ___49-[KCPairingChannel acceptorFirstPacket:complete:]_block_invoke.274 : 652 -> 756
~ ___49-[KCPairingChannel acceptorFirstPacket:complete:]_block_invoke.275 : 1884 -> 2096
~ ___49-[KCPairingChannel acceptorFirstPacket:complete:]_block_invoke.276 : 440 -> 496
~ ___49-[KCPairingChannel acceptorFirstPacket:complete:]_block_invoke.278 : 440 -> 496
~ ___49-[KCPairingChannel acceptorFirstPacket:complete:]_block_invoke.279 : 440 -> 496
~ -[KCPairingChannel acceptorSecondPacket:complete:] : 1888 -> 2076
~ ___50-[KCPairingChannel acceptorSecondPacket:complete:]_block_invoke : 652 -> 756
~ ___50-[KCPairingChannel acceptorSecondPacket:complete:]_block_invoke.283 : 1680 -> 1868
~ ___50-[KCPairingChannel acceptorSecondPacket:complete:]_block_invoke.284 : 440 -> 496
~ ___50-[KCPairingChannel acceptorSecondPacket:complete:]_block_invoke.286 : 440 -> 496
~ -[KCPairingChannel acceptorThirdPacket:complete:] : 1100 -> 1180
~ ___49-[KCPairingChannel acceptorThirdPacket:complete:]_block_invoke : 384 -> 440
~ ___49-[KCPairingChannel acceptorThirdPacket:complete:]_block_invoke.291 : 952 -> 1008
~ -[AAFAnalyticsEventSecurity initWithKeychainCircleMetrics:altDSID:flowID:deviceSessionID:eventName:testsAreEnabled:canSendMetrics:category:] : 864 -> 860
~ ___40-[AAFAnalyticsEventSecurity addMetrics:]_block_invoke : 316 -> 312
~ _CFStringCreateByTrimmingCharactersInSet : 696 -> 712
~ ___CFDictionaryCopyCompactDescription_block_invoke : 328 -> 336
~ ___CFDictionaryCopySuperCompactDescription_block_invoke : 504 -> 524
CStrings:
+ "com.apple.security.tdlDuplicateMIDRecord"
+ "com.apple.security.tdlDuplicateStableID"
+ "com.apple.security.tdlMembershipCheckFailed"
+ "com.apple.security.tdlMembershipMultipleRecords"
+ "com.apple.security.tdlSilentDrop"
+ "com.apple.security.tdlStableIDDivergenceDisallow"
+ "isDemoAccount"
+ "lookupKeyType"
+ "recordCount"
```
