## DataCollector

> `/System/Library/PrivateFrameworks/DataCollector.framework/DataCollector`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31414` | `0x31abc` | **`+0x6a8`** |
| `__AUTH_CONST.__const` | `0x2429` | `0x25b1` | **`+0x188`** |
| `__DATA.__data` | `0xa18` | `0xaa8` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0xfea` | `0x106a` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x3a4` | `0x414` | **`+0x70`** |
| `__TEXT.__const` | `0x2e70` | `0x2ec0` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x1414` | `0x1464` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x10f0` | `0x1140` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x113d` | `0x118b` | **`+0x4e`** |
| `__DATA_DIRTY.__data` | `0xd28` | `0xd18` | **`-0x10`** |
| `__TEXT.__cstring` | `0x2cd` | `0x2dd` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x26f0` | `0x2700` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x70` | `0x74` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x10c` | `0x110` | **`+0x4`** |

### Other Changes

```diff

-3600.21.1.0.0
+3605.5.1.0.0

-  Functions: 1709
-  Symbols:   789
+  Functions: 1730
+  Symbols:   796
Symbols:
+ ___swift_closure_destructor.16Tm
+ _objc_release_x27
+ _objc_retain_x27
+ _symbolic $s13DataCollector21ServiceConfigProviderP
+ _symbolic ScCyx______pG s5ErrorP
+ _symbolic _____ 13DataCollector16SafeContinuation33_16650F5CFDF5CF5E5DEC6532C9C5B8B5LLC5StateO
+ _symbolic ______p 13DataCollector21ServiceConfigProviderP
+ _symbolic ______pSg 13DataCollector21ServiceConfigProviderP
+ _symbolic _____y______G 13DataCollector16SafeContinuation33_16650F5CFDF5CF5E5DEC6532C9C5B8B5LLC5StateO 10Foundation0A0V
+ _symbolic _____y_____y______GG 15Synchronization5MutexVAARi_zrlE 13DataCollector16SafeContinuation33_16650F5CFDF5CF5E5DEC6532C9C5B8B5LLC5StateO 10Foundation0C0V
+ _symbolic _____y_____yx_GG 15Synchronization5MutexVAARi_zrlE 13DataCollector16SafeContinuation33_16650F5CFDF5CF5E5DEC6532C9C5B8B5LLC5StateO
+ _symbolic _____yx______pG s6ResultOsRi_zRi0_zrlE s5ErrorP
- ___swift_closure_destructor.15Tm
- _objc_retain_x26
- _symbolic ScCy___________pGSg 10Foundation4DataV s5ErrorP
- _symbolic _____yScCy___________pGSgG 15Synchronization5MutexVAARi_zrlE 10Foundation4DataV s5ErrorP
- _symbolic _____yScCyx______pGSgG 15Synchronization5MutexVAARi_zrlE s5ErrorP
CStrings:
+ "call(ospreyChannel:safeContinuation:methodName:messageData:compressionEnabled:disableDeviceAuthentication:logger:)"
- "call(ospreyChannel:methodName:messageData:headers:compressionEnabled:disableDeviceAuthentication:logger:)"
```
