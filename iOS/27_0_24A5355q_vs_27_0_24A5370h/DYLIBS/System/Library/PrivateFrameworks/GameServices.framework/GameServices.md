## GameServices

> `/System/Library/PrivateFrameworks/GameServices.framework/GameServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1677c8` | `0x16d740` | **`+0x5f78`** |
| `__TEXT.__eh_frame` | `0x18220` | `0x18b50` | **`+0x930`** |
| `__TEXT.__const` | `0x1e318` | `0x1e8c8` | **`+0x5b0`** |
| `__TEXT.__unwind_info` | `0x86f0` | `0x88e8` | **`+0x1f8`** |
| `__TEXT.__swift5_typeref` | `0x7a63` | `0x7be5` | **`+0x182`** |
| `__TEXT.__cstring` | `0x80d5` | `0x81c5` | **`+0xf0`** |
| `__TEXT.__swift5_acfuncs` | `0xe9c` | `0xf3c` | **`+0xa0`** |
| `__TEXT.__swift_as_cont` | `0x16c8` | `0x1748` | **`+0x80`** |
| `__TEXT.__swift_as_entry` | `0xbb4` | `0xc14` | **`+0x60`** |
| `__TEXT.__swift_as_ret` | `0xe74` | `0xed4` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x9578` | `0x95b8` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x3b08` | `0x3b48` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x1eb2` | `0x1ec2` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x41b0` | `0x41bc` | **`+0xc`** |
| `__DATA.__data` | `0x24c8` | `0x24d0` | **`+0x8`** |

### Other Changes

```diff

-821.0.13.1.2
+821.0.16.0.0

-  Functions: 11426
-  Symbols:   2774
-  CStrings:  474
+  Functions: 11527
+  Symbols:   2785
+  CStrings:  478
Symbols:
+ ___swift_memcpy25_8
+ _symbolic S2SSdxSb______p_____Rz_____RzlIetMHgTgTyTgdzo_ s5ErrorP 11Distributed01_B9ActorStubP 12GameServices0B23GamesCLIServiceProtocolP
+ _symbolic S2SSdxSb______p_____RzlIetWHgTgTyTgdzo_ s5ErrorP 12GameServices34DistributedGamesCLIServiceProtocolP
+ _symbolic SSSaySSGxSaySDyS2SGG______p_____Rz_____RzlIetMHgTgTgozo_ s5ErrorP 11Distributed01_B9ActorStubP 12GameServices0B23GamesCLIServiceProtocolP
+ _symbolic SSSaySSGxSaySDyS2SGG______p_____RzlIetWHgTgTgozo_ s5ErrorP 12GameServices34DistributedGamesCLIServiceProtocolP
+ _symbolic SSxSaySDyS2SGG______p_____Rz_____RzlIetMHgTgozo_ s5ErrorP 11Distributed01_B9ActorStubP 12GameServices0B23GamesCLIServiceProtocolP
+ _symbolic SSxSaySDyS2SGG______p_____RzlIetWHgTgozo_ s5ErrorP 12GameServices34DistributedGamesCLIServiceProtocolP
+ _symbolic SSx______p_____Rz_____RzlIetMHgTgzo_ s5ErrorP 11Distributed01_B9ActorStubP 12GameServices0B23GamesCLIServiceProtocolP
+ _symbolic SSx______p_____RzlIetWHgTgzo_ s5ErrorP 12GameServices34DistributedGamesCLIServiceProtocolP
+ _symbolic Si6status_SSSg7messaget
+ _symbolic ______AAt 12GameServices0aB13InternalErrorO
CStrings:
+ "dumpAchievementProgressRows(bundleID:)"
+ "readAchievementProgress(bundleID:achievementIDs:)"
+ "writeAchievementProgress(bundleID:achievementID:percentComplete:)"
+ "writeAchievementReset(bundleID:)"
```
