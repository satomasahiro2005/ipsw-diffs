## OnDeviceStorageCore

> `/System/Library/PrivateFrameworks/OnDeviceStorageCore.framework/OnDeviceStorageCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x171458` | `0x17a3bc` | **`+0x8f64`** |
| `__TEXT.__oslogstring` | `0x10` | `0x8a7` | **`+0x897`** |
| `__TEXT.__cstring` | `0x6e1e` | `0x6b0e` | **`-0x310`** |
| `__AUTH_CONST.__const` | `0xc938` | `0xcbb0` | **`+0x278`** |
| `__DATA.__bss` | `0x1a980` | `0x1ab80` | **`+0x200`** |
| `__TEXT.__const` | `0x16240` | `0x16410` | **`+0x1d0`** |
| `__TEXT.__swift5_capture` | `0x9cc` | `0xaac` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x4652` | `0x46c4` | **`+0x72`** |
| `__TEXT.__unwind_info` | `0x49a8` | `0x4a00` | **`+0x58`** |
| `__DATA.__data` | `0x2608` | `0x25c0` | **`-0x48`** |
| `__DATA_DIRTY.__common` | `0xb0` | `0x68` | **`-0x48`** |
| `__TEXT.__swift5_reflstr` | `0x1d87` | `0x1dce` | **`+0x47`** |
| `__TEXT.__swift5_fieldmd` | `0x404c` | `0x4080` | **`+0x34`** |
| `__DATA.__common` | `0x50` | `0x80` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x3160` | `0x3130` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x3994` | `0x39b8` | **`+0x24`** |
| `__DATA_CONST.__const` | `0x98` | `0xb8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x11b0` | `0x1198` | **`-0x18`** |
| `__TEXT.__eh_frame` | `0x7800` | `0x7814` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x1458` | `0x1468` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x538` | `0x53c` | **`+0x4`** |

### Other Changes

```diff

-3.0.59.0.0
+3.1.10.0.0

