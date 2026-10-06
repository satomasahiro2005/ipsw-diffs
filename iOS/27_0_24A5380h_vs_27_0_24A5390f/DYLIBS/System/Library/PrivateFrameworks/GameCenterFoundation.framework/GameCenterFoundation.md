## GameCenterFoundation

> `/System/Library/PrivateFrameworks/GameCenterFoundation.framework/GameCenterFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x172424` | `0x172850` | **`+0x42c`** |
| `__DATA.__bss` | `0x8150` | `0x82d0` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0x114e0` | `0x11640` | **`+0x160`** |
| `__TEXT.__cstring` | `0x18ec0` | `0x18ff0` | **`+0x130`** |
| `__AUTH_CONST.__objc_const` | `0x24500` | `0x245c8` | **`+0xc8`** |
| `__TEXT.__const` | `0x6548` | `0x6608` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x6c58` | `0x6ce8` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x6158` | `0x61b0` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x1219c` | `0x121dc` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x8530` | `0x8560` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1113` | `0x1143` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x67a0` | `0x67c8` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x18bc` | `0x18e0` | **`+0x24`** |
| `__TEXT.__swift5_fieldmd` | `0x1728` | `0x1744` | **`+0x1c`** |
| `__DATA.__data` | `0x3a50` | `0x3a60` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x2054` | `0x2062` | **`+0xe`** |
| `__TEXT.__swift5_proto` | `0x438` | `0x444` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1550` | `0x1558` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1b0` | `0x1b4` | **`+0x4`** |

### Other Changes

```diff

-821.0.18.0.0
+821.0.20.0.0

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 11204
-  Symbols:   12298
-  CStrings:  4190
+  Functions: 11219
+  Symbols:   12313
+  CStrings:  4202
Symbols:
+ _GKRemoteAlertDeeplinkActionActivityInstanceValue
+ _GKRemoteAlertDeeplinkActionArcadeValue
+ _GKRemoteAlertDeeplinkActionChallengeCreationValue
+ _GKRemoteAlertDeeplinkActionChallengeValue
+ _GKRemoteAlertDeeplinkActionChallengesHubValue
+ _GKRemoteAlertDeeplinkActionFriendInvitesValue
+ _GKRemoteAlertDeeplinkActionFriendRequestsValue
+ _GKRemoteAlertDeeplinkActionFriendsListValue
+ _GKRemoteAlertDeeplinkActionMultiplayerActivityValue
+ _GKRemoteAlertDeeplinkActionPickActivityValue
+ _GKRemoteAlertDeeplinkActionSecondaryIdentifierKey
+ __OBJC_$_INSTANCE_METHODS_GKPreferences(AgeCategoryRestrictions|Restrictions|GameCenterFoundation)
+ ___106+[GKAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_6
+ ___106+[GKAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_7
+ _associated conformance 20GameCenterFoundation15GCFFeatureFlags33_C8F9952CB504BDA417696FB853948431LLOSHAASQ
+ _symbolic _____ 20GameCenterFoundation15GCFFeatureFlags33_C8F9952CB504BDA417696FB853948431LLO
- __OBJC_$_INSTANCE_METHODS_GKPreferences(AgeCategoryRestrictions|Restrictions)
CStrings:
+ "achievements_game_services"
+ "deep-link-action-secondary-identifier"
+ "deep-link-activity-instance"
+ "deep-link-arcade"
+ "deep-link-challenge"
+ "deep-link-challenge-creation"
+ "deep-link-challenges-hub"
+ "deep-link-friend-invites"
+ "deep-link-friend-requests"
+ "deep-link-friends-list"
+ "deep-link-multiplayer-activity"
+ "deep-link-pick-activity"
```
