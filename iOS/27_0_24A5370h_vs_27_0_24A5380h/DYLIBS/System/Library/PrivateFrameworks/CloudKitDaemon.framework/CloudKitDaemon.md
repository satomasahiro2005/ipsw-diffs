## CloudKitDaemon

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/CloudKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3da15c` | `0x3d8d80` | **`-0x13dc`** |
| `__AUTH_CONST.__const` | `0x5830` | `0x51c8` | **`-0x668`** |
| `__TEXT.__cstring` | `0x2ab75` | `0x2b0de` | **`+0x569`** |
| `__TEXT.__swift5_capture` | `0xb2c` | `0x8a4` | **`-0x288`** |
| `__DATA_CONST.__got` | `0x1dc8` | `0x2038` | **`+0x270`** |
| `__TEXT.__oslogstring` | `0x3207f` | `0x322e8` | **`+0x269`** |
| `__AUTH_CONST.__cfstring` | `0x23680` | `0x237a0` | **`+0x120`** |
| `__TEXT.__const` | `0x4cb8` | `0x4bf8` | **`-0xc0`** |
| `__TEXT.__eh_frame` | `0x3230` | `0x3178` | **`-0xb8`** |
| `__TEXT.__gcc_except_tab` | `0xc62c` | `0xc664` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xce78` | `0xce40` | **`-0x38`** |
| `__DATA.__data` | `0x1e28` | `0x1df8` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x12f10` | `0x12f40` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x2248` | `0x2218` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x1f7d` | `0x1f5f` | **`-0x1e`** |
| `__AUTH_CONST.__auth_got` | `0x2158` | `0x2168` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x4a9c0` | `0x4a9b0` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x99b0` | `0x99c0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x31434` | `0x31444` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x1a8` | `0x198` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x12c` | `0x138` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-2710.112.0.0.0
+2710.114.0.0.0

-  Functions: 20670
-  Symbols:   2942
-  CStrings:  8407
+  Functions: 20606
+  Symbols:   2944
+  CStrings:  8446
Symbols:
+ _$sSS11utf8CStrings15ContiguousArrayVys4Int8VGvg
+ _CKDPCSFetchOptionsCanSatisfyOptions
+ _CKStringForQueuePriority
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%@ %@ State: %@, QoS: %@, QueuePriority: %@"
+ "%@ (%@)"
+ "%s: Received blocking device acquisition event: %s, readinessError: %@"
+ "%{public}s MMCS item %llu with size:%llu, paddedSize:%llu, signature:%@, path:%@"
+ "AccountCheck Account Notification Handler"
+ "AccountCheck Request Auth Token"
+ "AccountCheck Start"
+ "AccountCheck TCC Notification Handler"
+ "AccountCheck Token Renewal Notification Handler"
+ "Boosted queuePriority to VeryHigh for cancellation <%{public}@: %p; %{public}@>"
+ "CKDDeserializeRecordModificationsOperation is unable to instantiate a CKDProtocolTranslator"
+ "CKDSessionAcquirer Acquiring Session "
+ "CKDSessionAcquirer Awaiting Account Check "
+ "CKDSessionAcquirer Awaiting Data Security Check "
+ "CKDSessionAcquirer Awaiting Device Check "
+ "CKDSessionAcquirer Awaiting Encryption Check "
+ "CKDSessionAcquirer Cancelling Acquisition"
+ "CKDSessionAcquirer Fetching User Info"
+ "CKDSessionAcquirer Registering Push"
+ "Couldn't remove participant PCS for share %@: %@"
+ "DataSecurityCheck Account Notification Handler"
+ "DataSecurityCheck Start"
+ "Detached test servers don't have account data security observers"
+ "Detected minimal resolve for %@ but adopter is not entitled with InProcessShareAccessRequests; returning UnknownItem"
+ "DeviceCheck Logical Device Availability Notification Handler"
+ "DeviceCheck Start"
+ "DeviceCheck System Availability Notification Handler"
+ "EncryptionCheck Identity Completed"
+ "EncryptionCheck Start"
+ "Error translating CKMergeableDeltas during serialization: %@"
+ "Expected state %ld for MMCS engine context %@"
+ "Failed to fetch sharePCS for share %@"
+ "Failed to get keyID from encrypted data %@. Soldiering on and trying all keyIDs. PCS error: %@"
+ "Failed to register token registration refresh task with error: %@"
+ "Failed to remove download directory while clearing cache: %{public}@"
+ "Firing queued fetch %@ immediately since it's been waiting too long"
+ "Forcing a failure to save device capabilities for operation %@"
+ "Incoming client %@ connection with processBinaryName %@ is waiting to resume its container available queue. We have %ld existing connection%@ tearing down"
+ "Initialized with container %p. Background: %d, cellular: %d, expensive: %d, QOS: 0x%x, queuePriority: %{public}@"
+ "Invalid list of heterogeneous values for field name %@ in recordID %@"
+ "Must not set properties on CKUsageInfoImmutable instance"
+ "QueuePriority %@ "
+ "Registered token registration refresh task"
+ "Rolling existing zone %@ due to reparenting to %@"
+ "Server Configuration plist contains override for container %@, but it does not have an enableAdopterCapabilityReport key"
+ "Server Configuration plist contains override for container %@, but it does not have an enableCheckingAdopterCapability key"
+ "ServiceIdentityActor Completed"
+ "ServiceIdentityActor PCS Notification Handler"
+ "ServiceIdentityActor Start"
+ "Share %@ does not exist or is not accessible"
+ "Successfully saved updated device capabilities to the server for containerID %{public}@: %{public}@"
+ "This requires an authenticated account, we only have an anonymous account"
+ "TrafficLogger Delayed Flush"
+ "TrafficLogger Flush"
+ "Trying to decrypt data that is too short to contain an IV and tag"
+ "Type=%{signpost.description:attribute,public}@ ID=%{signpost.description:attribute}@ ContainerID=%{signpost.description:attribute}@ BundleID=%{signpost.description:attribute}@ QoS=%{signpost.description:attribute,public}@ QueuePriority=%{signpost.description:attribute,public}@ "
+ "Unable to vet due to failed authentication even after successful authentication attempt, giving up"
+ "We failed a prior decryption of this PCS data with a manatee identity when current identity is non-manatee. Did our identity change?"
+ "Zone %@ failed zone PCS validation while saving with parent %@. Evicting cached parent zone PCS before retry."
+ "clientQueuePriority"
+ "explicit"
+ "queuePriority"
+ "queuePriorityString"
+ "wants-zone-parent"
- "%@ %@ State: %@, QoS: %@"
- "%s: Received blocking device device acquisition event: %s, readinessError: %@"
- "CKDPCSCacheShareFetchOperation.m"
- "Couldn't remove participant participant PCS for share %@: %@"
- "Error translating CKMergerableDeltas during serialization: %@"
- "Expected state %ld for MMCS engine context"
- "Failed to get keyID from encrypted data %@. Soldering on and trying all keyIDs. PCS error: %@"
- "Failed to remove download directory while clearning cache: %{public}@"
- "Firing queued fetch %@ immediately since its been waiting too long"
- "Forcing a failure to save device capabilties for operation %@"
- "Incoming client %@ connection with processBinaryName %@ is waiting resume its container available queue. We have %ld existing connection%@ tearing down"
- "Initialized with container %p. Background: %d, cellular: %d, expensive: %d, QOS: 0x%x"
- "Invalid list of heterogenous values for field name %@ in recordID %@"
- "Must not set properies on CKUsageInfoImmutable instance"
- "Rolling existing zone %@ due reparenting to %@"
- "Server Configuration plist contains override for container %@, but it does not have a enableAdopterCapabilityReport key"
- "Server Configuration plist contains override for container %@, but it does not have a enableCheckingAdopterCapability key"
- "Successfully saved updated device capabilties to the server for containerID %{public}@: %{public}@"
- "This requires an authenticated account, we have only have an anonymous account"
- "Trying to decrypt a zero-length data"
- "Type=%{signpost.description:attribute,public}@ ID=%{signpost.description:attribute}@ ContainerID=%{signpost.description:attribute}@ BundleID=%{signpost.description:attribute}@ QoS=%{signpost.description:attribute,public}@ "
- "Unable to vet due to failed authentification even after successful authentication attempt, giving up"
- "We failed a prior decryption of this PCS data a with manatee identity when current identity is non-manatee. Did our identity change?"
- "We should have PCS data for share %@ by this point"
- "{public}%s MMCS item %llu with size:%llu, paddedSize:%llu, signature:%@, path:%@"
```
