## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x290760` | `0x29103c` | **`+0x8dc`** |
| `__TEXT.__cstring` | `0x82e33` | `0x8300f` | **`+0x1dc`** |
| `__DATA_CONST.__const` | `0x210e8` | `0x21100` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x5fb8` | `0x5fd0` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__osclassinfo`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-1580.59.0.0.0
+1580.63.0.0.0

-  Functions: 14163
-  Symbols:   12051
-  CStrings:  13117
+  Functions: 14172
+  Symbols:   12055
+  CStrings:  13125
Symbols:
+ _ZN24AppleBCMWLANNANInterface24setNAN_MULTICAST_PEER_OPEP32apple80211_nan_multicast_peer_op
+ __ZN24AppleBCMWLANNANInterface24setNAN_MULTICAST_PEER_OPEP32apple80211_nan_multicast_peer_op
+ __ZThn112_N24AppleBCMWLANNANInterface24setNAN_MULTICAST_PEER_OPEP32apple80211_nan_multicast_peer_op
+ __ZThn128_N24AppleBCMWLANNANInterface24setNAN_MULTICAST_PEER_OPEP32apple80211_nan_multicast_peer_op
CStrings:
+ "\"AppleBCMWLANV3_driverkit-1580.63\""
+ "AppleBCMWLANV3_driverkit-1580.63"
+ "Debug: WL_NAN_CMD_CFG_SET_PEER_KEY (mcast_peer) bytestream: "
+ "Jul  1 2026 23:33:59"
+ "[dk] %s@%d:%s invalid operation %u\n"
+ "[dk] %s@%d:%s invalid peer count %u\n"
+ "[dk] %s@%d:%s: op=%u count=%u laddr=%02x:%02x:%02x:%02x:%02x:%02x mcast=%02x:%02x:%02x:%02x:%02x:%02x\n"
+ "[dk] %s@%d:ERROR: Unable to set NAN multicast peer, ret = %d\n"
+ "[dk] %s@%d:Failed to allocate fBackplane lock\n"
+ "setNAN_MULTICAST_PEER_OP"
+ "virtual int32_t AppleBCMWLANNANInterface::setNAN_MULTICAST_PEER_OP(apple80211_nan_multicast_peer_op_t *)"
- "\"AppleBCMWLANV3_driverkit-1580.59\""
- "AppleBCMWLANV3_driverkit-1580.59"
- "Jun 16 2026 21:46:18"
```
