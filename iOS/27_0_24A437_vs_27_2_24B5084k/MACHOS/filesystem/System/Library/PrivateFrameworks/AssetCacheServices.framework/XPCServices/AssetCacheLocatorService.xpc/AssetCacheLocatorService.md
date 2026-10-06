## AssetCacheLocatorService

> `/System/Library/PrivateFrameworks/AssetCacheServices.framework/XPCServices/AssetCacheLocatorService.xpc/AssetCacheLocatorService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fea4` | `0x20190` | **`+0x2ec`** |
| `__TEXT.__oslogstring` | `0x297f` | `0x2a64` | **`+0xe5`** |
| `__TEXT.__objc_methname` | `0x39c1` | `0x3a34` | **`+0x73`** |
| `__TEXT.__cstring` | `0x230f` | `0x2381` | **`+0x72`** |
| `__TEXT.__objc_stubs` | `0x3140` | `0x31a0` | **`+0x60`** |
| `__DATA.__objc_const` | `0x19e8` | `0x1a18` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x1f80` | `0x1fa0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xde0` | `0xdf8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xfc4` | `0xfdc` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4d0` | `0x4c8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x124` | `0x128` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-157.0.0.0.0
+157.40.2.0.0

-  Functions: 496
+  Functions: 498

-  CStrings:  1270
+  CStrings:  1286
CStrings:
+ " [LONG-TTL negative]"
+ "#%08x [%s] %@ hit: %@ (from cache, %.0fs validity remaining)"
+ "#%08x [%s] locate outcome: http=%lu reason=%{public}s servers=%ld->%ld validity=%.0f%s retryAfter=%{public}s"
+ "#%08x [%s] locate outcome: transport-error=%ld (%{public}@) — no HTTP response"
+ "Retry-After"
+ "T@\"NSString\",C,V_locateRetryAfter"
+ "_locateRetryAfter"
+ "empty-200"
+ "http-503"
+ "http-error"
+ "locateRetryAfter"
+ "parse-error"
+ "parsed"
+ "server-cert-untrusted"
+ "setLocateRetryAfter:"
+ "valueForHTTPHeaderField:"
+ "zero-byte"
- "#%08x [%s] %@ hit: %@"
```
