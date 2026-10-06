## remotepairingdeviced

> `/usr/libexec/remotepairingdeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x971b0` | `0x98184` | **`+0xfd4`** |
| `__DATA.__bss` | `0x1fd0` | `0x2260` | **`+0x290`** |
| `__TEXT.__const` | `0x3968` | `0x3b18` | **`+0x1b0`** |
| `__DATA.__data` | `0x4b68` | `0x4c78` | **`+0x110`** |
| `__DATA.__objc_const` | `0x5908` | `0x59d8` | **`+0xd0`** |
| `__TEXT.__constg_swiftt` | `0x20f8` | `0x2164` | **`+0x6c`** |
| `__TEXT.__swift5_typeref` | `0x264c` | `0x26a8` | **`+0x5c`** |
| `__TEXT.__eh_frame` | `0x2018` | `0x2070` | **`+0x58`** |
| `__DATA.__objc_data` | `0x3c0` | `0x410` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x14b8` | `0x1508` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1bf8` | `0x1c48` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0xa32` | `0xa72` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0xc8` | `0xf8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x5bf0` | `0x5c10` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1d93` | `0x1db3` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x138` | `0x14c` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x4380` | `0x4370` | **`-0x10`** |
| `__TEXT.__cstring` | `0x565c` | `0x566c` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x1c15` | `0x1c25` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x21d0` | `0x21c8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x138` | `0x140` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x114` | `0x11c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-280.0.8.0.0
+280.0.12.0.0

-  Functions: 3696
-  Symbols:   1718
-  CStrings:  1008
+  Functions: 3745
+  Symbols:   1717
+  CStrings:  1012
Symbols:
+ _$s19RemotePairingDevice24ControlChannelConnectionC7OptionsO0C0V15allowsPairSetup0h7PinlessB00H25IncomingTunnelConnections0H25UpgradeOfLockdownPairings0H20SharingSensitiveInfo0h4FreeB0AGSb_S5btcfC
- _$s19RemotePairingDevice22AuditActivityAssertionC25NotificationConfigurationV10symbolNameSSvg
- _$s19RemotePairingDevice24ControlChannelConnectionC7OptionsO0C0V15allowsPairSetup0h7PinlessB00H25IncomingTunnelConnections0H25UpgradeOfLockdownPairings0H20SharingSensitiveInfoAGSb_S4btcfC
CStrings:
+ "PAIRED_MACS/HOST/"
+ "_TtC20remotepairingdeviced20AuditMigrationMarker"
+ "_completedAt"
+ "_identifier"
+ "com.apple.Preferences"
+ "iconForApplicationIdentifier:"
+ "prefs:root=DEVELOPER_SETTINGS&path="
- "iconForSystemImageNamed:"
- "prefs:root=DEVELOPER_SETTINGS"
- "prefs:root=DEVELOPER_SETTINGS&path=PAIRED_MACS/host/"
```
