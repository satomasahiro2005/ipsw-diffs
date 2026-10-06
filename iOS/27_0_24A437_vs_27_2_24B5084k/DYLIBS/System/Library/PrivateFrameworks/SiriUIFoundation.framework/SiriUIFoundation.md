## SiriUIFoundation

> `/System/Library/PrivateFrameworks/SiriUIFoundation.framework/SiriUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9195c` | `0x91fec` | **`+0x690`** |
| `__TEXT.__gcc_except_tab` | `0x984` | `0xa28` | **`+0xa4`** |
| `__AUTH_CONST.__const` | `0x3aa1` | `0x3b41` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x23c8` | `0x2458` | **`+0x90`** |
| `__TEXT.__cstring` | `0x6676` | `0x66e6` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x2738` | `0x2788` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x734` | `0x77c` | **`+0x48`** |
| `__TEXT.__const` | `0x387c` | `0x38bc` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x19b0` | `0x19d8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x9080` | `0x90a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x4748` | `0x4768` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x10fa` | `0x111a` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xf40` | `0xf28` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2fa8` | `0x2fc0` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xf7c` | `0xf94` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x1594` | `0x15aa` | **`+0x16`** |
| `__DATA_DIRTY.__data` | `0x9d0` | `0x9e0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x180` | `0x188` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x438` | `0x43c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xe8` | `0xec` | **`+0x4`** |

### Other Changes

```diff

-3600.55.37.11.4
+3605.22.2.0.0

-  Functions: 3376
-  Symbols:   3746
-  CStrings:  1129
+  Functions: 3392
+  Symbols:   3757
+  CStrings:  1132
Symbols:
+ +[SRUIFIntelligenceFlowFeatureFlag(SWEFeatureFlags) isDashboardCampoEnabled]
+ +[SRUIFSiriFeatureFlag(SWEFeatureFlags) isContinuousConversationHomepodEnabled]
+ _AFIsHorseman
+ _OBJC_IVAR_$_SRUIFAceCommandRecords._recordsQueue
+ ___47-[SRUIFAceCommandRecords _recordForAceCommand:]_block_invoke
+ ___51-[SRUIFAceCommandRecords aceCommandWithIdentifier:]_block_invoke
+ ___56-[SRUIFAceCommandRecords registerAceCommand:completion:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56bs64r_e5_v8?0ls32l8s40l8s48l8s56l8r64l8
+ ___swift_closure_destructor.64Tm
+ __dispatch_queue_attr_concurrent
+ _dispatch_barrier_sync
+ _symbolic So8NSStringC
+ _symbolic So8NSStringCSg
- ___block_descriptor_48_e8_32s40s_e48_v32?0"NSString"8"SRUIFAceCommandRecord"16^B24ls32l8s40l8
- ___swift_closure_destructor.57Tm
- _symbolic _____Sg 18AppIntentsServices0bC0O14InterfaceIdiomO
CStrings:
+ "-[SRUIFAceCommandRecords registerAceCommand:completion:]_block_invoke"
+ "DashboardCampo"
+ "com.apple.siriui.SRUIFAceCommandRecords"
+ "continuous_conversation_homepod"
- "v32@?0@\"NSString\"8@\"SRUIFAceCommandRecord\"16^B24"
```
