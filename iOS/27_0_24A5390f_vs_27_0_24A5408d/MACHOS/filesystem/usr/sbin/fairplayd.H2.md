## fairplayd.H2

> `/usr/sbin/fairplayd.H2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd1a418` | `0xd0ec5c` | **`-0xb7bc`** |
| `__DATA_CONST.__const` | `0x712b0` | `0x70030` | **`-0x1280`** |
| `__TEXT.__const` | `0x395180` | `0x395250` | **`+0xd0`** |
| `__DATA.__data` | `0x10880` | `0x10930` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x8d0` | `0x948` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x1cc` | `0x1e4` | **`+0x18`** |
| `__DATA.__common` | `0x5808` | `0x57f8` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x220` | `0x210` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x118` | `0x110` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 935
-  Symbols:   165
-  CStrings:  26
+  Functions: 944
+  Symbols:   176
+  CStrings:  27
Symbols:
+ __dispatch_source_type_mach_recv
+ __dispatch_source_type_read
+ __exit
+ _dispatch_activate
+ _dispatch_after
+ _dispatch_get_global_queue
+ _dispatch_main
+ _dispatch_queue_attr_make_initially_inactive
+ _dispatch_queue_attr_make_with_qos_class
+ _dispatch_release
+ _dispatch_resume
+ _dispatch_source_cancel
+ _dispatch_source_create
+ _dispatch_source_get_handle
+ _dispatch_source_set_cancel_handler
+ _dispatch_source_set_event_handler
+ _dispatch_time
+ _mach_port_destroy
- _CFFileDescriptorCreateRunLoopSource
- _CFMachPortCreateRunLoopSource
- _CFMachPortCreateWithPort
- _CFRunLoopAddSource
- _CFRunLoopRun
- __dispatch_main_q
- _kCFRunLoopDefaultMode
CStrings:
+ "HR29gxIvrE%dE0011r%dJtL"
```
