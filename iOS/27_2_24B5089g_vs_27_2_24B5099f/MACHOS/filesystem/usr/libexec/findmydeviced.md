## findmydeviced

> `/usr/libexec/findmydeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f59b8` | `0x4f8934` | **`+0x2f7c`** |
| `__TEXT.__eh_frame` | `0x2741c` | `0x27748` | **`+0x32c`** |
| `__TEXT.__oslogstring` | `0x1d669` | `0x1d859` | **`+0x1f0`** |
| `__TEXT.__unwind_info` | `0xfeb8` | `0xff60` | **`+0xa8`** |
| `__TEXT.__const` | `0x469e6` | `0x46a76` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x20559` | `0x205e5` | **`+0x8c`** |
| `__DATA.__bss` | `0x28fa0` | `0x29020` | **`+0x80`** |
| `__DATA.__objc_const` | `0x1ece8` | `0x1ed48` | **`+0x60`** |
| `__TEXT.__cstring` | `0xdfde` | `0xe02e` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x57be` | `0x57fe` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x5c94` | `0x5ccc` | **`+0x38`** |
| `__DATA.__data` | `0xb2f0` | `0xb320` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x20f0` | `0x211c` | **`+0x2c`** |
| `__TEXT.__swift5_typeref` | `0x4df4` | `0x4e1e` | **`+0x2a`** |
| `__TEXT.__swift_as_ret` | `0x1478` | `0x14a0` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x6ef4` | `0x6f18` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x1ba8` | `0x1b90` | **`-0x18`** |
| `__TEXT.__swift_as_entry` | `0xd80` | `0xd98` | **`+0x18`** |
| `__DATA.__common` | `0x9f0` | `0xa00` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1dd50` | `0x1dd60` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x4e70` | `0x4e60` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x2748` | `0x2740` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x1414` | `0x1418` | **`+0x4`** |

### Same-size Content Changes

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
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-482.31.6.16.11
+482.31.6.16.16

-  Functions: 16509
-  Symbols:   2719
-  CStrings:  10372
+  Functions: 16540
+  Symbols:   2717
+  CStrings:  10383
Symbols:
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s11Distributed0A23TargetInvocationDecoderP18decodeNextArgumentqd__yKlFTj
- _$s10Foundation4DateVSLAAMc
- _$s14XPCDistributed9XPCSystemC17InvocationDecoderV18decodeNextArgumentxyKSeRzSERzlF
- _$sSL2leoiySbx_xtFZTj
- _swift_conformsToProtocol2
CStrings:
+ "%{public}s %{public}s %{public}s %{bool}d"
+ "%{public}s: Peripheral not connected."
+ "Accessory %{private,mask.hash}s does not support play sound"
+ "Accessory not connected, will not execute command."
+ "Detected non-matching findMy accessory: %{public}s"
+ "Disconnected from %{public}s, error: %{public}@"
+ "Failed to get play sound capability for accessory %{private,mask.hash}s, error: %@"
+ "Peripheral not connected, not executing command"
+ "Updated companionDeviceOnline: %{bool,public}d"
+ "_execute(command:peripheral:executeOnlyIfConnected:)"
+ "clientBundleIdentifier"
+ "com.apple.icloud.findmydeviced.btfinding"
+ "companionDeviceOnline"
- "Disconnected from %{public}s"
- "_execute(command:peripheral:)"
```
