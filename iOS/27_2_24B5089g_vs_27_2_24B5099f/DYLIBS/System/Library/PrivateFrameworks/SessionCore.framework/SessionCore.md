## SessionCore

> `/System/Library/PrivateFrameworks/SessionCore.framework/SessionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14f458` | `0x14e74c` | **`-0xd0c`** |
| `__TEXT.__eh_frame` | `0x3818` | `0x3940` | **`+0x128`** |
| `__DATA.__bss` | `0x2280` | `0x2180` | **`-0x100`** |
| `__TEXT.__oslogstring` | `0x7a54` | `0x7b14` | **`+0xc0`** |
| `__DATA_DIRTY.__data` | `0x70f8` | `0x7070` | **`-0x88`** |
| `__TEXT.__swift5_fieldmd` | `0x2d30` | `0x2cbc` | **`-0x74`** |
| `__TEXT.__const` | `0x5612` | `0x55a2` | **`-0x70`** |
| `__AUTH_CONST.__const` | `0x6198` | `0x6130` | **`-0x68`** |
| `__TEXT.__swift5_typeref` | `0x2df5` | `0x2e3f` | **`+0x4a`** |
| `__TEXT.__constg_swiftt` | `0x46a8` | `0x4664` | **`-0x44`** |
| `__AUTH_CONST.__auth_got` | `0x1de8` | `0x1e18` | **`+0x30`** |
| `__DATA.__data` | `0x1a10` | `0x1a30` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x2cd7` | `0x2cb7` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x14b4` | `0x14c4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2678` | `0x2688` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x370` | `0x368` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x29c` | `0x294` | **`-0x8`** |

### Other Changes

```diff

-313.2.4.0.0
+313.2.7.0.0

-  Functions: 3579
-  Symbols:   1756
-  CStrings:  846
+  Functions: 3582
+  Symbols:   1759
+  CStrings:  848
Symbols:
+ _swift_release_x10
+ _swift_retain_x9
+ _symbolic SDy___________pG 18ReplicatorServices0A6DeviceV0C4TypeO 11SessionCore20ReplicationFilteringP
+ _symbolic _____3key_______p5valuet 18ReplicatorServices0A6DeviceV0C4TypeO 11SessionCore20ReplicationFilteringP
+ _symbolic _____SgXw 11SessionCore21ReplicatorParticipantC
+ _symbolic ____________pt 18ReplicatorServices0A6DeviceV0C4TypeO 11SessionCore20ReplicationFilteringP
+ _symbolic _____y____________ptG s23_ContiguousArrayStorageC 18ReplicatorServices0D6DeviceV0F4TypeO 11SessionCore20ReplicationFilteringP
+ _symbolic _____y___________pG s18_DictionaryStorageC 18ReplicatorServices0C6DeviceV0E4TypeO 11SessionCore20ReplicationFilteringP
- _associated conformance 11SessionCore13ActivityStateV0D0OSHAASQ
- _symbolic _____ 11SessionCore13ActivityStateV
- _symbolic _____ 11SessionCore13ActivityStateV0D0O
- _symbolic _____Sg 10Foundation4DataV
- _symbolic ______pSg 11SessionCore20ReplicationFilteringP
CStrings:
+ "Cannot replicate activity to a device that does not exist: %{public}s: relationshipSchedule %{public}s"
+ "Error finding the app record for bundle identifier: %{private}s"
+ "Replication of activity %{public}s is unfiltered for relationshipSchedule %{public}s"
+ "appSettings disallowed replication for %s"
- "Error finding the app record for bundle identifier: %{private}s: %s"
- "No asset provider bundle ID provided"
```
