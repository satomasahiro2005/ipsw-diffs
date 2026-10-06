## CoreHandwriting

> `/System/Library/PrivateFrameworks/CoreHandwriting.framework/CoreHandwriting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3504c4` | `0x350d08` | **`+0x844`** |
| `__TEXT.__oslogstring` | `0x170b1` | `0x1735a` | **`+0x2a9`** |
| `__TEXT.__gcc_except_tab` | `0x516fc` | `0x51740` | **`+0x44`** |
| `__DATA_CONST.__const` | `0x53d8` | `0x5400` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xf100` | `0xf120` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xbb90` | `0xbbb0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x8935` | `0x8941` | **`+0xc`** |

### Other Changes

```diff

-587.1.0.0.0
+587.2.0.0.0

-  Functions: 7473
+  Functions: 7477

-  CStrings:  3599
+  CStrings:  3608
CStrings:
+ "Adjacency data contains more maps than stroke count (%ld) when deserializing."
+ "Adjacency map count (%zu) does not match stroke count (%ld) when deserializing."
+ "Adjacency map size %zu exceeds remaining bytes when deserializing."
+ "ContextLookup Query suppressing %ld orphan non-text strokes below caption ink floor (total arc length %.1f)"
+ "Latin-ASCII"
+ "Missing adjacency data when deserializing sparse adjacency matrix."
+ "Negative stroke count (%ld) or stroke class count (%ld) when deserializing stroke classification matrix."
+ "Stroke count (%ld) or stroke class count (%ld) exceeds supported maximum (%ld) when deserializing stroke classification matrix."
+ "Truncated adjacency data when reading map size."
```
