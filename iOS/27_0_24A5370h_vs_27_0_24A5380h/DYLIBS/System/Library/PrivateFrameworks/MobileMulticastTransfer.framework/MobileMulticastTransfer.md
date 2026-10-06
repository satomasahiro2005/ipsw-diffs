## MobileMulticastTransfer

> `/System/Library/PrivateFrameworks/MobileMulticastTransfer.framework/MobileMulticastTransfer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38430` | `0x37f54` | **`-0x4dc`** |
| `__TEXT.__oslogstring` | `0x51f9` | `0x510f` | **`-0xea`** |
| `__AUTH_CONST.__const` | `0x31a0` | `0x3120` | **`-0x80`** |
| `__AUTH_CONST.__cfstring` | `0xba0` | `0xb80` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x5038` | `0x5018` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0xe98` | `0xe78` | **`-0x20`** |
| `__TEXT.__cstring` | `0x109d` | `0x1091` | **`-0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0xf98` | `0xf90` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x1868` | `0x1860` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x2c0` | `0x2bc` | **`-0x4`** |

### Other Changes

```diff

-266.0.0.0.0
+274.0.0.0.0

-  Functions: 1603
-  Symbols:   1597
-  CStrings:  574
+  Functions: 1594
+  Symbols:   1593
+  CStrings:  569
Symbols:
+ -[MIBUNWServerController _fetchOneBatchOfPacketsWithDelay:]
+ ___59-[MIBUNWServerController _fetchOneBatchOfPacketsWithDelay:]_block_invoke
+ ___59-[MIBUNWServerController _fetchOneBatchOfPacketsWithDelay:]_block_invoke_2
- -[MIBUNWClientController stopMulticast]
- -[MIBUNWServerController _fetchOneBatchOfPacketsFromProvider]
- _OBJC_IVAR_$_MIBUNWClientController._multicastSocketSem
- ___39-[MIBUNWClientController stopMulticast]_block_invoke
- ___39-[MIBUNWClientController stopMulticast]_block_invoke_2
- ___61-[MIBUNWServerController _fetchOneBatchOfPacketsFromProvider]_block_invoke
- ___61-[MIBUNWServerController _fetchOneBatchOfPacketsFromProvider]_block_invoke_2
CStrings:
+ "%{public}@: Ignoring packet reception completion (state=%lu)"
+ "Reached EOF of packet provider!"
- "%{public}@: Ignoring extra packet reception completion"
- "%{public}@: Multicast semaphore signaled, stopMulticast complete"
- "%{public}@: Signaling multicast socket semaphore"
- "%{public}@: Waiting on multicast semaphore..."
- "%{public}@: stopMulticast called, waiting for multicast to stop..."
- "EOF Reached"
- "Reached EOF of packet provider! We are done!"
```
