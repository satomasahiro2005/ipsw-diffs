## CallsXPC

> `/System/Library/PrivateFrameworks/CallsXPC.framework/CallsXPC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x192a0` | `0x18f28` | **`-0x378`** |
| `__TEXT.__swift5_typeref` | `0x701` | `0x799` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x798` | `0x770` | **`-0x28`** |
| `__TEXT.__const` | `0x11e0` | `0x11c0` | **`-0x20`** |
| `__DATA.__data` | `0x78` | `0x68` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x8c0` | `0x8c8` | **`+0x8`** |

### Other Changes

```diff

-143.100.11.2.1
+145.100.7.2.1

-  Functions: 531
-  Symbols:   328
+  Functions: 525
+  Symbols:   326
Symbols:
+ ___swift_closure_destructor.26Tm
+ ___swift_closure_destructor.77Tm
+ _symbolic _____ySDySS_____yx_G_____nYu______y14ClientMessages_____QzGtYbcGG 15Synchronization5MutexVAARi_zrlE 8CallsXPC7XPCHostC12MessageReply33_486BE1C75C58B5FF152E39684162B14CLLO 0D0011XPCReceivedF0V AD15TypedPayloadBoxV AD12XPCInterfaceP
+ _symbolic _____ySDySSy_____nYu______y12HostMessages_____QzGtYaYbcGG 15Synchronization5MutexVAARi_zrlE 3XPC18XPCReceivedMessageV 05CallsC015TypedPayloadBoxV AG12XPCInterfaceP
+ _symbolic _____ySay_____yxGGG 15Synchronization5MutexVAARi_zrlE 8CallsXPC17XPCHostConnectionC
+ _symbolic _____yxSgG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____yy_____yxG_______ptYbcSgG 15Synchronization5MutexVAARi_zrlE 8CallsXPC17XPCHostConnectionC s5ErrorP
- ___swift_closure_destructor.30Tm
- ___swift_closure_destructor.81Tm
- _get_type_metadata 8CallsXPC12XPCInterfaceRzl15Synchronization5MutexVySDySSAA7XPCHostC12MessageReply33_486BE1C75C58B5FF152E39684162B14CLLOyx_G0B0011XPCReceivedG0VnYu_AA15TypedPayloadBoxVy14ClientMessagesQzGtYbcGG noncopyable
- _get_type_metadata 8CallsXPC12XPCInterfaceRzl15Synchronization5MutexVySDySSy0B018XPCReceivedMessageVnYu_AA15TypedPayloadBoxVy12HostMessagesQzGtYaYbcGG noncopyable
- _get_type_metadata 8CallsXPC12XPCInterfaceRzl15Synchronization5MutexVySayAA17XPCHostConnectionCyxGGG noncopyable
- _get_type_metadata 8CallsXPC12XPCInterfaceRzl15Synchronization5MutexVyyAA17XPCHostConnectionCyxG_s5Error_ptYbcSgG noncopyable
- _get_type_metadata 8CallsXPC12XPCInterfaceRzl15Synchronization5MutexVyys5Error_pYbcSgG noncopyable
- _get_type_metadata s8SendableRzl15Synchronization5MutexVyxSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
```
