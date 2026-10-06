## TrustedPeers

> `/System/Library/PrivateFrameworks/TrustedPeers.framework/TrustedPeers`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x341a8` | `0x34274` | **`+0xcc`** |
| `__TEXT.__oslogstring` | `0x1c7f` | `0x1cea` | **`+0x6b`** |
| `__TEXT.__gcc_except_tab` | `0xbf0` | `0xc1c` | **`+0x2c`** |
| `__TEXT.__unwind_info` | `0xba0` | `0xb80` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x3964` | `0x397c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1988` | `0x1998` | **`+0x10`** |

### Other Changes

```diff

-62426.0.0.0.4
+62460.0.22.0.0

-  Functions: 1238
-  Symbols:   2107
-  CStrings:  375
+  Functions: 1240
+  Symbols:   2111
+  CStrings:  377
Symbols:
+ -[TPModel dynamicInfoForJoiningPeerID:peerPermanentInfo:peerStableInfo:sponsorID:preapprovedKeys:signingKeyPair:currentMachineIDs:requiresTDLFetch:distrustEveryoneOnJoin:error:]
+ -[TPModel peerIDsThatTrustRecoveryKeys:canIntroducePeer:stableInfo:error:]
+ GCC_except_table1190
+ GCC_except_table1198
+ GCC_except_table131
+ GCC_except_table133
+ GCC_except_table136
+ GCC_except_table138
+ GCC_except_table145
+ GCC_except_table147
+ GCC_except_table159
+ GCC_except_table165
+ GCC_except_table168
+ GCC_except_table178
+ GCC_except_table181
+ GCC_except_table189
+ GCC_except_table195
+ GCC_except_table203
+ GCC_except_table210
+ GCC_except_table220
+ GCC_except_table229
+ GCC_except_table234
+ GCC_except_table306
+ _IsOctagonAuthenticatedRKJoinEnabled
+ __OctagonSignpostLogMetricDeltas
+ ___177-[TPModel dynamicInfoForJoiningPeerID:peerPermanentInfo:peerStableInfo:sponsorID:preapprovedKeys:signingKeyPair:currentMachineIDs:requiresTDLFetch:distrustEveryoneOnJoin:error:]_block_invoke
+ ___177-[TPModel dynamicInfoForJoiningPeerID:peerPermanentInfo:peerStableInfo:sponsorID:preapprovedKeys:signingKeyPair:currentMachineIDs:requiresTDLFetch:distrustEveryoneOnJoin:error:]_block_invoke_2
+ ___74-[TPModel peerIDsThatTrustRecoveryKeys:canIntroducePeer:stableInfo:error:]_block_invoke
+ ___block_descriptor_80_e8_v12?0B8l
- GCC_except_table1188
- GCC_except_table1196
- GCC_except_table130
- GCC_except_table132
- GCC_except_table135
- GCC_except_table137
- GCC_except_table144
- GCC_except_table146
- GCC_except_table158
- GCC_except_table163
- GCC_except_table166
- GCC_except_table176
- GCC_except_table179
- GCC_except_table187
- GCC_except_table193
- GCC_except_table197
- GCC_except_table206
- GCC_except_table212
- GCC_except_table227
- GCC_except_table230
- GCC_except_table304
- ___154-[TPModel dynamicInfoForJoiningPeerID:peerPermanentInfo:peerStableInfo:sponsorID:preapprovedKeys:signingKeyPair:currentMachineIDs:requiresTDLFetch:error:]_block_invoke
- ___154-[TPModel dynamicInfoForJoiningPeerID:peerPermanentInfo:peerStableInfo:sponsorID:preapprovedKeys:signingKeyPair:currentMachineIDs:requiresTDLFetch:error:]_block_invoke_2
- ___74-[TPModel peerIDThatTrustsRecoveryKeys:canIntroducePeer:stableInfo:error:]_block_invoke
- ___block_descriptor_48_e8_v12?0B8l
CStrings:
+ "Error determining possible sponsors that trust the RK: %{public}@"
+ "Error fetching trusted peers: %{public}@"
```
