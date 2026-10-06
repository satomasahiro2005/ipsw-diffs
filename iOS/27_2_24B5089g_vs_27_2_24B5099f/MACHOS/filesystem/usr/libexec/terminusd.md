## terminusd

> `/usr/libexec/terminusd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2017fc` | `0x201da4` | **`+0x5a8`** |
| `__TEXT.__cstring` | `0x52a9a` | `0x52bd6` | **`+0x13c`** |
| `__TEXT.__gcc_except_tab` | `0x62c8` | `0x63b4` | **`+0xec`** |
| `__DATA_CONST.__const` | `0x4f18` | `0x4f40` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0xe90` | `0xeb8` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x3ef0` | `0x3f10` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1f88` | `0x1f98` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3178` | `0x3188` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xf00` | `0xf08` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-914.40.23.0.0
+914.40.26.502.1

-  Functions: 3909
-  Symbols:   1547
-  CStrings:  11630
+  Functions: 3910
+  Symbols:   1550
+  CStrings:  11634
Symbols:
+ _RPOptionStatusFlags
+ _nw_advertise_descriptor_get_advertise_scope
+ _nw_endpoint_get_application_service_alias
CStrings:
+ "%s%.30s:%-4d Not starting NAN: room distributor is unused (wired link or 6GHz infrastructure Wi-Fi)"
+ "%s%.30s:%-4d advertise scope unset for %@, defaulting to personal|family"
+ "%s%.30s:%-4d no advertise descriptor for %@, ignoring resolve request"
+ "%s%.30s:%-4d not returning endpoint for %@ (%@), no common scope %u/%u"
+ "%s%.30s:%-4d returning endpoint for %@ (%@), common scope %u/%u"
+ "%s%.30s:%-4d returning endpoint for %@, advertise scope all"
+ "%s%.30s:%-4d room distributor unused (wired link or 6GHz infrastructure Wi-Fi), not establishing a distribution relationship towards the room distributor"
+ "-[NRApplicationServiceManager copyListenerEndpointForASName:asClient:]"
+ "19:31:07"
+ "914.40.26.502.1"
+ "Oct  2 2026"
- "%s%.30s:%-4d Not starting NAN: room distributor is unused (wired link or 2.4GHz/6GHz infrastructure Wi-Fi)"
- "%s%.30s:%-4d room distributor unused (wired link or 2.4GHz/6GHz infrastructure Wi-Fi), not establishing a distribution relationship towards the room distributor"
- "-[NRApplicationServiceManager copyListenerEndpointForASName:]"
- "20:18:05"
- "914.40.23"
- "Sep 13 2026"
- "disableWiFiAwareOn2GHz"
```
