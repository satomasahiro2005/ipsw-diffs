## trustd

> `/usr/libexec/trustd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59e4c` | `0x5a36c` | **`+0x520`** |
| `__TEXT.__oslogstring` | `0x590c` | `0x5b59` | **`+0x24d`** |
| `__DATA_CONST.__cfstring` | `0x5a60` | `0x5a40` | **`-0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0xe0` | `0x100` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5d59` | `0x5d3f` | **`-0x1a`** |
| `__DATA_CONST.__objc_arrayobj` | `0x48` | `0x60` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x108` | `0x120` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x920` | `0x930` | **`+0x10`** |
| `__DATA.__data` | `0x450` | `0x458` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1030` | `0x1028` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-62460.0.22.0.0
+62460.0.38.0.1

-  CStrings:  2163
+  CStrings:  2169
Functions:
~ sub_10000b600 : 580 -> 572
~ sub_10001a554 -> sub_10001a54c : 132 -> 164
~ sub_10001d904 -> sub_10001d91c : 268 -> 300
~ sub_10001e568 -> sub_10001e5a0 : 1424 -> 1680
~ sub_100023c8c -> sub_100023dc4 : 196 -> 324
~ sub_1000392e0 -> sub_100039498 : 116 -> 152
~ sub_100041958 -> sub_100041b34 : 196 -> 612
~ sub_100041a1c -> sub_100041d98 : 52 -> 196
~ sub_100041a50 -> sub_100041e5c : 372 -> 52
~ sub_100041bc4 -> sub_100041e90 : 72 -> 356
~ sub_100041c0c -> sub_100041ff4 : 84 -> 72
~ sub_100041c60 -> sub_10004203c : 584 -> 84
~ sub_100043338 -> sub_100043520 : 572 -> 1308
~ sub_1000436bc -> sub_100043b84 : 6084 -> 6148
~ sub_100046900 -> sub_100046e08 : 1780 -> 1804
CStrings:
+ "CT log has non-date \"expiry\" field; not counting (log=%@)"
+ "CT log has non-date \"frozen\" field; treating as invalid (log=%@)"
+ "CT log has non-date shard window field; treating as invalid (log=%@)"
+ "MobileAssetCompatibilityVersion"
+ "OTATrust: failed to read key from trusted CT log array entry at index %lu"
+ "OTATrust: failed to reset OTAPKIContext after compat change: %@"
+ "OTATrust: trusted CT log entry at index %lu has non-data \"key\" (class=%@); skipping"
+ "OTATrust: trusted CT log entry at index %lu has non-data \"log_id\" (class=%@); skipping"
+ "OTATrust: trusted CT log entry at index %lu has non-date \"%@\" (class=%@); skipping"
+ "com.apple.ValidUpdater.update"
+ "compatibility version changed (disk %@ -> binary %lu); resetting check-in"
+ "no log_id in trusted CT log array entry at index %lu; computing from key"
+ "v16@?0^{__SecRevocationDb=^{__OpaqueSecDb}BBB^{__CFArray}^{__CFDictionary}{os_unfair_lock_s=I}}8"
+ "validupdate: Failed to create db at \"%@\""
- "%s path"
- "%s path as UTF8 string"
- "com.apple.trustd.valid.db-changed"
- "could not get valid snapshot"
- "failed to read key from trusted CT log array entry at index %lu"
- "failed to read log_id from trusted CT log array entry at index %lu, computing log_id"
- "sqlite3"
- "v16@?0^{__SecRevocationDb=^{__OpaqueSecDb}^{dispatch_queue_s}BBB^{__CFArray}^{__CFDictionary}{os_unfair_lock_s=I}}8"
```
