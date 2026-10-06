## configd

> `/usr/libexec/configd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68ab0` | `0x68fac` | **`+0x4fc`** |
| `__TEXT.__oslogstring` | `0x564d` | `0x56dd` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0x25c0` | `0x2580` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0xa28` | `0xa50` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x19d0` | `0x19f0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3026` | `0x3044` | **`+0x1e`** |
| `__TEXT.__auth_stubs` | `0x24e0` | `0x24d0` | **`-0x10`** |
| `__DATA.__common` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1280` | `0x1278` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1441.0.0.0.0
+1444.0.0.0.0

-  Functions: 955
-  Symbols:   819
-  CStrings:  1668
+  Functions: 962
+  Symbols:   818
+  CStrings:  1673
Symbols:
- _CFArrayGetValues
CStrings:
+ "  %d : port = 0x%x (%u)"
+ "%s: all done waiting"
+ "%s: delaying shutdown by %d seconds"
+ "/var/tmp/configd-watcher.plist"
+ "configd: bundle shutdown complete"
+ "configd: calling stop() on %@"
+ "configd: handling SIGTERM"
+ "configd: no plugins need stop, exiting"
+ "configd: stopping plugins"
+ "no plugins delayed stop"
+ "stop_IPMonitor"
- "  %d : port = 0x%x"
- "calling bundle stop() functions"
- "server shutdown complete (%f)"
- "starting server shutdown (%f)"
- "watcherRefs"
- "watchers"
```
