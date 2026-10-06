## HearingWidgetExtension

> `/Applications/HearingApp.app/PlugIns/HearingWidgetExtension.appex/HearingWidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15014` | `0x15540` | **`+0x52c`** |
| `__TEXT.__swift5_typeref` | `0x2dba` | `0x2ed6` | **`+0x11c`** |
| `__DATA_CONST.__const` | `0x9bb` | `0x91b` | **`-0xa0`** |
| `__TEXT.__oslogstring` | `0x34a` | `0x39a` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x140` | `0xf8` | **`-0x48`** |
| `__TEXT.__objc_stubs` | `0x360` | `0x3a0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0xb4e` | `0xb6f` | **`+0x21`** |
| `__TEXT.__auth_stubs` | `0x1180` | `0x11a0` | **`+0x20`** |
| `__DATA.__data` | `0x930` | `0x940` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x460` | `0x470` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x8c8` | `0x8d8` | **`+0x10`** |
| `__TEXT.__const` | `0x1318` | `0x1328` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4c8` | `0x4d8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x220` | `0x22c` | **`+0xc`** |
| `__DATA.__objc_data` | `0x130` | `0x138` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x590` | `0x598` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x260` | `0x268` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0x236` | `0x23e` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-536.0.0.0.0
+539.1.0.0.0

-  Functions: 416
-  Symbols:   156
-  CStrings:  260
+  Functions: 410
+  Symbols:   159
+  CStrings:  262
Symbols:
+ _OBJC_CLASS_$_HUHearingAidSettings
+ _objc_release_x22
+ _objc_retain_x23
+ _objc_retain_x28
- _objc_retain_x21
CStrings:
+ "HearingWidget: MuteVolumeIntent — hearing aid not reachable"
+ "HearingWidget: MuteVolumeIntent — toggling microphone mute to %{bool}d"
+ "HearingWidget: fast path — device '%s' already loaded"
+ "HearingWidget: makeEntry — device '%s' hasConnection=%{bool}d reachable=%{bool}d"
+ "T@\"AXHearingAidMode\",R,&"
+ "T@\"NSNumber\",R"
+ "hearingAidMicrophoneMuted"
+ "setHearingAidMicrophoneMuted:"
- "HearingWidget: MuteVolumeIntent — muting all volumes"
- "HearingWidget: MuteVolumeIntent — no device available"
- "HearingWidget: buildAndResolve — device '%s' hasConnection=%{bool}d reachable=%{bool}d"
- "T@\"AXHearingAidMode\",R,&,N"
- "T@\"NSNumber\",R,N"
- "T@\"NSString\",R,&,N"
```
