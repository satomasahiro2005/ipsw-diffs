## RequestDispatcherBridges

> `/System/Library/PrivateFrameworks/RequestDispatcherBridges.framework/RequestDispatcherBridges`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10ef48` | `0x1122d8` | **`+0x3390`** |
| `__TEXT.__oslogstring` | `0xc527` | `0xc7c7` | **`+0x2a0`** |
| `__AUTH_CONST.__objc_const` | `0x73a0` | `0x7470` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x2024` | `0x20c4` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x7268` | `0x72f0` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0x2e6c` | `0x2eac` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x3270` | `0x32a0` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x2171` | `0x21a1` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x2e28` | `0x2e48` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2878` | `0x2898` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x670` | `0x688` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x9e8` | `0xa00` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xbf8` | `0xc08` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x888` | `0x898` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1a6c` | `0x1a78` | **`+0xc`** |
| `__DATA.__common` | `0x1f8` | `0x200` | **`+0x8`** |
| `__TEXT.__const` | `0x51d8` | `0x51d0` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x3a0` | `0x3a8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x2cc` | `0x2d4` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x364` | `0x368` | **`+0x4`** |

### Other Changes

```diff

-3600.54.24.11.1
+3605.18.1.0.0

-  Functions: 2888
-  Symbols:   1273
-  CStrings:  837
+  Functions: 2902
+  Symbols:   1274
+  CStrings:  847
Symbols:
+ _OBJC_CLASS_$_SAUIPerformAppIntent
+ ___swift_closure_destructor.6Tm
- ___swift_closure_destructor.5Tm
CStrings:
+ "MUX: Discarding stale pendingUserIdentificationMessage (requestId: %s) — does not match local request %s"
+ "MUX: No processor found for UserIdentificationMessage with requestId: %s — caching at session level"
+ "MUX: Setting selectedUserId=%s source=%s"
+ "MUX: Unexpected processor-level UserIdentificationMessage on local request %s; using session-level cache"
+ "MUX: Using pre-seeded UserIdentificationMessage for local request with userId: %s"
+ "MUX: makeEagerChildRequest userId=%{private}s (fellBackToSessionUser=%{bool,public}d)"
+ "SessionEndedMessage for a session this bridge does not own. Skipping IF session cleanup."
+ "UserIdentificationMessage"
+ "activateFlexibleFollowUpSecureRemoteMic(withTimestamp:deviceId:context:completion:)"
+ "activeUserSharedUserId"
```
