## chassisplatformhostd

> `/usr/libexec/chassisplatformhostd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84fcb8` | `0x84e3bc` | **`-0x18fc`** |
| `__TEXT.__eh_frame` | `0x67a90` | `0x67cd0` | **`+0x240`** |
| `__TEXT.__oslogstring` | `0x10b2e` | `0x10d6e` | **`+0x240`** |
| `__TEXT.__unwind_info` | `0x24dc8` | `0x24e68` | **`+0xa0`** |
| `__DATA.__data` | `0x24a88` | `0x24a08` | **`-0x80`** |
| `__DATA_CONST.__const` | `0x40b08` | `0x40a88` | **`-0x80`** |
| `__TEXT.__swift5_reflstr` | `0x13412` | `0x133a2` | **`-0x70`** |
| `__TEXT.__const` | `0x49ce2` | `0x49d42` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x13f4c` | `0x13eec` | **`-0x60`** |
| `__TEXT.__cstring` | `0x12473` | `0x12433` | **`-0x40`** |
| `__TEXT.__swift5_capture` | `0xf5ac` | `0xf56c` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0x15da8` | `0x15de8` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x6ba4` | `0x6be4` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x3694` | `0x36b0` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0xc570` | `0xc588` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x27c0` | `0x27d8` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x14554` | `0x14540` | **`-0x14`** |
| `__TEXT.__auth_stubs` | `0x73d0` | `0x73c0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x39f8` | `0x39f0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-60.0.0.0.0
+61.0.0.0.0

-  Functions: 36057
-  Symbols:   3719
-  CStrings:  3886
+  Functions: 36083
+  Symbols:   3718
+  CStrings:  3894
Symbols:
- _$s18ChassisPlatformKit7CPKUDIDV9deriveULA8bmcIndex4nodeSSs5UInt8V_ACtFZ
CStrings:
+ "%s SoC is already in DFU, expecting %s to disconnect."
+ "%s cleanup finished"
+ "%s disconnected, cleaning up"
+ "%s downstreamMonitorTask did not exit within %llus, orphaning"
+ "%s ignoring pre-DFU-request restorable device %s, disconnect is expected."
+ "%s pre-DFU-request restorable device %s disappeared."
+ "%s prior downstreamMonitorTask did not exit within %llus, orphaning"
+ "%s setupTask for node %s did not exit within %llus, orphaning"
+ "BMC %s node %s: setupTask did not exit within %llus, orphaning"
+ "Deleting stale proxy RSD route: %s"
+ "No proxy RSD routes found or failed to query routing table: %@"
+ "ProxyRSD monitorBMCConnection finished, should not happen"
+ "^fd[0-9a-f][0-9a-f]:%04x[:/]"
+ "netstat -rn -f inet6 | grep '"
- "BMC %s: disconnected, cleaning up"
- "Deleting stale ULA route: %s"
- "No ULA routes found or failed to query routing table: %@"
- "Timed out determining SoC state."
- "determiningSoCState"
- "netstat -rn -f inet6 | grep '^fd'"
```
