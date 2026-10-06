## libnwswifttls.dylib

> `/usr/lib/libnwswifttls.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf98e0` | `0xf9c44` | **`+0x364`** |
| `__TEXT.__oslogstring` | `0x52bb` | `0x534b` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x3fe8` | `0x4018` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x1fe0` | `0x1fd8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x28d8` | `0x28e0` | **`+0x8`** |

### Other Changes

```diff

-171.40.7.0.0
+171.40.10.0.0

-  Functions: 3687
-  Symbols:   8329
-  CStrings:  527
+  Functions: 3688
+  Symbols:   8330
+  CStrings:  529
Symbols:
+ _$s15SwiftTLSLibrary16TLSRecordHandlerV17protectForTesting9plaintext17actualContentTypeAA13TLSCiphertextVSays5UInt8VG_AA0jK0VtAA8TLSErrorOYKF
Functions:
+ _$s15SwiftTLSLibrary16TLSRecordHandlerV17protectForTesting9plaintext17actualContentTypeAA13TLSCiphertextVSays5UInt8VG_AA0jK0VtAA8TLSErrorOYKF
~ _$s15SwiftTLSLibrary16TLSRecordHandlerV9readAlert33_3A7BCC859838BE1761A4636F58F247A0LLyys7RawSpanVAA8TLSErrorOYKF : 1004 -> 1752
CStrings:
+ "alert record contained trailing bytes after a complete alert message"
+ "alert record did not contain a complete alert message"
```
