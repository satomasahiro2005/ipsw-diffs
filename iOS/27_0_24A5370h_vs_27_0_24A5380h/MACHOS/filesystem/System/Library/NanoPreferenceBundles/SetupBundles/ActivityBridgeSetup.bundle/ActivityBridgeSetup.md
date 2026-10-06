## ActivityBridgeSetup

> `/System/Library/NanoPreferenceBundles/SetupBundles/ActivityBridgeSetup.bundle/ActivityBridgeSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53d9c` | `0x548f4` | **`+0xb58`** |
| `__TEXT.__swift5_typeref` | `0x3f4b` | `0x3bf1` | **`-0x35a`** |
| `__TEXT.__objc_methname` | `0x4de5` | `0x4f25` | **`+0x140`** |
| `__TEXT.__objc_stubs` | `0x3900` | `0x3a20` | **`+0x120`** |
| `__TEXT.__const` | `0x3590` | `0x3510` | **`-0x80`** |
| `__DATA.__objc_data` | `0xe20` | `0xe90` | **`+0x70`** |
| `__DATA.__objc_const` | `0x4080` | `0x40e0` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x12a4` | `0x1304` | **`+0x60`** |
| `__TEXT.__cstring` | `0x156c` | `0x15cc` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0xb4f` | `0xbaf` | **`+0x60`** |
| `__DATA.__data` | `0x21c0` | `0x2170` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x2260` | `0x22b0` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x13d8` | `0x1420` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x23b0` | `0x2380` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xa18` | `0xa3c` | **`+0x24`** |
| `__TEXT.__swift5_capture` | `0x49c` | `0x4bc` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x11e8` | `0x11d0` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x1270` | `0x1288` | **`+0x18`** |
| `__DATA.__bss` | `0x1f78` | `0x1f68` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x830` | `0x828` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x1320` | `0x1328` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.0.104.0.0
+2027.0.110.0.0

-  Functions: 1599
+  Functions: 1610

-  CStrings:  1180
+  CStrings:  1195
CStrings:
+ "DAILY_BUTTON_LABEL"
+ "GOAL_STEPPER_LABEL"
+ "SCHEDULE_BUTTON_LABEL"
+ "appliedTwoColumnLayout"
+ "availableHeightConstraints"
+ "constant"
+ "constraintEqualToConstant:"
+ "constraintLessThanOrEqualToAnchor:constant:"
+ "constraintLessThanOrEqualToConstant:"
+ "deactivateConstraints:"
+ "isTwoColumnLayoutEnabled"
+ "sendActionsForControlEvents:"
+ "setAccessibilityLabel:"
+ "setPriority:"
+ "videoLayoutConstraints"
```
