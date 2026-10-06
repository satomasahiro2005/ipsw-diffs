## WiFiPeerToPeer

> `/System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/WiFiPeerToPeer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ff34` | `0x401dc` | **`+0x2a8`** |
| `__TEXT.__oslogstring` | `0x1bf5` | `0x1c68` | **`+0x73`** |
| `__TEXT.__cstring` | `0x9969` | `0x99c8` | **`+0x5f`** |
| `__AUTH_CONST.__objc_const` | `0x9ef8` | `0x9f18` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x565c` | `0x567c` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x560` | `0x570` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x22c8` | `0x22d8` | **`+0x10`** |
| `__TEXT.__const` | `0x270` | `0x280` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xfa8` | `0xfb0` | **`+0x8`** |

### Other Changes

```diff

-885.77.0.0.0
+885.85.0.0.0

-  Functions: 1754
-  Symbols:   3463
-  CStrings:  1194
+  Functions: 1757
+  Symbols:   3468
+  CStrings:  1198
Symbols:
+ -[WiFiAwareDataSession initiatorDataAddress]
+ -[WiFiAwareDataSession setDatapathID:]
+ -[WiFiAwareDataSession setInitiatorDataAddress:]
+ GCC_except_table43
+ _dispatch_queue_get_label
+ _objc_setProperty_atomic
- GCC_except_table44
CStrings:
+ "-[WiFiP2PXPCConnection invalidate]"
+ "-[WiFiP2PXPCConnection start]"
+ "-[WiFiP2PXPCConnection stop]"
+ "[WiFiP2PXPCConnection %p] %{public}s endpointType=%ld connection=%p callingQueue=%{public}s targetQueue=%{public}s"
+ "\xd1Q"
- "\xf1Q"
```
