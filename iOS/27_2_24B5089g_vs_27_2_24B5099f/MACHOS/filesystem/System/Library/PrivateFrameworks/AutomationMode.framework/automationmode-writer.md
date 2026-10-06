## automationmode-writer

> `/System/Library/PrivateFrameworks/AutomationMode.framework/automationmode-writer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9bc0` | `0xb250` | **`+0x1690`** |
| `__TEXT.__cstring` | `0x320` | `0x410` | **`+0xf0`** |
| `__TEXT.__auth_stubs` | `0x950` | `0xa30` | **`+0xe0`** |
| `__DATA_CONST.__auth_got` | `0x4b0` | `0x520` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x126` | `0x194` | **`+0x6e`** |
| `__TEXT.__objc_methname` | `0x6a1` | `0x6e1` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x300` | `0x340` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xb60` | `0xba0` | **`+0x40`** |
| `__DATA.__data` | `0x410` | `0x440` | **`+0x30`** |
| `__TEXT.__const` | `0x1f2` | `0x220` | **`+0x2e`** |
| `__TEXT.__eh_frame` | `0x40` | `0x68` | **`+0x28`** |
| `__DATA.__objc_const` | `0x440` | `0x460` | **`+0x20`** |
| `__DATA.__objc_data` | `0x220` | `0x240` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x120` | `0x140` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x135` | `0x153` | **`+0x1e`** |
| `__TEXT.__constg_swiftt` | `0x1ac` | `0x1c4` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1b8` | `0x1d0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1b8` | `0x1c8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xec` | `0xf8` | **`+0xc`** |
| `__DATA.__common` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x58` | `0x60` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-34.0.0.0.0
+35.0.0.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 117
-  Symbols:   212
-  CStrings:  165
+  Functions: 122
+  Symbols:   229
+  CStrings:  174
Symbols:
+ _$s10Foundation3URLV22appendingPathComponentyACSSF
+ _$s10Foundation3URLV25deletingLastPathComponentACyF
+ _$s10Foundation3URLV4pathSSvg
+ _$s10Foundation4DateV17timeIntervalSinceySdACF
+ _$s10Foundation4DateV21timeIntervalSince1970ACSd_tcfC
+ _$s10Foundation4DateV21timeIntervalSince1970Sdvg
+ _$s10Foundation4DateVACycfC
+ _$s10Foundation4DateVMa
+ _$s10Foundation4DateVMn
+ _$s10Foundation4DateVSQAAMc
+ _$sSQ2eeoiySbx_xtFZTj
+ _$sSd11descriptionSSvg
+ _$sSy10FoundationE5write6toFile10atomically8encodingyqd___SbSSAAE8EncodingVtKSyRd__lF
+ _$syycWV
+ _AnalyticsSendEvent
+ _swift_release_x21
+ _swift_release_x23
+ _swift_retain_x21
- _objc_retain_x21
CStrings:
+ "Failed to persist last approval time: %{public}s"
+ "authenticationResult"
+ "com.apple.dt.automationmode.AutomationModeAuthenticationEvent"
+ "com.apple.dt.automationmode.enableAutomationmodeWithoutAuthentication"
+ "hasPriorApproval"
+ "initWithBool:"
+ "initWithInt:"
+ "requestedAuthentication"
+ "sendAnalyticsEvent"
```
