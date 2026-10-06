## GRPCCoreInternal

> `/System/Library/PrivateFrameworks/GRPCCoreInternal.framework/GRPCCoreInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7fbf8` | `0x800b0` | **`+0x4b8`** |
| `__TEXT.__eh_frame` | `0x58ac` | `0x598c` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x1ace` | `0x1af6` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2ac0` | `0x2ae8` | **`+0x28`** |
| `__DATA.__data` | `0x5c8` | `0x5b0` | **`-0x18`** |
| `__TEXT.__const` | `0x6ee0` | `0x6ed0` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x2e4` | `0x2ec` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x34c` | `0x354` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x424` | `0x428` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 3404
-  Symbols:   885
+  Functions: 3402
+  Symbols:   883
Symbols:
+ ___swift_closure_destructor.85Tm
+ ___swift_get_extra_inhabitant_index.71Tm
+ ___swift_store_extra_inhabitant_index.72Tm
+ _swift_task_localValuePop
+ _swift_task_localValuePush
+ _symbolic _____y_____y_xq_q0_q1_q2__GG 15Synchronization5MutexVAARi_zrlE 16GRPCCoreInternal17ClientRPCExecutorO15HedgingExecutorV5StateV
+ _symbolic _____y_____yxGG 15Synchronization5MutexVAARi_zrlE 16GRPCCoreInternal30_BroadcastSequenceStateMachineV
+ _symbolic _____y_____yx_GG 15Synchronization5MutexVAARi_zrlE 16GRPCCoreInternal10GRPCClientC12StateMachine33_BC70E0D9488AC3548B2965497CE0033BLLV
+ _symbolic _____y_____yx_GG 15Synchronization5MutexVAARi_zrlE 16GRPCCoreInternal10GRPCServerC5State33_B94F2B811610C609704BC2144BDB94DELLO
- ___swift_closure_destructor.86Tm
- ___swift_get_extra_inhabitant_index.72Tm
- ___swift_store_extra_inhabitant_index.73Tm
- _get_type_metadata 15Synchronization5MutexVy16GRPCCoreInternal25ServerCancellationManagerC5StateVG noncopyable
- _get_type_metadata 15Synchronization5MutexVySiG noncopyable
- _get_type_metadata 16GRPCCoreInternal15ClientTransportRzl15Synchronization5MutexVyAA10GRPCClientC12StateMachine33_BC70E0D9488AC3548B2965497CE0033BLLVyx_GG noncopyable
- _get_type_metadata 16GRPCCoreInternal15ClientTransportRzs8SendableR_7MessageQy1_Rs_sACR0_ADQy2_Rs0_AA0F10SerializerR1_AA0F12DeserializerR2_r3_l15Synchronization5MutexVyAA0C11RPCExecutorO15HedgingExecutorV5StateVy_xq_q0_q1_q2__GG noncopyable
- _get_type_metadata 16GRPCCoreInternal15ServerTransportRzl15Synchronization5MutexVyAA10GRPCServerC5State33_B94F2B811610C609704BC2144BDB94DELLOyx_GG noncopyable
- _get_type_metadata ScIRzl15Synchronization6AtomicVySbG noncopyable
- _get_type_metadata s8SendableRzl15Synchronization5MutexVy16GRPCCoreInternal30_BroadcastSequenceStateMachineVyxGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
```
