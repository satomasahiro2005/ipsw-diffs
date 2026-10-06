## AppPlaceholderSync

> `/System/Library/PrivateFrameworks/AppPlaceholderSync.framework/AppPlaceholderSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a1e4` | `0x2a430` | **`+0x24c`** |
| `__TEXT.__oslogstring` | `0xcbf` | `0xd2f` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0xba0` | `0xb80` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x5b0` | `0x5d0` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0xbb0` | `0xbd0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x37f` | `0x39f` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x61c` | `0x634` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x6e0` | `0x6ca` | **`-0x16`** |
| `__DATA_CONST.__const` | `0xf8` | `0x108` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x590` | `0x5a0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x398` | `0x3a4` | **`+0xc`** |
| `__TEXT.__swift5_capture` | `0xf8` | `0x100` | **`+0x8`** |

### Other Changes

```diff

-54.0.0.0.0
+54.1.1.0.0

-  Functions: 555
-  Symbols:   418
-  CStrings:  106
+  Functions: 563
+  Symbols:   413
+  CStrings:  108
Symbols:
+ _symbolic Sbz_Xx
+ _symbolic So17OS_dispatch_queueC
- _objc_retain_x26
- _swift_weakDestroy
- _swift_weakInit
- _swift_weakLoadStrong
- _symbolic So23SFAuthenticationManagerC
- _symbolic _____SgXw 18AppPlaceholderSync0C7ManagerC
- _symbolic _____SgXwz_Xx 18AppPlaceholderSync0C7ManagerC
CStrings:
+ "%s: skipping sync because paired devices is invalid"
+ "listCandidateDevices returned error: %{public}@"
+ "paired devices relationshipIDs: %{public}s"
- "paired devices relationshipIDS: %{public}s"
```
