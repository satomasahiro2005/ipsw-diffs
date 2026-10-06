## ANEServices

> `/System/Library/PrivateFrameworks/ANEServices.framework/ANEServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a2ec` | `0x4a3e0` | **`+0xf4`** |
| `__TEXT.__oslogstring` | `0x4bfb` | `0x4c88` | **`+0x8d`** |
| `__AUTH_CONST.__auth_got` | `0x6e8` | `0x6f8` | **`+0x10`** |
| `__TEXT.__const` | `0x276d` | `0x2775` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x13a8` | `0x13b0` | **`+0x8`** |

### Other Changes

```diff

-10.14.2.0.0
+10.15.4.0.0

-  Functions: 2114
-  Symbols:   2382
-  CStrings:  892
+  Functions: 2116
+  Symbols:   2384
+  CStrings:  895
Symbols:
+ __ZN3ANE17ANECreateCVBufferEjjjj14ANEFrameFormatbjjjbjb
+ __ZN3ANE21ANECreateCVBufferPoolEjjjj14ANEFrameFormatlbjjjbjb
+ __ZN3ANE28ANERequestReceiverBufferPoolC1ENS_32ANERequestReceiverBufferPoolTypeEjjjjj14ANEFrameFormatbjjjjjjb
+ __ZN3ANE28ANERequestReceiverBufferPoolC2ENS_32ANERequestReceiverBufferPoolTypeEjjjjj14ANEFrameFormatbjjjjjjb
+ _mach_vm_allocate
+ _mach_vm_deallocate
- __ZN3ANE17ANECreateCVBufferEjjjj14ANEFrameFormatbjjjbj
- __ZN3ANE21ANECreateCVBufferPoolEjjjj14ANEFrameFormatlbjjjbj
- __ZN3ANE28ANERequestReceiverBufferPoolC1ENS_32ANERequestReceiverBufferPoolTypeEjjjjj14ANEFrameFormatbjjjjjj
- __ZN3ANE28ANERequestReceiverBufferPoolC2ENS_32ANERequestReceiverBufferPoolTypeEjjjjj14ANEFrameFormatbjjjjjj
CStrings:
+ "baseModelWiredMemorySize is 0\n"
+ "mach_vm_allocate() failed. error: 0x%x\n"
+ "prodAddr=%llx progHandle=%llx model=%{public}s"
+ "progHandle=%llx instanceHandle=%llx model=%{public}s"
- "prodAddr=%llx progHandle=%llx"
```
