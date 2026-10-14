## replayd

> `/usr/libexec/replayd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbae68` | `0xbaecc` | **`+0x64`** |
| `__TEXT.__objc_methname` | `0x15f73` | `0x15f9b` | **`+0x28`** |
| `__DATA.__objc_const` | `0x11398` | `0x113b8` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x167e9` | `0x16809` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x43f5` | `0x4410` | **`+0x1b`** |
| `__TEXT.__cstring` | `0x17d0c` | `0x17d26` | **`+0x1a`** |
| `__DATA.__objc_ivar` | `0xd84` | `0xd88` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-765.14.1.0.0
+765.15.2.0.0

-  CStrings:  7389
+  CStrings:  7391
Functions:
~ sub_100003674 : 384 -> 408
~ sub_1000037f4 -> sub_10000380c : 352 -> 376
~ sub_1000053c0 -> sub_1000053f0 : 248 -> 252
~ sub_1000054b8 -> sub_1000054ec : 260 -> 264
~ sub_10000a970 -> sub_10000a9a8 : 156 -> 160
~ sub_10000ade8 -> sub_10000ae24 : 640 -> 668
~ sub_10000b710 -> sub_10000b768 : 140 -> 152
CStrings:
+ " [INFO] %{public}s:%d %p hasStarted=%d micDeviceUID=%@ micCaptureSessionCount=%ld"
+ " [INFO] %{public}s:%d didStart=%d pid=%d attributionSource=%ld micDeviceUID=%@"
+ "-[SCMediaAttributionManager updateMicrophoneCaptureDidStart:withAuditToken:micDeviceUID:]"
+ "-[SCMediaAttributionManager updateMicrophoneCaptureDidStart:withPID:attributionSource:micDeviceUID:]"
+ "_micDeviceUID"
+ "updateMicrophoneCaptureDidStart:withAuditToken:micDeviceUID:"
+ "updateMicrophoneCaptureDidStart:withPID:attributionSource:micDeviceUID:"
+ "v40@0:8B16i20q24@32"
+ "v60@0:8B16{?=[8I]}20@52"
- " [INFO] %{public}s:%d %p hasStarted=%d micCaptureSessionCount=%ld"
- " [INFO] %{public}s:%d didStart=%d pid=%d attributionSource=%ld"
- "-[SCMediaAttributionManager updateMicrophoneCaptureDidStart:withAuditToken:]"
- "-[SCMediaAttributionManager updateMicrophoneCaptureDidStart:withPID:attributionSource:]"
- "updateMicrophoneCaptureDidStart:withAuditToken:"
- "updateMicrophoneCaptureDidStart:withPID:attributionSource:"
- "v32@0:8B16i20q24"
```
