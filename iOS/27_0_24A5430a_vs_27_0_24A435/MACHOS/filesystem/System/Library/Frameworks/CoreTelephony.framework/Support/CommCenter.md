## CommCenter

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b337b8` | `0x1b358b0` | **`+0x20f8`** |
| `__TEXT.__cstring` | `0x80b0c` | `0x80c6c` | **`+0x160`** |
| `__TEXT.__gcc_except_tab` | `0x1d4ae8` | `0x1d4bcc` | **`+0xe4`** |
| `__TEXT.__oslogstring` | `0x17479b` | `0x17486b` | **`+0xd0`** |
| `__DATA_CONST.__cfstring` | `0x29a20` | `0x29ae0` | **`+0xc0`** |
| `__TEXT.__const` | `0x23ab54` | `0x23ac14` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x16b7b8` | `0x16b838` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0xae708` | `0xae728` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x19154` | `0x1915c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-13487.6.0.0.0
+13487.7.0.0.0

-  Functions: 132696
+  Functions: 132707

-  CStrings:  56234
+  CStrings:  56250
Symbols:
+ _swift_retain_x10
- _swift_retain_x9
CStrings:
+ "CBMessage-V63"
+ "CFUserNotificationDisplayAlert failed with result: %d"
+ "Clearing Pending HardwareSimSlot Selection."
+ "Failed to enable back psim"
+ "Failed to fetch alert strings"
+ "LocalizationInterface not found"
+ "SIM_TRAY_HARDWARE_SIM_CONFIG_ALERT_CONFIGURE"
+ "SIM_TRAY_HARDWARE_SIM_CONFIG_ALERT_MESSAGE"
+ "SIM_TRAY_HARDWARE_SIM_CONFIG_ALERT_MESSAGE_NO_ESIM"
+ "SIM_TRAY_HARDWARE_SIM_CONFIG_ALERT_MESSAGE_PLURAL"
+ "SIM_TRAY_HARDWARE_SIM_CONFIG_ALERT_TITLE"
+ "Showing tray inserted alert"
+ "configure,cancel"
+ "sim_tray_config_no_esim"
+ "sim_tray_config_plural_sim"
+ "sim_tray_config_single_sim"
```
