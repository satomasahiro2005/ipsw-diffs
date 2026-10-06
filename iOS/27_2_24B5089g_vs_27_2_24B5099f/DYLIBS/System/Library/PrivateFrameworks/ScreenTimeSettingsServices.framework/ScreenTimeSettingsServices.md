## ScreenTimeSettingsServices

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsServices.framework/ScreenTimeSettingsServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x171f38` | `0x173a44` | **`+0x1b0c`** |
| `__DATA.__bss` | `0x216b0` | `0x217b0` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0xa098` | `0xa198` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x10c50` | `0x10d40` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x503f` | `0x511c` | **`+0xdd`** |
| `__TEXT.__const` | `0x1bc5c` | `0x1bcdc` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x5ef0` | `0x5f60` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x23b0` | `0x2410` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x4f43` | `0x4fa2` | **`+0x5f`** |
| `__TEXT.__swift5_fieldmd` | `0x6904` | `0x6934` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x838` | `0x864` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x1130` | `0x1150` | **`+0x20`** |
| `__DATA.__data` | `0x3150` | `0x3170` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x2dc` | `0x2ec` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x5848` | `0x5852` | **`+0xa`** |
| `__AUTH_CONST.__objc_const` | `0xfa8` | `0xfb0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x560` | `0x568` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x4440` | `0x4448` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x458` | `0x460` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1a3c` | `0x1a44` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x15c` | `0x164` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x180` | `0x188` | **`+0x8`** |

### Other Changes

```diff

-97.1.9.0.0
+97.1.12.0.0

-  Functions: 9512
-  Symbols:   2590
-  CStrings:  635
+  Functions: 9543
+  Symbols:   2592
+  CStrings:  641
Symbols:
+ ___swift_closure_destructor.259Tm
+ ___swift_closure_destructor.326Tm
+ _keypath_set.202Tm
+ _objc_retain_x27
+ _symbolic Shy_____G 26ScreenTimeSettingsServices0abC0C0B10AllowancesV5GroupV
- ___swift_closure_destructor.257Tm
- ___swift_closure_destructor.313Tm
- _keypath_set.199Tm
CStrings:
+ "Adding time allowance groups: %{public}s"
+ "Removing time allowance groups: %{public}s"
+ "com.apple.screentimesettings.block-list-addition"
+ "com.apple.screentimesettings.pause-activity-tapped"
+ "com.apple.screentimesettings.unlimited-access-tapped"
+ "migrateAppData(from:to:)"
```
