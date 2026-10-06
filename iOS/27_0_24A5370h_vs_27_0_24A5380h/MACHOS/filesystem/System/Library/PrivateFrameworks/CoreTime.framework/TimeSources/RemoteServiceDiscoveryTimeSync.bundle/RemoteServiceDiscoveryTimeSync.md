## RemoteServiceDiscoveryTimeSync

> `/System/Library/PrivateFrameworks/CoreTime.framework/TimeSources/RemoteServiceDiscoveryTimeSync.bundle/RemoteServiceDiscoveryTimeSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2de8` | `0x358c` | **`+0x7a4`** |
| `__TEXT.__objc_stubs` | `0x340` | `0x440` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x5f9` | `0x6b4` | **`+0xbb`** |
| `__TEXT.__oslogstring` | `0x3a7` | `0x434` | **`+0x8d`** |
| `__TEXT.__objc_methtype` | `0x29d` | `0x31e` | **`+0x81`** |
| `__DATA_CONST.__const` | `0x200` | `0x278` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x200` | `0x240` | **`+0x40`** |
| `__DATA.__objc_const` | `0x3b8` | `0x3e8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x130` | `0x158` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x6b0` | `0x6d0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2bc` | `0x2d4` | **`+0x18`** |
| `__TEXT.__cstring` | `0x258` | `0x26d` | **`+0x15`** |
| `__DATA_CONST.__auth_got` | `0x368` | `0x378` | **`+0x10`** |
| `__TEXT.__const` | `0xc8` | `0xd0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1c` | `0x20` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-245.0.1.502.2
+245.0.4.0.0

-  Functions: 97
-  Symbols:   157
-  CStrings:  171
+  Functions: 105
+  Symbols:   159
+  CStrings:  187
Symbols:
+ _objc_release_x24
+ _objc_release_x26
CStrings:
+ "%{public}@> expected t1 of %08X.%08X got %08X.%08X"
+ "%{public}@> time sync failed: invalid sntp response payload size"
+ "%{public}@> time sync skipped: synthesizer unavailable"
+ "/var/sntpd/state.bin"
+ "T^{?=b3b3b2CCc{?=SS}{?=SS}I{?=II}},V_header"
+ "^{?=b3b3b2CCc{?=SS}{?=SS}I{?=II}}"
+ "^{?=b3b3b2CCc{?=SS}{?=SS}I{?=II}}16@0:8"
+ "_header"
+ "applyExchange:utc:rtc:rtcUnc:"
+ "coarseMonotonicTime"
+ "header"
+ "machTime"
+ "propagatedTimeAtRTC:"
+ "propagatedUncertaintyAtRTC:"
+ "setHeader:"
+ "timeAtRtc:"
+ "timeProvider"
+ "v120@0:8{?=i{?=II}{?=II}{?=II}{?=II}{?=b3b3b2CCc{?=SS}{?=SS}I{?=II}}(?={in_addr=I}{in6_addr=(?=[16C][8S][4I])})i}16d96d104d112"
+ "v24@0:8^{?=b3b3b2CCc{?=SS}{?=SS}I{?=II}}16"
- "applyExchange:"
- "invalid sntp response payload"
- "v96@0:8{?=i{?=II}{?=II}{?=II}{?=II}{?=b3b3b2CCc{?=SS}{?=SS}I{?=II}}(?={in_addr=I}{in6_addr=(?=[16C][8S][4I])})i}16"
```
