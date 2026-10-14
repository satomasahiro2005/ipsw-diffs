## SessionCore

> `/System/Library/PrivateFrameworks/SessionCore.framework/SessionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14e74c` | `0x14eecc` | **`+0x780`** |
| `__TEXT.__cstring` | `0x35b2` | `0x3622` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x7b14` | `0x7b74` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x3940` | `0x3970` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x2cb7` | `0x2cd7` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x2cbc` | `0x2cd4` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1e18` | `0x1e28` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x6130` | `0x6140` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x7070` | `0x7060` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2688` | `0x2698` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x4664` | `0x465c` | **`-0x8`** |

### Other Changes

```diff

-313.2.7.0.0
+313.2.9.0.0

-  Functions: 3582
+  Functions: 3586

-  CStrings:  848
+  CStrings:  852
Symbols:
+ ___swift_closure_destructor.38Tm
- ___swift_closure_destructor.39Tm
CStrings:
+ "Activity request blocked by alert scene target without user consent: %{public}s"
+ "Activity request blocked by content source without user consent: %{public}s"
+ "Activity request blocked by scene target without user consent: %{public}s"
+ "Alert scene target is restricted: %{public}s"
+ "Live Activities are not supported for this type of request: %{public}s"
+ "Push cannot assert user preconsent: %{public}s"
+ "Requester is entitled to create activities: %{public}s"
+ "Requester is foreground: %{public}s"
+ "Requester is not entitled to assert user preconsent: %{public}d"
+ "Requester is not foreground: %{public}s"
+ "Requester is not targeted by an activity request assertion: %{public}s"
+ "Requester is targeted by an activity request assertion: %{public}s"
+ "Scene target is restricted: %{public}s"
+ "com.apple.private.activitykit.userPreconsentAsserter"
+ "localizedAppNameBundleID"
- "Activity request blocked by alert scene target without user consent: %{private}s"
- "Activity request blocked by content source without user consent: %{private}s"
- "Activity request blocked by scene target without user consent: %{private}s"
- "Alert scene target is restricted: %{private}s"
- "Live Activities are not supported for this type of request: %{private}s"
- "Requester is entitled to create activities: %{private}s"
- "Requester is foreground: %{private}s"
- "Requester is not foreground: %{private}s"
- "Requester is not targeted by an activity request assertion: %{private}s"
- "Requester is targeted by an activity request assertion: %{private}s"
- "Scene target is restricted: %{private}s"
```
