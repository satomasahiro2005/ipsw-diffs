## CoreSpeechFoundation

> `/System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/CoreSpeechFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcd774` | `0xcd8fc` | **`+0x188`** |
| `__TEXT.__oslogstring` | `0x11bfb` | `0x11c58` | **`+0x5d`** |
| `__TEXT.__cstring` | `0x16adf` | `0x16b38` | **`+0x59`** |
| `__AUTH_CONST.__cfstring` | `0x9a40` | `0x9a60` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x14ff8` | `0x15018` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x28c0` | `0x28c8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7588` | `0x7590` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xdb10` | `0xdb18` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3e80` | `0x3e88` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xdac` | `0xdb0` | **`+0x4`** |

### Other Changes

```diff

-3605.23.1.0.0
+3605.25.1.0.0

-  Functions: 5275
-  Symbols:   9899
-  CStrings:  3790
+  Functions: 5276
+  Symbols:   9902
+  CStrings:  3793
Symbols:
+ -[CSAudioConsumingStateMonitor backdateSessionStartBySeconds:]
+ GCC_except_table3670
+ GCC_except_table3730
+ GCC_except_table3744
+ GCC_except_table3787
+ GCC_except_table3817
+ GCC_except_table3819
+ GCC_except_table3824
+ GCC_except_table3847
+ GCC_except_table3849
+ GCC_except_table3855
+ GCC_except_table3860
+ GCC_except_table3886
+ GCC_except_table3912
+ GCC_except_table3933
+ GCC_except_table3956
+ GCC_except_table3966
+ GCC_except_table4058
+ GCC_except_table4067
+ GCC_except_table4072
+ GCC_except_table4076
+ GCC_except_table4087
+ GCC_except_table4091
+ GCC_except_table4098
+ GCC_except_table4100
+ GCC_except_table4103
+ GCC_except_table4106
+ GCC_except_table4110
+ GCC_except_table4115
+ GCC_except_table4119
+ GCC_except_table4122
+ GCC_except_table4127
+ GCC_except_table4155
+ GCC_except_table4205
+ GCC_except_table4209
+ GCC_except_table4261
+ GCC_except_table4271
+ GCC_except_table4274
+ GCC_except_table4295
+ GCC_except_table4299
+ GCC_except_table4308
+ GCC_except_table4320
+ GCC_except_table4329
+ GCC_except_table4337
+ GCC_except_table4339
+ GCC_except_table4346
+ GCC_except_table4348
+ GCC_except_table4351
+ GCC_except_table4353
+ GCC_except_table4355
+ GCC_except_table4357
+ GCC_except_table4359
+ GCC_except_table4366
+ GCC_except_table4380
+ GCC_except_table4383
+ GCC_except_table4385
+ GCC_except_table4389
+ GCC_except_table4394
+ GCC_except_table4396
+ GCC_except_table4401
+ GCC_except_table4431
+ GCC_except_table4543
+ GCC_except_table4550
+ GCC_except_table4633
+ GCC_except_table4700
+ GCC_except_table4710
+ GCC_except_table4768
+ GCC_except_table4775
+ GCC_except_table4778
+ GCC_except_table4780
+ GCC_except_table4783
+ GCC_except_table4785
+ GCC_except_table4821
+ GCC_except_table4887
+ GCC_except_table4892
+ GCC_except_table4933
+ GCC_except_table4999
+ _OBJC_IVAR_$_CSAudioConsumingStateMonitor._audioConsumingStartHostTime
+ _kCSDiagnosticReporterAudioConsumingSessionStale
- GCC_except_table3669
- GCC_except_table3729
- GCC_except_table3743
- GCC_except_table3785
- GCC_except_table3815
- GCC_except_table3818
- GCC_except_table3821
- GCC_except_table3846
- GCC_except_table3848
- GCC_except_table3852
- GCC_except_table3859
- GCC_except_table3885
- GCC_except_table3911
- GCC_except_table3932
- GCC_except_table3952
- GCC_except_table3965
- GCC_except_table4056
- GCC_except_table4066
- GCC_except_table4068
- GCC_except_table4074
- GCC_except_table4078
- GCC_except_table4089
- GCC_except_table4096
- GCC_except_table4099
- GCC_except_table4101
- GCC_except_table4104
- GCC_except_table4108
- GCC_except_table4112
- GCC_except_table4116
- GCC_except_table4120
- GCC_except_table4123
- GCC_except_table4154
- GCC_except_table4204
- GCC_except_table4208
- GCC_except_table4259
- GCC_except_table4267
- GCC_except_table4272
- GCC_except_table4294
- GCC_except_table4296
- GCC_except_table4300
- GCC_except_table4319
- GCC_except_table4328
- GCC_except_table4330
- GCC_except_table4338
- GCC_except_table4340
- GCC_except_table4347
- GCC_except_table4349
- GCC_except_table4352
- GCC_except_table4354
- GCC_except_table4356
- GCC_except_table4358
- GCC_except_table4365
- GCC_except_table4378
- GCC_except_table4381
- GCC_except_table4384
- GCC_except_table4386
- GCC_except_table4393
- GCC_except_table4395
- GCC_except_table4399
- GCC_except_table4430
- GCC_except_table4542
- GCC_except_table4549
- GCC_except_table4632
- GCC_except_table4699
- GCC_except_table4709
- GCC_except_table4765
- GCC_except_table4769
- GCC_except_table4776
- GCC_except_table4779
- GCC_except_table4781
- GCC_except_table4784
- GCC_except_table4820
- GCC_except_table4886
- GCC_except_table4891
- GCC_except_table4932
- GCC_except_table4998
Functions:
~ -[CSAudioConsumingStateMonitor _setAudioConsumingActive:] : 180 -> 200
~ -[CSAudioConsumingStateMonitor isAudioConsumingSessionActive] : 84 -> 336
+ -[CSAudioConsumingStateMonitor backdateSessionStartBySeconds:]
CStrings:
+ "%s Audio consuming session active for %.1fs with no stop notification; resetting stale state"
+ "-[CSAudioConsumingStateMonitor isAudioConsumingSessionActive]"
+ "audioConsumingSessionStale"
```
