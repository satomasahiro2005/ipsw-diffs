## gamed

> `/usr/libexec/gamed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a630c` | `0x2aa4dc` | **`+0x41d0`** |
| `__TEXT.__objc_methname` | `0x23dd7` | `0x24447` | **`+0x670`** |
| `__TEXT.__oslogstring` | `0x19319` | `0x198b9` | **`+0x5a0`** |
| `__DATA.__objc_const` | `0x21000` | `0x21330` | **`+0x330`** |
| `__TEXT.__objc_stubs` | `0x1bcc0` | `0x1bfe0` | **`+0x320`** |
| `__DATA_CONST.__const` | `0x14708` | `0x14968` | **`+0x260`** |
| `__DATA_CONST.__cfstring` | `0xc2c0` | `0xc4e0` | **`+0x220`** |
| `__TEXT.__objc_methlist` | `0xe2ec` | `0xe4ec` | **`+0x200`** |
| `__TEXT.__cstring` | `0x19801` | `0x19981` | **`+0x180`** |
| `__TEXT.__gcc_except_tab` | `0x30e4` | `0x3210` | **`+0x12c`** |
| `__DATA.__objc_selrefs` | `0x82c8` | `0x83c0` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0x9190` | `0x9288` | **`+0xf8`** |
| `__DATA.__objc_data` | `0x71e8` | `0x7288` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0xc7e8` | `0xc888` | **`+0xa0`** |
| `__TEXT.__objc_methtype` | `0x73ea` | `0x747a` | **`+0x90`** |
| `__TEXT.__const` | `0x13590` | `0x13600` | **`+0x70`** |
| `__TEXT.__auth_stubs` | `0x4ad0` | `0x4b00` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x2a37` | `0x2a67` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x71c` | `0x744` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x1c2c` | `0x1c48` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0x2580` | `0x2598` | **`+0x18`** |
| `__DATA.__bss` | `0x51e8` | `0x51d8` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x970` | `0x980` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1798` | `0x17a8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x22c8` | `0x22c0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x4b8` | `0x4c0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x2cd0` | `0x2cd6` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x1ec` | `0x1f0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-821.1.8.0.0
+821.1.16.0.0

