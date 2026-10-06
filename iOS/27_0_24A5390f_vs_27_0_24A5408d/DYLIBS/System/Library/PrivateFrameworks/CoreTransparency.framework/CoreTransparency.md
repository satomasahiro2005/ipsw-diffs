## CoreTransparency

> `/System/Library/PrivateFrameworks/CoreTransparency.framework/CoreTransparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48e20` | `0x4ebb8` | **`+0x5d98`** |
| `__TEXT.__const` | `0x73b4` | `0x7c04` | **`+0x850`** |
| `__TEXT.__swift5_reflstr` | `0x22c4` | `0x29c4` | **`+0x700`** |
| `__AUTH_CONST.__const` | `0x3b60` | `0x3ef8` | **`+0x398`** |
| `__TEXT.__swift5_fieldmd` | `0x1cdc` | `0x1f28` | **`+0x24c`** |
| `__TEXT.__swift5_typeref` | `0x1888` | `0x1a3a` | **`+0x1b2`** |
| `__TEXT.__eh_frame` | `0x22a4` | `0x2434` | **`+0x190`** |
| `__DATA.__bss` | `0x7400` | `0x7580` | **`+0x180`** |
| `__TEXT.__cstring` | `0xd6e` | `0xede` | **`+0x170`** |
| `__TEXT.__swift5_capture` | `0x150` | `0x2a0` | **`+0x150`** |
| `__TEXT.__constg_swiftt` | `0x1b6c` | `0x1c60` | **`+0xf4`** |
| `__TEXT.__unwind_info` | `0x1858` | `0x1928` | **`+0xd0`** |
| `__AUTH.__data` | `0xa10` | `0xac8` | **`+0xb8`** |
| `__AUTH_CONST.__auth_got` | `0x938` | `0x990` | **`+0x58`** |
| `__TEXT.__swift5_assocty` | `0x568` | `0x5a8` | **`+0x40`** |
| `__DATA.__data` | `0x9c0` | `0x9f0` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x430` | `0x438` | **`+0x8`** |

### Other Changes

```diff

-1766.0.39.0.2
+1766.0.60.0.0

-  Functions: 2915
-  Symbols:   731
-  CStrings:  97
+  Functions: 3051
+  Symbols:   760
+  CStrings:  105
Symbols:
+ ___swift_memcpy128_8
+ ___swift_memcpy203_8
+ ___swift_memcpy224_8
+ ___swift_memcpy80_8
+ _associated conformance 16CoreTransparency042CTEscapableAETEventsResponseLogConsistencyE0VAA0defgE8ProtocolAA0F4TypeAaDP_SY
+ _associated conformance 16CoreTransparency15CTEPublicKeyBagVAA06PublicdE8ProtocolAA03AppD10CollectionAaDP_AA08CTPublicdI0
+ _associated conformance 16CoreTransparency15CTEPublicKeyBagVAA06PublicdE8ProtocolAA13PATConfigNodeAaDP_AA0hiG0
+ _associated conformance 16CoreTransparency15CTEPublicKeyBagVAA06PublicdE8ProtocolAA13TLTConfigNodeAaDP_AA0hiG0
+ _associated conformance 16CoreTransparency15CTEPublicKeyBagVAA06PublicdE8ProtocolAA16TLTKeyCollectionAaDP_AA08CTPublicdI0
+ _associated conformance 16CoreTransparency15CTEPublicKeyBagVAA06PublicdE8ProtocolAA6VRFKeyAaDP_AA09VRFPublicdG0
+ _associated conformance 16CoreTransparency17PublicKeyBagErrorO10Foundation13CustomNSErrorAAs0F0
+ _get_enum_tag_for_layout_string 16CoreTransparency11VerifiedSLHVyAA23CTEscapableSignedObjectVAA10CTELogHeadVGSg
+ _get_enum_tag_for_layout_string 16CoreTransparency15CTPATConfigNodeVSg
+ _objc_release_x28
+ _swift_release_x27
+ _swift_retain_x27
+ _symbolic 13PATConfigNode_____Qz 16CoreTransparency20PublicKeyBagProtocolP
+ _symbolic 13TLTConfigNode_____Qz 16CoreTransparency20PublicKeyBagProtocolP
+ _symbolic 16AppKeyCollection_____Qz 16CoreTransparency20PublicKeyBagProtocolP
+ _symbolic 16TLTKeyCollection_____Qz 16CoreTransparency20PublicKeyBagProtocolP
+ _symbolic 6VRFKey_____Qz 16CoreTransparency20PublicKeyBagProtocolP
+ _symbolic 7LogType_____Qz 16CoreTransparency031AETEventsResponseLogConsistencyD8ProtocolP
+ _symbolic 7LogType______8RawValueSYQZ 16CoreTransparency031AETEventsResponseLogConsistencyD8ProtocolP
+ _symbolic SS10keySetName_SS26underlyingErrorDescriptiont
+ _symbolic SS10keySetName_Si14configEarliestSi9requestedt
+ _symbolic SS10keySetName______8positiont s6UInt64V
+ _symbolic Si9requested_Si8nextTreet
+ _symbolic _____8expected_AA6actualt 16CoreTransparency15CTPBApplicationO
+ _symbolic _____Sg 16CoreTransparency15CTPATConfigNodeV
+ _symbolic _____Sg 16CoreTransparency15CTTLTConfigNodeV
+ _symbolic _____Sg 16CoreTransparency23CTEscapableVRFPublicKeyV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 16CoreTransparency11CTPublicKeyV
- ___swift_memcpy120_8
- ___swift_memcpy136_8
- ___swift_memcpy72_8
CStrings:
+ "mapStillPopulating"
+ "shutDownTimestampMs"
+ "verifyConsistencyProof: failed to verify consistency "
+ "verifyConsistencyProof: failed to verify endSLH signature: "
+ "verifyConsistencyProof: failed to verify startSLH signature: "
+ "verifyConsistencyProof: verified consistency "
+ "verifyConsistencyProof: verified endSLH "
+ "verifyConsistencyProof: verified startSLH "
+ "verifyConsistencyProofs: new end head "
+ "verifyConsistencyProofs: response logType="
+ "verifyConsistencyProofs: returning "
+ "verifyConsistencyProofs: stamped PAT head "
+ "verifyConsistencyProofs: stamped TLT head "
+ "verifyMapProofs: mismatched TLT heads "
- "verifyConsistencyProofs: failed to verify consistency "
- "verifyConsistencyProofs: failed to verify endSLH signature: "
- "verifyConsistencyProofs: failed to verify startSLH signature: "
- "verifyConsistencyProofs: verified consistency "
- "verifyConsistencyProofs: verified endSLH "
- "verifyConsistencyProofs: verified startSLH "
```
