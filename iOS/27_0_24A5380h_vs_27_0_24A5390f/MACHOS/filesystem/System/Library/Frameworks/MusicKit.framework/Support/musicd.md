## musicd

> `/System/Library/Frameworks/MusicKit.framework/Support/musicd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29108` | `0x2a02c` | **`+0xf24`** |
| `__TEXT.__eh_frame` | `0x25a0` | `0x2610` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x13b7` | `0x1427` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x450` | `0x478` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x1450` | `0x1470` | **`+0x20`** |
| `__TEXT.__const` | `0x15a8` | `0x15c8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4a0` | `0x4c0` | **`+0x20`** |
| `__DATA.__data` | `0xb98` | `0xba8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xa30` | `0xa40` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x712` | `0x720` | **`+0xe`** |
| `__TEXT.__swift_as_cont` | `0x1a4` | `0x1ac` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb00` | `0xb08` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x118` | `0x11c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-4026.100.85.0.0
+4026.100.89.0.0

-  Functions: 943
-  Symbols:   572
-  CStrings:  189
+  Functions: 978
+  Symbols:   579
+  CStrings:  191
Symbols:
+ _$s16MusicKitInternal0A22ConcertsRankingServiceV014recordNotifiedD03foryAC12NotificationV_tYaKF
+ _$s16MusicKitInternal0A22ConcertsRankingServiceV014recordNotifiedD03foryAC12NotificationV_tYaKFTu
+ _$s16MusicKitInternal0A22ConcertsRankingServiceV27pruneScheduledNotificationsyyYaKF
+ _$s16MusicKitInternal0A22ConcertsRankingServiceV27pruneScheduledNotificationsyyYaKFTu
+ _$s16MusicKitInternal0A22ConcertsRankingServiceV29processNotificationCandidates_014forgetNotifiedD0SayAC0H0VGAA0adH7PayloadV_SbtYaKF
+ _$s16MusicKitInternal0A22ConcertsRankingServiceV29processNotificationCandidates_014forgetNotifiedD0SayAC0H0VGAA0adH7PayloadV_SbtYaKFTu
+ _$s16MusicKitInternal0A24ConcertsRankingInterfaceP29processNotificationCandidates_014forgetNotifiedD0AA0A6DaemonV6ResultOy_AG11CodableVoidVGAA0adH7PayloadV_SbtYaFTq
+ _$s16MusicKitInternal0A24ConcertsRankingInterfaceP29processNotificationCandidates_014forgetNotifiedD0AA0A6DaemonV6ResultOy_AG11CodableVoidVGAA0adH7PayloadV_SbtYaKFTqTE
+ _$sSbN
+ _$sSbSEsWP
+ _$sSbSesWP
- _$s16MusicKitInternal0A22ConcertsRankingServiceV29processNotificationCandidatesySayAC0H0VGAA0adH7PayloadVYaKF
- _$s16MusicKitInternal0A22ConcertsRankingServiceV29processNotificationCandidatesySayAC0H0VGAA0adH7PayloadVYaKFTu
- _$s16MusicKitInternal0A24ConcertsRankingInterfaceP29processNotificationCandidatesyAA0A6DaemonV6ResultOy_AF11CodableVoidVGAA0adH7PayloadVYaFTq
- _$s16MusicKitInternal0A24ConcertsRankingInterfaceP29processNotificationCandidatesyAA0A6DaemonV6ResultOy_AF11CodableVoidVGAA0adH7PayloadVYaKFTqTE
CStrings:
+ "[ConcertsRanking] Failed to prune past scheduled notifications: %{public}s."
+ "[ConcertsRanking] Scheduled a notification but failed to record its concerts for dedupe: %{public}s."
+ "forgetNotifiedConcerts"
- "[ConcertsRanking] Re-ranking concerts before processing notifications."
```
