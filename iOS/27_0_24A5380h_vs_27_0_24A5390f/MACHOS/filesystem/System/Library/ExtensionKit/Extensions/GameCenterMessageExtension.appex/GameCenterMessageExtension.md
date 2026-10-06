## GameCenterMessageExtension

> `/System/Library/ExtensionKit/Extensions/GameCenterMessageExtension.appex/GameCenterMessageExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3be94` | `0x3b638` | **`-0x85c`** |
| `__TEXT.__objc_methtype` | `0x50f` | `0x57f` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x2ef0` | `0x2eaa` | **`-0x46`** |
| `__TEXT.__auth_stubs` | `0x1940` | `0x1930` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x2dbd` | `0x2dcd` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xbe0` | `0xbd0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xca8` | `0xca0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-821.0.18.0.0
+821.0.20.0.0

-  Functions: 1200
-  Symbols:   305
-  CStrings:  698
+  Functions: 1199
+  Symbols:   304
+  CStrings:  702
Symbols:
- _swift_unknownObjectWeakAssign
CStrings:
+ "@\"GKDashboardPlayerPhotoView\""
+ "@\"UIActivityIndicatorView\""
+ "@\"UIButton\""
+ "@\"UIView\""
+ "@\"UIVisualEffectView\""
+ "T@\"GKDashboardPlayerPhotoView\",N,&,VfriendAvatarView"
+ "T@\"GKDashboardPlayerPhotoView\",N,&,VplayerAvatarView"
+ "T@\"UIActivityIndicatorView\",N,&,VactivityIndicator"
+ "T@\"UIButton\",N,&,VacceptButton"
+ "T@\"UIButton\",N,&,VactionButton"
+ "T@\"UIButton\",N,&,VignoreButton"
+ "T@\"UIButton\",N,&,VreceiverActionStatus"
+ "T@\"UIImageView\",N,&,VgameCenterPhoto"
+ "T@\"UILabel\",N,&,VachievementsCountLabel"
+ "T@\"UILabel\",N,&,VachievementsLabel"
+ "T@\"UILabel\",N,&,VactionLabel"
+ "T@\"UILabel\",N,&,VdescriptionLabel"
+ "T@\"UILabel\",N,&,VedgeCaseStateLabel"
+ "T@\"UILabel\",N,&,VerrorStateLabel"
+ "T@\"UILabel\",N,&,VfriendsCountLabel"
+ "T@\"UILabel\",N,&,VfriendsLabel"
+ "T@\"UILabel\",N,&,VgameCenterLabel"
+ "T@\"UILabel\",N,&,VgamesCountLabel"
+ "T@\"UILabel\",N,&,VgamesLabel"
+ "T@\"UILabel\",N,&,VinviteStatusInfoLabel"
+ "T@\"UILabel\",N,&,Vlabel"
+ "T@\"UILabel\",N,&,VplayerName"
+ "T@\"UILabel\",N,&,VsecondSubtitleLabel"
+ "T@\"UILabel\",N,&,VsubTitle"
+ "T@\"UILabel\",N,&,VsubtitleLabel"
+ "T@\"UILabel\",N,&,VtitleLabel"
+ "T@\"UILabel\",N,&,VtryAgainLabel"
+ "T@\"UILabel\",N,&,VviewFriendsLabel"
+ "T@\"UIStackView\",N,&,VbuttonsStackView"
+ "T@\"UIStackView\",N,&,VinviteAcceptedStackView"
+ "T@\"UIStackView\",N,&,VplayerProfileInfoBarAndButtonStackView"
+ "T@\"UIStackView\",N,&,VplayerProfileInfoBarStackView"
+ "T@\"UIStackView\",N,&,VreceiverInfoStackView"
+ "T@\"UIView\",N,&,VdividerView"
+ "T@\"UIView\",N,&,VmainContainer"
+ "T@\"UIVisualEffectView\",N,&,VeffectsView"
- "?"
- "T@\"GKDashboardPlayerPhotoView\",N,W,VfriendAvatarView"
- "T@\"GKDashboardPlayerPhotoView\",N,W,VplayerAvatarView"
- "T@\"UIActivityIndicatorView\",N,W,VactivityIndicator"
- "T@\"UIButton\",N,W,VacceptButton"
- "T@\"UIButton\",N,W,VactionButton"
- "T@\"UIButton\",N,W,VignoreButton"
- "T@\"UIButton\",N,W,VreceiverActionStatus"
- "T@\"UIImageView\",N,W,VgameCenterPhoto"
- "T@\"UILabel\",N,W,VachievementsCountLabel"
- "T@\"UILabel\",N,W,VachievementsLabel"
- "T@\"UILabel\",N,W,VactionLabel"
- "T@\"UILabel\",N,W,VdescriptionLabel"
- "T@\"UILabel\",N,W,VedgeCaseStateLabel"
- "T@\"UILabel\",N,W,VerrorStateLabel"
- "T@\"UILabel\",N,W,VfriendsCountLabel"
- "T@\"UILabel\",N,W,VfriendsLabel"
- "T@\"UILabel\",N,W,VgameCenterLabel"
- "T@\"UILabel\",N,W,VgamesCountLabel"
- "T@\"UILabel\",N,W,VgamesLabel"
- "T@\"UILabel\",N,W,VinviteStatusInfoLabel"
- "T@\"UILabel\",N,W,Vlabel"
- "T@\"UILabel\",N,W,VplayerName"
- "T@\"UILabel\",N,W,VsecondSubtitleLabel"
- "T@\"UILabel\",N,W,VsubTitle"
- "T@\"UILabel\",N,W,VsubtitleLabel"
- "T@\"UILabel\",N,W,VtitleLabel"
- "T@\"UILabel\",N,W,VtryAgainLabel"
- "T@\"UILabel\",N,W,VviewFriendsLabel"
- "T@\"UIStackView\",N,W,VbuttonsStackView"
- "T@\"UIStackView\",N,W,VinviteAcceptedStackView"
- "T@\"UIStackView\",N,W,VplayerProfileInfoBarAndButtonStackView"
- "T@\"UIStackView\",N,W,VplayerProfileInfoBarStackView"
- "T@\"UIStackView\",N,W,VreceiverInfoStackView"
- "T@\"UIView\",N,W,VdividerView"
- "T@\"UIView\",N,W,VmainContainer"
- "T@\"UIVisualEffectView\",N,W,VeffectsView"
```