-  Functions: 6981
-  Symbols:   2195
-  CStrings:  683
+  Functions: 7033
+  Symbols:   2207
+  CStrings:  695
Symbols:
+ ___unnamed_13
+ ___unnamed_16
+ ___unnamed_36
+ __objc_autoreleasePoolPop
+ __objc_autoreleasePoolPush
+ __os_log_impl
+ _associated conformance 19OnDeviceStorageCore11DaemonErrorO31SyncAccountUnresolvedCodingKeys33_2EC86B0C67D2C3FF02A82C2CBEEE1165LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 19OnDeviceStorageCore11DaemonErrorO31SyncAccountUnresolvedCodingKeys33_2EC86B0C67D2C3FF02A82C2CBEEE1165LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _objc_retain_x23
+ _os_log_type_enabled
+ _symbolic SSIego_
+ _symbolic _____ 19OnDeviceStorageCore11DaemonErrorO31SyncAccountUnresolvedCodingKeys33_2EC86B0C67D2C3FF02A82C2CBEEE1165LLO
+ _symbolic _____ s5Int32V
+ _symbolic _____y_____G s11_SetStorageC 08OnDeviceB4Core0B8CategoryO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 19OnDeviceStorageCore11DaemonErrorO31SyncAccountUnresolvedCodingKeys33_2EC86B0C67D2C3FF02A82C2CBEEE1165LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 19OnDeviceStorageCore11DaemonErrorO31SyncAccountUnresolvedCodingKeys33_2EC86B0C67D2C3FF02A82C2CBEEE1165LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 08OnDeviceC4Core0C8CategoryO
+ _symbolic _____yySpy_____Gz_SpySo8NSObjectCSgGSgzSpyypGSgztcG s23_ContiguousArrayStorageC s5UInt8V
- ___swift_allocate_boxed_opaque_existential_0Tm
- ___unnamed_15
- ___unnamed_18
- ___unnamed_38
- _symbolic _____y_____G s23_ContiguousArrayStorageC 18OnDeviceFoundation10LogMessageV
- _symbolic _____y______pG s9TaskLocalC 18OnDeviceFoundation6LoggerP
CStrings:
+ " (a TTL is mandatory for sync storage)"
+ " (a primary key is mandatory for sync storage — it is the cross-device row identity)"
+ "%{public}ld row(s) were dropped due to value sizes for %{public}ld columns being too large: %{public}s"
+ "%{public}s"
+ "%{public}s is not implemented for %{public}s"
+ "Already closed (handle=%{public}s)"
+ "Ambiguous profile folder match for partial hash or profileId: "
+ "Clearing container data at: %{public}s, items: %{public}ld"
+ "Closing connection (handle=%{public}s) at: %{public}s"
+ "Container data cleared: %{public}ld/%{public}ld items deleted"
+ "Database file doesn't exit probably because no data has ever been written yet or because data was written using a different profileId"
+ "Deleted: %{public}s"
+ "Directory does not exist: %{public}s"
+ "Error reading directory at %{public}s: %{public}s"
+ "Estimated row size in bytes: %{public}ld"
+ "Failed to fetch column names for %{public}s: %{public}s"
+ "Failed to infer value type: %{public}s"
+ "Failed to open directory at %{public}s: %{public}s"
+ "GENERATED ALWAYS AS"
+ "Invalid max batch size: %{public}ld"
+ "Invalid row size estimate: %{public}ld"
+ "Make sure data is written to database first, make sure data is written and read under the same profileId"
+ "Multiple profile folders match the provided partial hash or profileId"
+ "No data has ever been written to this database yet (Different profileId?)"
+ "Opened connection (handle=%{public}s) at: %{public}s"
+ "Profile folder not found for partial hash or profileId: "
+ "SQL statement has more values than placeholders, placeholders: %{public}ld, values: %{public}ld."
+ "Sending error of Error type to client, expecting RichError. (%{public}s)"
+ "Sending error of LocalizedError type to client, expecting RichError. (%{public}s)"
+ "Statements finalized, retrying close (handle=%{public}s)..."
+ "Sync account unresolved"
+ "Synced (CloudKit) storage cannot be located before the cloud account is resolved"
+ "Synced (CloudKit) storage cannot be opened before the cloud account is resolved"
+ "The estimate size of returned row (%{public}ld) is larger than or equal to max batch size: %{public}ld"
+ "The storage category is not supported by this build"
+ "The storage category is not supported by this build: "
+ "Unable to %{public}s network fetch for certificate chain verification, status: %{public}d"
+ "Unable to delete file at path: %{public}s. (%{public}s)"
+ "Unable to get size estimate for column: %{public}s"
+ "Unable to get table specification for size estimation, reason: %{public}s"
+ "Unable to verify certificate chain in offline mode, reason: %{public}s, retrying with network fetch enabled"
+ "Unqualified table name found when estimating row size, table: %{public}s"
+ "com.apple.aps.amsondevicestoraged"
+ "deinit Connection (handle=%{public}s) at: %{public}s"
+ "missing required TTL for table: "
+ "missing required primary key for table: "
+ "sqlite3_close (handle=%{public}s) returned %{public}d"
+ "sqlite3_close returned %{public}d for connection"
+ "sqlite3_close returned %{public}d on retry"
+ "syncAccountUnresolved"
- " columns being too large: "
- " is not implemented for "
- " network fetch for certificate chain verification, status: "
- " row(s) were dropped due to value sizes for "
- ") is larger than or equal to max batch size: "
- ", retrying with network fetch enabled"
- "Already closed (handle="
- "Ambiguous user folder match for partial hash or userId: "
- "Clearing container data at: "
- "Closing connection (handle="
- "Container data cleared: "
- "Database file doesn't exit probably because no data has ever been written yet or because data was written using different user account (DSID)"
- "Directory does not exist: "
- "Error reading directory at "
- "Estimated row size in bytes: "
- "Failed to fetch column names for "
- "Failed to infer value type: "
- "Failed to open directory at "
- "Invalid max batch size: "
- "Invalid row size estimate: "
- "Make sure data is written to database first, make sure data is written and read under the same user account (DSID)"
- "Multiple user folders match the provided partial hash or userId"
- "No data has ever been written to this database yet (Different user DSID?)"
- "Opened connection (handle="
- "SQL statement has more values than placeholders, placeholders: "
- "Sending error of Error type to client, expecting RichError. ("
- "Sending error of LocalizedError type to client, expecting RichError. ("
- "Statements finalized, retrying close (handle="
- "The estimate size of returned row ("
- "Unable to delete file at path: "
- "Unable to get size estimate for column: "
- "Unable to get table specification for size estimation, reason: "
- "Unable to verify certificate chain in offline mode, reason: "
- "Unqualified table name found when estimating row size, table: "
- "User folder not found for partial hash or userId: "
- "deinit Connection (handle="
- "sqlite3_close (handle="
- "sqlite3_close returned "
```
