## NDOAPI

> `/System/Library/PrivateFrameworks/NDOAPI.framework/NDOAPI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdfc70` | `0xe186c` | **`+0x1bfc`** |
| `__TEXT.__oslogstring` | `0x1260` | `0x13a0` | **`+0x140`** |
| `__AUTH_CONST.__auth_got` | `0xa68` | `0xb20` | **`+0xb8`** |
| `__AUTH_CONST.__const` | `0x31d8` | `0x3268` | **`+0x90`** |
| `__TEXT.__cstring` | `0x1c04` | `0x1c84` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x60a8` | `0x6118` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x45e0` | `0x4618` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x390` | `0x3b0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x2550` | `0x256c` | **`+0x1c`** |
| `__DATA.__data` | `0x1cd8` | `0x1ce8` | **`+0x10`** |
| `__TEXT.__const` | `0xdae8` | `0xdaf8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2958` | `0x2968` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x2130` | `0x2136` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x288` | `0x28c` | **`+0x4`** |

### Other Changes

```diff

-624.40.14.0.0
+624.40.15.0.0

+  - /usr/lib/swift/libswiftSystem.dylib

-  Functions: 6725
-  Symbols:   1286
-  CStrings:  274
+  Functions: 6738
+  Symbols:   1287
+  CStrings:  284
Symbols:
+ _symbolic _____ 6NDOAPI15NDOSerialNumberO
CStrings:
+ "%s: %{public}s url host is not an Apple host"
+ "%s: %{public}s url scheme is not http(s)"
+ "%s: Malformed/invalid serial number"
+ "%s: missing or unparsable %{public}s url"
+ "%s: path resolved outside the coverage cache directory"
+ "%s: using plaintext http for %{public}s url, host %{public}s"
+ "Rejected non-Apple host for "
+ "Rejected non-http(s) "
+ "deviceCoverageCachePath(for:)"
+ "validatedApiUrl(_:context:)"
```
