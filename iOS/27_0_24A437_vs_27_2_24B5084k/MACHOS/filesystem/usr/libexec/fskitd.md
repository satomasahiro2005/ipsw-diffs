## fskitd

> `/usr/libexec/fskitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4cef8` | `0x4d3b0` | **`+0x4b8`** |
| `__TEXT.__objc_methname` | `0x68f2` | `0x6a18` | **`+0x126`** |
| `__DATA.__objc_const` | `0x2320` | `0x23a0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x3963` | `0x39e2` | **`+0x7f`** |
| `__DATA.__data` | `0x718` | `0x778` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x1fdc` | `0x2034` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x4635` | `0x4680` | **`+0x4b`** |
| `__TEXT.__objc_methlist` | `0x22f4` | `0x233c` | **`+0x48`** |
| `__DATA_CONST.__cfstring` | `0x900` | `0x940` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x5340` | `0x5380` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x1940` | `0x1978` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0x1fa` | `0x20a` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1190` | `0x11a0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x27f1` | `0x27ff` | **`+0xe`** |
| `__DATA.__objc_ivar` | `0x184` | `0x18c` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__const` | `0x138` | `0x130` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-974.0.13.0.2
+974.40.11.0.0

-  Functions: 1491
+  Functions: 1496

-  CStrings:  2110
+  CStrings:  2127
CStrings:
+ "%s: dropping orphaned task %@ on connection invalidation"
+ "-[fskitdXPCServer handleInvalidated]"
+ "@24@0:8B16B20"
+ "FSClientFSCKXPC"
+ "FSClientFSCKXPCProtocols"
+ "Incomming connection, entitled %d, fsck-entitled %d"
+ "T@\"NSMutableSet\",&,V_fsckTaskUUIDs"
+ "TB,V_clientHasFSCKEntitlement"
+ "TB,V_clientHasLiveFSEntitlement"
+ "_clientHasFSCKEntitlement"
+ "_clientHasLiveFSEntitlement"
+ "_fsckTaskUUIDs"
+ "clientHasFSCKEntitlement"
+ "clientHasLiveFSEntitlement"
+ "com.apple.private.security.disk-device-access"
+ "com.apple.rootless.restricted-block-devices"
+ "fsckTaskUUIDs"
+ "initForEntitledClient:fsckEntitled:"
+ "removeAllObjects"
+ "setClientHasFSCKEntitlement:"
+ "setClientHasLiveFSEntitlement:"
+ "setFsckTaskUUIDs:"
- "Incomming connection, entitled %d"
- "TB,V_clientHasEntitlement"
- "_clientHasEntitlement"
- "clientHasEntitlement"
- "setClientHasEntitlement:"
```