-  Functions: 12527
-  Symbols:   2581
-  CStrings:  10621
+  Functions: 12631
+  Symbols:   2582
+  CStrings:  10714
Symbols:
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _GKOverlayBundleIDs
+ _dispatch_assert_queue_barrier
+ _dispatch_barrier_sync
- _$sSL2geoiySbx_xtFZTj
- _$sSL2leoiySbx_xtFZTj
- _GKGameOverlayUIIdentifier
- _GKGameOverlayViewServiceIdentifier
CStrings:
+ "\x1f"
+ "%p"
+ "+[GKCloudKitMultiplayer generateAndStoreInviteBulletinForRecord:shareRecordID:database:]"
+ "-[GKProfileService _fetchProfilesForPlayerIDs:familiarity:responseKind:deferNonEssentialData:context:handler:]"
+ "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:familiarity:context:handler:]"
+ "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:familiarity:context:handler:]_block_invoke"
+ "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:handler:]"
+ "-[GKProfileService _loadProfilesForPlayerIDs:familiarity:responseComplete:deferNonEssentialData:context:handler:]"
+ "-[GKUtilityServicePrivate fetchFriendSuggestionsWithHandler:]_block_invoke_2"
+ "-[GKUtilityServicePrivate fetchFriendSuggestionsWithHandler:]_block_invoke_4"
+ "@\"GKFriendSuggestionContext\""
+ "@64@0:8@16@24@32@40@?48@?56"
+ "@68@0:8@16@24B32@36@44@52@?60"
+ "@?40@0:8@?16d24@32"
+ "@?48@0:8@?16d24@32@?40"
+ "Accepted"
+ "B16@?0@\"NSSet\"8"
+ "B48@0:8@16@24@32@?40"
+ "Background game metadata warm completed for %lu bundle id(s)"
+ "Background game metadata warm failed: %@"
+ "Background scoped id warm completed"
+ "Delivered"
+ "Failed to warm scoped ids for profiles in the background, error: %@"
+ "GKFriendSuggestionContext"
+ "GKInviteTrackingEntry"
+ "GKProfileService: warmGameMetadataInBackgroundForBundleIDs:"
+ "Processing"
+ "Removed %@ invite tracking entr%@ older than %.0f hours."
+ "T@\"GKFriendSuggestionContext\",&,N,V_context"
+ "T@\"NSArray\",C,N,V_recentGamesInCommon"
+ "T@\"NSDate\",R,N,V_stateChangedAt"
+ "T@\"NSDictionary\",&,N,V_cachedCaidsMetadata"
+ "T@\"NSMutableDictionary\",&,N,V_inviteTrackingByShareRecordID"
+ "T@\"NSMutableDictionary\",&,N,V_pendingCallbackParameters"
+ "T@\"NSNumber\",C,N,V_hasFriendsInCommon"
+ "T@\"NSNumber\",C,N,V_numRecentGamesInCommon"
+ "Tq,N,V_state"
+ "Will not rerank contact association IDs with service since cached values cover all current CAIDs: %@"
+ "[%@] About to claim share %@."
+ "[%@] About to look up an accepted session token."
+ "[%@] About to mark share %@ Delivered."
+ "[%@] About to stop tracking share %@."
+ "[%@] Ignoring accept: no session token was provided."
+ "[%@] Ignoring accept: session token is not tracked (likely not a Messages-based invite)."
+ "[%@] Not clearing share %@: it is %@, owned by a later delivery."
+ "[%@] Share %@ has been %@ for %.1f seconds; allowing a retry."
+ "[%@] Share %@ has no tracking entry; treating this delivery as new."
+ "[%@] Share %@ is now Accepted."
+ "[%@] Share %@ is now Delivered (has session token: %@)."
+ "[%@] Share %@ is still %@ (%.1f seconds old); ignoring this redelivery."
+ "[%@] Share %@ received an accept, but was already %@; ignoring."
+ "[%@] Share %@ was already Accepted; ignoring this redelivery."
+ "[%@] Share %@ was not being tracked when marking it Delivered; creating a new entry."
+ "[%@] Stopped tracking share %@; the next redelivery will be treated as new."
+ "_cachedCaidsMetadata"
+ "_fetchProfilesForPlayerIDs:familiarity:responseKind:deferNonEssentialData:context:handler:"
+ "_getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:familiarity:context:handler:"
+ "_getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:handler:"
+ "_hasFriendsInCommon"
+ "_inviteTrackingByShareRecordID"
+ "_loadProfilesForPlayerIDs:familiarity:responseComplete:deferNonEssentialData:context:handler:"
+ "_numRecentGamesInCommon"
+ "_pendingCallbackParameters"
+ "_recentGamesInCommon"
+ "_state"
+ "_stateChangedAt"
+ "cacheOnly"
+ "cachedCaidsMetadata"
+ "cachedSuggestedFriendsWithContext:"
+ "caids-with-metadata"
+ "caidsMetadata"
+ "claimShareRecordIDForProcessing:"
+ "com.apple.gamed.GKNetworkRequestManager.timeoutReplyGuard"
+ "common == NO"
+ "contactAssociationIDsFromServerArray:"
+ "contextFromServerDictionary:"
+ "contextMapFromServerArray:"
+ "doesCallbackListExistFor:parameters:callback:inFlightMatcher:"
+ "fetchFriendSuggestions: friend list unavailable; returning no suggestions to avoid surfacing friends as suggestions."
+ "full"
+ "g:"
+ "generateAndStoreInviteBulletinForRecord:shareRecordID:database:"
+ "getProfilesForPlayerIDs:discardingStaleData:deferNonEssentialData:handler:"
+ "hardExpiryForTesting"
+ "has-friends-in-common"
+ "hasFriendsInCommon"
+ "ies"
+ "initWithSettings:networkRequester:cachedSortedAssociationIDs:cachedCaidsMetadata:transactionGroupProvider:featureEnabledBlock:"
+ "inviteTrackingByShareRecordID"
+ "isSubsetOfSet:"
+ "loadFriendListIfNeverLoaded: friend list has never been loaded; fetching friend IDs before proceeding."
+ "loadFriendListIfNeverLoaded: unable to load friend list: %@"
+ "loadFriendListIfNeverLoadedWithHandler:"
+ "markInviteAcceptedForSessionToken:"
+ "markSessionTokenAccepted:"
+ "markShareRecordIDDelivered:sessionToken:"
+ "modifiersWithSettings:contactsIntegrationController:hasCachedSuggestions:cachedSortedAssociationIDs:cachedCaidsMetadata:rerankRequester:transactionGroupProvider:"
+ "num-recent-games-in-common"
+ "numRecentGamesInCommon"
+ "p:"
+ "pendingCallbackParameters"
+ "recent-games-in-common"
+ "recentGamesInCommon"
+ "retryTimeoutForTesting"
+ "setCachedCaidsMetadata:"
+ "setCaidsMetadata:"
+ "setHasFriendsInCommon:"
+ "setInviteTrackingByShareRecordID:"
+ "setNumRecentGamesInCommon:"
+ "setPendingCallbackParameters:"
+ "setRecentGamesInCommon:"
+ "stateChangedAt"
+ "stopTrackingShareRecordID:"
+ "sweepExpiredEntriesLocked"
+ "timeoutBoundedHandler:timeout:timeoutError:"
+ "timeoutBoundedHandler:timeout:timeoutError:timeoutScheduler:"
+ "timeoutReplyGuardQueue"
+ "v24@?0@8@\"NSError\"16"
+ "v24@?0d8@?<v@?>16"
+ "v32@?0@\"CKRecordID\"8@\"GKInviteTrackingEntry\"16^B24"
+ "v52@0:8@16B24B28i32@36@?44"
+ "v52@0:8@16i24B28B32@36@?44"
+ "v52@0:8@16i24i28B32@36@?44"
+ "warmGameMetadataInBackgroundForBundleIDs:"
- "+[GKCloudKitMultiplayer generateAndStoreInviteBulletinForRecord:database:]"
- "-[GKProfileService _fetchProfilesForPlayerIDs:familiarity:responseKind:context:handler:]"
- "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:familiarity:context:handler:]"
- "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:familiarity:context:handler:]_block_invoke"
- "-[GKProfileService _getProfilesForPlayerIDs:discardingStaleData:handler:]"
- "-[GKProfileService _loadProfilesForPlayerIDs:familiarity:responseComplete:context:handler:]"
- "-[GKUtilityServicePrivate fetchFriendSuggestionsWithHandler:]_block_invoke"
- "-[GKUtilityServicePrivate fetchFriendSuggestionsWithHandler:]_block_invoke_3"
- "@56@0:8@16@24@32@?40@?48"
- "@60@0:8@16@24B32@36@44@?52"
- "Already processing same share metadata, returning."
- "T@\"NSMutableSet\",&,N,V_acceptingInProgressRecordIDs"
- "Will not rerank contact association IDs with service since we have cached values: %@"
- "_acceptingInProgressRecordIDs"
- "_fetchProfilesForPlayerIDs:familiarity:responseKind:context:handler:"
- "_getGameMetadataForBundleIDs"
- "_getProfilesForPlayerIDs"
- "_getProfilesForPlayerIDs:discardingStaleData:familiarity:context:handler:"
- "_getProfilesForPlayerIDs:discardingStaleData:handler:"
- "_loadProfilesForPlayerIDs:familiarity:responseComplete:context:handler:"
- "acceptingInProgressRecordIDs"
- "com.apple.gamed.GKGameService.metadata.serial"
- "com.apple.gamed.GKProfileService.profile.serial"
- "generateAndStoreInviteBulletinForRecord:database:"
- "initWithSettings:networkRequester:cachedSortedAssociationIDs:transactionGroupProvider:featureEnabledBlock:"
- "metadataSerialQueue"
- "modifiersWithSettings:contactsIntegrationController:hasCachedSuggestions:cachedSortedAssociationIDs:rerankRequester:transactionGroupProvider:"
- "profileSerialQueue"
- "setAcceptingInProgressRecordIDs:"
- "v48@0:8@16i24B28@32@?40"
- "v48@0:8@16i24i28@32@?40"
```
