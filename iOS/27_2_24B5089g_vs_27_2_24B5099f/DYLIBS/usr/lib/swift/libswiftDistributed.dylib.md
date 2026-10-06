## libswiftDistributed.dylib

> `/usr/lib/swift/libswiftDistributed.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `0x120` | `—` | **`-0x120`** |
| `__DATA_DIRTY.__data` | `0x2b0` | `0x3d0` | **`+0x120`** |
| `__TEXT.__text` | `0xb554` | `0xb434` | **`-0x120`** |
| `__DATA_DIRTY.__bss` | `0x120` | `0x130` | **`+0x10`** |

### Other Changes

```diff

-6.4.0.34.1
+6.4.2.1.7

-  Functions: 367
-  Symbols:   975
+  Functions: 368
+  Symbols:   977
Symbols:
+ _$s11Distributed0A23TargetInvocationDecoderPAAE15decodeErrorTypeypXpSgyKF
+ _$s11Distributed0A23TargetInvocationDecoderPAAE16decodeReturnTypeypXpSgyKF
Functions:
~ _$s11Distributed0A11ActorSystemPAAE07executeA6Target2on6target17invocationDecoder7handleryqd___AA010RemoteCallE0V010InvocationI0Qzz13ResultHandlerQztYaKAA0aB0Rd__lFTY0_ : 2904 -> 2640
~ _$s11Distributed0A11ActorSystemPAAE07executeA6Target2on6target17invocationDecoder7handleryqd___AA010RemoteCallE0V010InvocationI0Qzz13ResultHandlerQztYaKAA0aB0Rd__lFTQ1_ : 840 -> 824
~ _$s11Distributed0A11ActorSystemPAAE07executeA6Target2on6target17invocationDecoder7handleryqd___AA010RemoteCallE0V010InvocationI0Qzz13ResultHandlerQztYaKAA0aB0Rd__lFTQ2_ : 620 -> 616
~ _$s11Distributed0A11ActorSystemPAAE07executeA6Target2on6target17invocationDecoder7handleryqd___AA010RemoteCallE0V010InvocationI0Qzz13ResultHandlerQztYaKAA0aB0Rd__lFTQ4_ : 620 -> 616
~ _$s11Distributed0A11ActorSystemPAAE07executeA6Target2on6target17invocationDecoder7handleryqd___AA010RemoteCallE0V010InvocationI0Qzz13ResultHandlerQztYaKAA0aB0Rd__lFTY8_ : 448 -> 440
+ _$s11Distributed0A23TargetInvocationDecoderPAAE16decodeReturnTypeypXpSgyKF
```
