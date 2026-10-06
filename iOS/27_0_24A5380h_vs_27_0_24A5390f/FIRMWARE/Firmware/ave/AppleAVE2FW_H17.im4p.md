## AppleAVE2FW_H17.im4p

> `Firmware/ave/AppleAVE2FW_H17.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1114c8` | `0x112768` | **`+0x12a0`** |
| `__TEXT.__cstring` | `0x17ab9` | `0x17c45` | **`+0x18c`** |
| `__TEXT.__const` | `0x266b4` | `0x266d4` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__TEXT.__chain_starts`

### Other Changes

```diff

-  Functions: 1218
-  Symbols:   1707
-  CStrings:  2690
+  Functions: 1221
+  Symbols:   1710
+  CStrings:  2698
Symbols:
+ __ZN10CAVEClient15GetCommandQueueE19_E_Proc_Mode_Queues
+ __ZN10CAVEClient22ProcessDirectFrameCmdsEi
+ __ZN9BlurRatio6updateERK10FrameStats
CStrings:
+ "!MIDR: 0x%x"
+ "%s: frameNum %d, bufIdx %d"
+ "%s::%s:%d  Failed to Queue AVE_Cmd_Process for client_id: %lld %lld"
+ "%s::%s:%d %s | Fail to dequeue frame %d"
+ "%s::%s:%d %s | Failed to enqueue frame %lld"
+ "%s::%s:%d BITBOX (%lld %lld) type %d current blur %d.%06d filtered blur %d.%06d transcodeBits %d cplxFiltered %d.%06d"
+ "%s::%s:%d Failed to Queue AVE_Cmd_Process for client_id: %lld %lld"
+ "9013.35.1"
+ "ProcessDirectFrameCmds"
+ "bDequeued"
+ "bEnqueueResult"
- "!MIDR: 0x%llx"
- "%s: bufIdx %d"
- "9013.12.1"
```
