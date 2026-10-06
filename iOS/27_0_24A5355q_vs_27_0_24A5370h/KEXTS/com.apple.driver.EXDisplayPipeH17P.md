## com.apple.driver.EXDisplayPipeH17P

> `com.apple.driver.EXDisplayPipeH17P`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x4b0` | **`+0x4b0`** |
| `__TEXT_EXEC.__text` | `0x98e8` | `0x99c8` | **`+0xe0`** |

### Other Changes

```diff

-9.1.40.0.0
+9.1.42.0.0
Functions:
~ sub_fffffff009b4e678 -> sub_fffffff009bb4f38 : 88 -> 92
~ sub_fffffff009b4ebcc -> sub_fffffff009bb5490 : 364 -> 376
~ sub_fffffff009b4ed38 -> sub_fffffff009bb5608 : 64 -> 72
~ sub_fffffff009b4ed78 -> sub_fffffff009bb5650 : 64 -> 72
~ __ZN13EXDisplayPipe18dumpCancelledQueueE19EXDisplayPipeStatus : 144 -> 140
~ __ZN13EXDisplayPipe16dumpDroppedQueueE19EXDisplayPipeStatus : 140 -> 136
~ sub_fffffff009b4f698 -> sub_fffffff009bb5f70 : 180 -> 184
~ __ZZN13EXDisplayPipe13setIndicatorsEPK19EXDisplayPipeStatusEN3$_08__invokeEP8OSObjectPvS6_S6_S6_ : 484 -> 496
~ sub_fffffff009b4f940 -> sub_fffffff009bb6228 : 256 -> 260
~ __ZZN13EXDisplayPipe9getStatusEP19EXDisplayPipeStatusEN3$_08__invokeEP8OSObjectPvS5_S5_S5_ : 772 -> 828
~ __ZZN13EXDisplayPipe17getSecureTEStatusEP27EXDisplayPipeSecureTEStatusEN3$_08__invokeEP8OSObjectPvS5_S5_S5_ : 460 -> 504
~ __ZN13EXDisplayPipe5startEP9IOService : 876 -> 888
~ __ZN13EXDisplayPipe16setup_interruptsEv : 248 -> 252
~ sub_fffffff009b52634 -> sub_fffffff009bb8f94 : 1344 -> 1340
~ __ZZN13EXDisplayPipe19getSCASessionHealthEPjEN3$_08__invokeEP8OSObjectPvS4_S4_S4_ : 428 -> 424
~ sub_fffffff009b561a0 -> sub_fffffff009bbcaf8 : 404 -> 416
~ sub_fffffff009b564f8 -> sub_fffffff009bbce5c : 240 -> 260
~ sub_fffffff009b566b4 -> sub_fffffff009bbd02c : 396 -> 420
~ sub_fffffff009b5706c -> sub_fffffff009bbd9fc : 836 -> 852
```
