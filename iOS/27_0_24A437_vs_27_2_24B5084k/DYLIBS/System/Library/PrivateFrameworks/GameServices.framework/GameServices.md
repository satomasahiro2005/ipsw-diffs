## GameServices

> `/System/Library/PrivateFrameworks/GameServices.framework/GameServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16fe24` | `0x16f308` | **`-0xb1c`** |
| `__TEXT.__eh_frame` | `0x18d78` | `0x18ab0` | **`-0x2c8`** |
| `__TEXT.__const` | `0x1ece8` | `0x1eb48` | **`-0x1a0`** |
| `__AUTH_CONST.__const` | `0x9660` | `0x9760` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x8df8` | `0x8d70` | **`-0x88`** |
| `__AUTH_CONST.__auth_got` | `0xcd8` | `0xd50` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0x7c45` | `0x7be3` | **`-0x62`** |
| `__TEXT.__swift5_capture` | `0x19c` | `0x1fc` | **`+0x60`** |
| `__TEXT.__cstring` | `0x82c5` | `0x8295` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x39e` | `0x3ce` | **`+0x30`** |
| `__TEXT.__swift5_acfuncs` | `0xf78` | `0xf50` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0x178c` | `0x176c` | **`-0x20`** |
| `__TEXT.__swift_as_entry` | `0xc40` | `0xc28` | **`-0x18`** |
| `__TEXT.__swift_as_ret` | `0xf04` | `0xeec` | **`-0x18`** |
| `__DATA.__bss` | `0x232f0` | `0x23300` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x4224` | `0x4234` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x3bac` | `0x3bb8` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x44c` | `0x450` | **`+0x4`** |
| `__DATA.__common` | `0x8` | `0x9` | **`+0x1`** |

### Other Changes

```diff

-821.0.25.0.0
+821.1.8.0.0

-  Functions: 11628
-  Symbols:   2794
-  CStrings:  481
+  Functions: 11618
+  Symbols:   2796
+  CStrings:  483
Symbols:
+ ___swift_closure_destructor.125Tm
+ __os_signpost_emit_with_name_impl
+ _os_variant_has_internal_ui
+ _symbolic _____ 12GameServices11PreferencesO
- _symbolic SSSaySSGxSaySDyS2SGG______p_____Rz_____RzlIetMHgTgTgozo_ s5ErrorP 11Distributed01_B9ActorStubP 12GameServices0B23GamesCLIServiceProtocolP
- _symbolic SSSaySSGxSaySDyS2SGG______p_____RzlIetWHgTgTgozo_ s5ErrorP 12GameServices34DistributedGamesCLIServiceProtocolP
CStrings:
+ "LocalExecute"
+ "RemoteCall"
+ "[Error] Interval already ended"
+ "actor=%{public}s target=%{public}s"
- "dumpAchievementProgressRows(bundleID:)"
- "readAchievementProgress(bundleID:achievementIDs:)"
```
