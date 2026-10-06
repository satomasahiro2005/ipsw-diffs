## VirtualAudio

> `/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5582dc` | `0x558b6c` | **`+0x890`** |
| `__TEXT.__oslogstring` | `0x58ca1` | `0x58deb` | **`+0x14a`** |
| `__DATA_CONST.__const` | `0x296b0` | `0x29728` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x14f80` | `0x14fd8` | **`+0x58`** |
| `__TEXT.__cstring` | `0x376f2` | `0x37739` | **`+0x47`** |
| `__TEXT.__gcc_except_tab` | `0x65bec` | `0x65c2c` | **`+0x40`** |
| `__DATA_CONST.__objc_intobj` | `0x30` | `—` | **`-0x30`** |
| `__TEXT.__const` | `0xb4938` | `0xb4910` | **`-0x28`** |
| `__TEXT.__objc_stubs` | `0x12a0` | `0x1280` | **`-0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0x18` | `—` | **`-0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0xf99` | `0xf89` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x580` | `0x578` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
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

-1451.208.0.0.0
+1451.209.0.0.0

-  Functions: 12517
-  Symbols:   836
-  CStrings:  12319
+  Functions: 12531
+  Symbols:   834
+  CStrings:  12326
Symbols:
- _OBJC_CLASS_$_NSConstantArray
- _OBJC_CLASS_$_NSConstantIntegerNumber
CStrings:
+ "%25s:%-5d Applying global calibration of 0 dB for repaired mic '%s'"
+ "%25s:%-5d Failed to read repair state for syscfg key '%s' - skipping"
+ "%25s:%-5d Repair detected for mics hosted under syscfg key '%s' - state: %s"
+ "%25s:%-5d Repair detected for syscfg key '%s' - calibrating %s"
+ "%25s:%-5d Repair detected for syscfg key '%s', but it hosts no mic trim gains on this product - nothing to calibrate"
+ "%25s:%-5d Repaired Mic Check returned syscfg keys: %s"
+ "@@ Strips Sep 12 2026 08:23:41"
+ "Issue"
+ "Mismatch"
+ "Original"
+ "RepairedWithServicePart"
+ "RepairedWithUsedPart"
+ "Unsupported"
- "%25s:%-5d Back Glass repair detected"
- "%25s:%-5d Cover Glass repair detected"
- "%25s:%-5d Repaired Mic Check returned: %s"
- "@@ Strips Sep  3 2026 00:42:08"
- "I"
- "integerValue"
```
