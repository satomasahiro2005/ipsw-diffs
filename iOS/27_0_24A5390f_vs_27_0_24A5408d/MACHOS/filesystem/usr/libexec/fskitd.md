## fskitd

> `/usr/libexec/fskitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c6ec` | `0x4cef8` | **`+0x80c`** |
| `__TEXT.__objc_methname` | `0x67e5` | `0x68f2` | **`+0x10d`** |
| `__TEXT.__oslogstring` | `0x4555` | `0x4635` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x1f4c` | `0x1fdc` | **`+0x90`** |
| `__TEXT.__cstring` | `0x3900` | `0x3963` | **`+0x63`** |
| `__TEXT.__objc_stubs` | `0x52e0` | `0x5340` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x22b4` | `0x22f4` | **`+0x40`** |
| `__DATA.__objc_const` | `0x22f0` | `0x2320` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1160` | `0x1190` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x1918` | `0x1940` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x2688` | `0x26b0` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x27cf` | `0x27f1` | **`+0x22`** |
| `__DATA.__objc_ivar` | `0x180` | `0x184` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-974.0.11.0.0
+974.0.13.0.2

-  Functions: 1484
+  Functions: 1491

-  CStrings:  2096
+  CStrings:  2110
CStrings:
+ "%s: another mount is in flight or already mounted for bundleID (%@) resource (%@)"
+ "%s: another mountSingleVolume is in flight for bundleID (%@) resource (%@)"
+ "%s: resource (%@) already bound to instance (%@) for bundleID (%@)"
+ "-[fskitdExtensionManager addToInflightMountForBundle:user:resource:]"
+ "-[fskitdXPCServer mountSingleVolumeForResource:bundleID:mountPath:options:replyHandler:]_block_invoke_4"
+ "@36@0:8@16I24@28"
+ "B40@0:8@16@24@32"
+ "T@\"NSMutableSet\",&,V_inFlightSingleVolumeMounts"
+ "_inFlightSingleVolumeMounts"
+ "addToInflightMountForBundle:user:resource:"
+ "inFlightSingleVolumeMounts"
+ "removeFromInflightMountForBundle:user:resource:"
+ "setInFlightSingleVolumeMounts:"
+ "singleVolumeMountKeyForBundle:uid:resource:"
+ "v24@?0@\"NSURL\"8@\"NSError\"16"
- "-[fskitdXPCServer mountSingleVolumeForResource:bundleID:mountPath:options:replyHandler:]_block_invoke_3"
```
