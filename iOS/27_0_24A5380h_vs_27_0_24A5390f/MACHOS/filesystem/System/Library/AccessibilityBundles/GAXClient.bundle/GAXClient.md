## GAXClient

> `/System/Library/AccessibilityBundles/GAXClient.bundle/GAXClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9dfc` | `0xa1ec` | **`+0x3f0`** |
| `__TEXT.__oslogstring` | `0x961` | `0xb20` | **`+0x1bf`** |
| `__TEXT.__objc_stubs` | `0x1960` | `0x19e0` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x5f0` | `0x640` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x1c45` | `0x1c7f` | **`+0x3a`** |
| `__TEXT.__cstring` | `0x29cb` | `0x29ff` | **`+0x34`** |
| `__DATA_CONST.__auth_got` | `0x308` | `0x330` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x848` | `0x868` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xc98` | `0xcb8` | **`+0x20`** |
| `__DATA.__bss` | `0x61` | `0x71` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x200` | `0x210` | **`+0x10`** |
| `__TEXT.__const` | `0x78` | `0x80` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xa44` | `0xa4c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x390` | `0x398` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1059.0.0.0.0
+1061.0.0.0.0

-  Functions: 251
-  Symbols:   458
-  CStrings:  746
+  Functions: 253
+  Symbols:   465
+  CStrings:  756
Symbols:
+ _AXIsInternalInstall
+ _bootstrap_look_up2
+ _bootstrap_port
+ _mach_port_deallocate
+ _mach_task_self_
+ _notify_get_state
+ _notify_register_check
CStrings:
+ "GAX client became active but per-PID IPC registration is GONE (backboard cannot reach us). Service:%{public}@"
+ "GAX client became active. Per-PID IPC registration is alive. Service:%{public}@"
+ "GAX client became active; unexpected bootstrap_look_up2 result (kr=%{public}d). Service:%{public}@"
+ "Skipping ASAM re-adoption on client load: backboard reports no active session."
+ "Suppressing stale currentlyActiveSession: backboard reports no active session."
+ "UTF8String"
+ "_logIPCRegistrationState"
+ "com.apple.accessibility.guidedaccess.session.active"
+ "isRunning"
+ "serviceName"
```
