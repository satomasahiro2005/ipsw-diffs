## diagnosticscheckupd

> `/usr/libexec/diagnosticscheckupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x492bc` | `0x4b264` | **`+0x1fa8`** |
| `__TEXT.__oslogstring` | `0x353a` | `0x374a` | **`+0x210`** |
| `__TEXT.__const` | `0x1ea8` | `0x2088` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0x2ed8` | `0x3018` | **`+0x140`** |
| `__DATA.__bss` | `0x1b10` | `0x1c10` | **`+0x100`** |
| `__TEXT.__constg_swiftt` | `0x1534` | `0x15f0` | **`+0xbc`** |
| `__TEXT.__swift5_reflstr` | `0x146d` | `0x1516` | **`+0xa9`** |
| `__DATA.__data` | `0x27d0` | `0x2850` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0xdf0` | `0xe54` | **`+0x64`** |
| `__DATA.__objc_const` | `0xe290` | `0xe2f0` | **`+0x60`** |
| `__DATA.__objc_data` | `0x1b78` | `0x1bb8` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x8251` | `0x8291` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x5b40` | `0x5b80` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1340` | `0x1370` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x53c` | `0x564` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0xbf3` | `0xc0e` | **`+0x1b`** |
| `__TEXT.__swift5_assocty` | `0xd8` | `0xf0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0x8c` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x15d0` | `0x15e0` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0xbe2` | `0xbef` | **`+0xd`** |
| `__DATA.__common` | `0xe0` | `0xe8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xaf8` | `0xb00` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x320` | `0x328` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xe8` | `0xf0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xb0` | `0xb8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x2ec9` | `0x2ecd` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_ivar`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1374.0.27.0.0
+1374.2.1.0.0

-  Functions: 1833
-  Symbols:   638
-  CStrings:  2378
+  Functions: 1862
+  Symbols:   639
+  CStrings:  2389
Symbols:
+ _swift_retain_x1
CStrings:
+ "Device %s is not present is selectable allowlist, skipping"
+ "Device remained archived through confirmation delay - ending session"
+ "Device resumed (phase: %s) - cancelling pending session end"
+ "DeviceSessionManager: fatal session error, sessionDisplayState -> .error"
+ "DeviceSessionManager: session archived, sessionDisplayState -> .complete"
+ "DeviceSessionManager: suite cleared while .testing forcing idle"
+ "Ignoring self-service session vended after a technician flow; continuing to poll"
+ "Informing %ld client(s) of exit reason %ld"
+ "Selecting first device in required SN list: %s"
+ "endDiagnostics() called, pendingWork != nil: %{bool}d"
+ "filters"
+ "hasEnteredTechnicianFlow"
+ "hasReportedExitReason"
- "Device remained archived after confirmation delay - ending session"
- "Device transitioned away from archived - spurious archive, continuing session"
```
