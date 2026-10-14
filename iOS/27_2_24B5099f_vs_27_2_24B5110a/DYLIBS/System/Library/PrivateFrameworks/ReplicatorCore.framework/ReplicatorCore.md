## ReplicatorCore

> `/System/Library/PrivateFrameworks/ReplicatorCore.framework/ReplicatorCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f1ec` | `0x81140` | **`+0x1f54`** |
| `__TEXT.__eh_frame` | `0x2000` | `0x2160` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x26d6` | `0x2776` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x1170` | `0x1208` | **`+0x98`** |
| `__AUTH_CONST.__auth_got` | `0x1980` | `0x19f0` | **`+0x70`** |
| `__TEXT.__const` | `0x1288` | `0x12f8` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0xdd0` | `0xe38` | **`+0x68`** |
| `__DATA_DIRTY.__data` | `0x16b0` | `0x16d0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xff9` | `0x1017` | **`+0x1e`** |
| `__TEXT.__constg_swiftt` | `0xf48` | `0xf64` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x7dc` | `0x7f8` | **`+0x1c`** |
| `__DATA.__data` | `0x7c0` | `0x7d0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x88` | `0x8c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x78` | `0x7c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-176.2.5.0.0
+176.2.6.0.0

-  Functions: 1025
-  Symbols:   660
-  CStrings:  238
+  Functions: 1045
+  Symbols:   665
+  CStrings:  239
Symbols:
+ ___swift_memcpy16_8
+ _symbolic _____ 14ReplicatorCore24BadJ490WidgetHostCleanupV
+ _symbolic ______p 14ReplicatorCore17DataMigratorStage33_848E0D235FCA0EB94D52E4482AEF4B45LLP
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 14ReplicatorCore17DataMigratorStage33_848E0D235FCA0EB94D52E4482AEF4B45LLP
+ _type_layout_string 14ReplicatorCore24BadJ490WidgetHostCleanupV
CStrings:
+ "Adding handshake advertiser"
+ "Fetched local device ID %{private}s for migration"
+ "IDS service has no matching device with ID %{private}s for relationship %{public}s"
+ "Me device %{private}s is already paired for persona %{public}s in relationship %{public}s"
+ "No push token for device with ID %{private}s for relationship %{public}s"
+ "No relationship found for %{public}s; sending introductory message to me device %{private}s"
+ "Received chronod message from device without a relationship: %{private}s; %{public}s"
+ "Received message from device without a relationship: %{private}s; %{public}s"
+ "Unpairing from device ID %{private}s in relationship %{public}s for persona %{public}s"
- "Device has no push token: %{public}s"
- "Fetched local device ID %{public}s for migration"
- "IDS service has no matching device with ID %{public}s"
- "Me device %{public}s is already paired for persona %{public}s"
- "No relationship found for %{public}s; sending introductory message to me device %{public}s"
- "Received chronod message from device without a relationship: %{public}s; %{public}s"
- "Received message from device without a relationship: %{public}s; %{public}s"
- "Unpairing from %{public}s for persona %{public}s"
```
