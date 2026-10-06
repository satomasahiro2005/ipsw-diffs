## UserNotificationsUIKit

> `/System/Library/PrivateFrameworks/UserNotificationsUIKit.framework/UserNotificationsUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bf0a0` | `0x1be9e8` | **`-0x6b8`** |
| `__TEXT.__oslogstring` | `0x10359` | `0x10199` | **`-0x1c0`** |
| `__DATA_DIRTY.__data` | `0x16a0` | `0x15b0` | **`-0xf0`** |
| `__AUTH_CONST.__const` | `0x50f8` | `0x5058` | **`-0xa0`** |
| `__DATA.__data` | `0x5100` | `0x5190` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x26bb8` | `0x26b30` | **`-0x88`** |
| `__TEXT.__constg_swiftt` | `0x1bdc` | `0x1b80` | **`-0x5c`** |
| `__DATA_CONST.__got` | `0x1858` | `0x1898` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x3ce2` | `0x3d20` | **`+0x3e`** |
| `__TEXT.__cstring` | `0xa02d` | `0x9ffd` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x1ae1c` | `0x1ae44` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x7380` | `0x7358` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x7f40` | `0x7f60` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x10e8` | `0x10cc` | **`-0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0xcc68` | `0xcc80` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0xd84` | `0xd74` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1558` | `0x1560` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x800` | `0x7f8` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x128` | `0x124` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-1077.2.4.100.0
+1077.2.7.0.0

-  Functions: 10982
-  Symbols:   14479
-  CStrings:  2174
+  Functions: 10970
+  Symbols:   14477
+  CStrings:  2164
Symbols:
+ -[NCCarPlayBannerSource _shouldPresentableBorrowCarPlayScreenOnInteraction:]
+ GCC_except_table40
+ _OBJC_CLASS_$__UIAppAttribution
+ ___swift_closure_destructor.157Tm
+ _symbolic _____Sg So17OS_dispatch_queueC8DispatchE17SchedulerTimeTypeV6StrideV
+ _symbolic _____y______yytGSo17OS_dispatch_queueCG 7Combine10PublishersO5DelayV AA4JustV
+ _symbolic _____y______yyt_____G_____y______yytACGADGG 7Combine10PublishersO14SwitchToLatestV AA12AnyPublisherV s5NeverO AC3MapV AA18PassthroughSubjectC
+ _symbolic _____y______yyt_____G_____yytACGG 7Combine10PublishersO3MapV AA18PassthroughSubjectC s5NeverO AA12AnyPublisherV
+ _symbolic _____yytG 7Combine4JustV
+ _symbolic _____yyt_____G 7Combine12AnyPublisherV s5NeverO
- __DATA__TtC22UserNotificationsUIKit17AutomationService
- __IVARS__TtC22UserNotificationsUIKit17AutomationService
- __METACLASS_DATA__TtC22UserNotificationsUIKit17AutomationService
- ___swift_closure_destructor.171Tm
- _notify_register_dispatch
- _swift_unknownObjectUnownedAssign
- _swift_unknownObjectUnownedDestroy
- _swift_unknownObjectUnownedInit
- _swift_unknownObjectUnownedLoadStrong
- _symbolic So28NCNotificationRootModernListCSgXo
- _symbolic _____ 22UserNotificationsUIKit17AutomationServiceC
- _symbolic _____y______yyt_____GSo17OS_dispatch_queueCG 7Combine10PublishersO8DebounceV AA18PassthroughSubjectC s5NeverO
CStrings:
+ "%{public}s. File:%{public}s line: %{public}lu"
+ "CRSUIBannerInteractionShouldBorrowScreenKey"
- "Calculated exclusionZones: %{public}s"
- "Calculated pages: %{public}s"
- "Incoming revealed: %{bool,public}d, History revealed: %{bool,public}d"
- "Scroll position invalid because it's below count"
- "Scroll position is currently in exclusion zone"
- "Scroll position is valid: %{bool,public}d"
- "Scroll view is tracking"
- "ScrollToNearestPage"
- "This is only valid while it is animating, not as a resting position"
- "ValidateScrollPosition"
- "Verifying scroll position... Current offset: %{public}f"
- "verifyScrollPositionValid"
```
