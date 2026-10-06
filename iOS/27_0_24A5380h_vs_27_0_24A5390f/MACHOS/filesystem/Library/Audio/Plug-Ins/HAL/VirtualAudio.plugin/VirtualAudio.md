## VirtualAudio

> `/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x52de7c` | `0x52efb8` | **`+0x113c`** |
| `__TEXT.__oslogstring` | `0x55de4` | `0x56013` | **`+0x22f`** |
| `__TEXT.__gcc_except_tab` | `0x5f704` | `0x5f834` | **`+0x130`** |
| `__DATA.__bss` | `0x25648` | `0x25678` | **`+0x30`** |
| `__TEXT.__const` | `0xb1410` | `0xb13e0` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x14500` | `0x14520` | **`+0x20`** |
| `__TEXT.__cstring` | `0x36bec` | `0x36be6` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dof_Aggregate`
- `__TEXT.__dof_VirtualA0`
- `__TEXT.__dof_VirtualAu`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1450.0.0.0.0
+1451.108.1.0.0

-  Functions: 12357
+  Functions: 12360

-  CStrings:  12076
+  CStrings:  12081
CStrings:
+ "%25s:%-5d - Forcing Change for %s: cached route references a removed port."
+ "%25s:%-5d Bluetooth device %u: skip %s at publish (VA will drive HW volume on this device at the current PME state)"
+ "%25s:%-5d Clamped input volume control maximum to %f for call certification."
+ "%25s:%-5d LP+HP mic coexistence barred: forcing %s onto the codec HP mic (another VAD holds it; product lacks supports-concurrent-hp-lp-mics)."
+ "%25s:%-5d creating a Puffin input port with name \"%s\" and UID \"%s\""
+ "@@ Strips Jul 13 2026 21:40:16"
+ "Concurrent LP and HP built-in mic on a product lacking supports-concurrent-hp-lp-mics — LP mic VAD(s): %{public}s; HP mic VAD(s): %{public}s. One capture path will be silenced."
- "%25s:%-5d Bluetooth device %u: skip %s at publish (VA policy will drive HW volume on this device)"
- "@@ Strips Jun 27 2026 22:18:31"
```
