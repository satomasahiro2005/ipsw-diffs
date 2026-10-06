## heartratecoordinatord

> `/usr/libexec/heartratecoordinatord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x51ab` | `0x5119` | **`-0x92`** |
| `__TEXT.__oslogstring` | `0x3a6f` | `0x3ae8` | **`+0x79`** |
| `__DATA_CONST.__cfstring` | `0x2080` | `0x2020` | **`-0x60`** |
| `__DATA.__objc_const` | `0x2c48` | `0x2c18` | **`-0x30`** |
| `__TEXT.__gcc_except_tab` | `0x4374` | `0x439c` | **`+0x28`** |
| `__TEXT.__cstring` | `0x21b2` | `0x2191` | **`-0x21`** |
| `__TEXT.__objc_stubs` | `0x4000` | `0x3fe0` | **`-0x20`** |
| `__TEXT.__text` | `0x26e50` | `0x26e6c` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x1a0c` | `0x19f4` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x228` | `0x238` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1248` | `0x1238` | **`-0x10`** |
| `__TEXT.__const` | `0x369` | `0x375` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x11f8` | `0x11f0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x28c` | `0x288` | **`-0x4`** |
| `__TEXT.__objc_methtype` | `0x1c3e` | `0x1c3b` | **`-0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_classname`

### Other Changes

```diff

-40.0.0.0.0
+41.1.0.0.0

-  Functions: 922
+  Functions: 919

-  CStrings:  1603
+  CStrings:  1600
CStrings:
+ "@48@0:8@16@24@32@40"
+ "firstObject"
+ "hr_count"
+ "initWithDelegate:remoteObjectProxy:onQueue:recentHighConfidenceHRBuffer:"
+ "most recent high confidence HR requested by %{public}@, returning bpm: %{sensitive}f timestamp: %{sensitive}@"
+ "most recent high confidence HR requested by %{public}@, returning nil"
+ "recent high confidence HRs requested by %{public}@, returning %lu samples, oldest: %.0fs, latest: %.0fs"
- "@56@0:8@16@24@32@40@48"
- "HR with bpm: %{sensitive}f"
- "T@\"HRCHeartRateData\",&,V_mostRecentHighConfidenceHeartRate"
- "initWithDelegate:remoteObjectProxy:onQueue:mostRecentHighConfidenceHR:recentHighConfidenceHRBuffer:"
- "most recent high confidence HR requested by %{public}@, returning %@"
- "mostRecentHighConfidenceHeartRate"
- "nil"
- "none"
- "recent high confidence HRs requested by %{public}@, returning %lu samples, latest: %{public}@"
- "setMostRecentHighConfidenceHeartRate:"
```
