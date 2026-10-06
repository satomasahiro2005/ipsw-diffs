## peakpowermanagerd

> `/usr/libexec/peakpowermanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1081c` | `0x109f4` | **`+0x1d8`** |
| `__TEXT.__oslogstring` | `0xabf` | `0xb38` | **`+0x79`** |
| `__TEXT.__cstring` | `0x8cd` | `0x93e` | **`+0x71`** |
| `__TEXT.__objc_stubs` | `0x2280` | `0x22c0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x90` | `0xc4` | **`+0x34`** |
| `__DATA_CONST.__const` | `0xd8` | `0xf8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x730` | `0x750` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x2b40` | `0x2b5f` | **`+0x1f`** |
| `__DATA.__objc_selrefs` | `0xc20` | `0xc30` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x3a8` | `0x3b8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xa0` | `0xb0` | **`+0x10`** |
| `__DATA.__bss` | `0x29` | `0x31` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1191.0.27.0.0
+1191.0.37.0.0

-  Functions: 447
-  Symbols:   146
-  CStrings:  679
+  Functions: 450
+  Symbols:   150
+  CStrings:  686
Symbols:
+ _OBJC_CLASS_$_NSValue
+ _bootstrap_check_in
+ _bootstrap_port
+ _exit
+ _objc_opt_new
+ _os_transaction_create
- _IODataQueueAllocateNotificationPort
- _mach_port_mod_refs
CStrings:
+ "%s: draining telemetry queue backlog on launch\n"
+ "%s: failed to request telemetry donation on launch\n"
+ "Telemetry entry has missing or invalid category; skipping entry\n"
+ "com.apple.peakpowermanagerd.telemetry-drain"
+ "com.apple.peakpowermanagerd.telemetry-notification"
+ "main_block_invoke"
+ "peakpowermanagerd could not check in notification MachService (%s) status %d\n"
+ "peakpowermanagerd: CPMS telemetry bridge torn down; exiting for clean relaunch\n"
+ "pointerValue"
+ "valueWithPointer:"
- "peakpowermanagerd could not allocate mach notification port\n"
- "peakpowermanagerd failed to destroy mach port status code : %d\n"
- "peakpowermanagerd failed to send mach port deallocated notification to kext\n"
```
