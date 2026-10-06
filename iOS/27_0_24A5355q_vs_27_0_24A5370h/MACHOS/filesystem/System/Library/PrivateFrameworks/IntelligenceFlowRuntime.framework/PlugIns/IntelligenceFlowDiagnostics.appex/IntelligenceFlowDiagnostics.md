## IntelligenceFlowDiagnostics

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/PlugIns/IntelligenceFlowDiagnostics.appex/IntelligenceFlowDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19b24` | `0x1a708` | **`+0xbe4`** |
| `__TEXT.__cstring` | `0x4d6` | `0x6b6` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0xc22` | `0xd12` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x1788` | `0x1838` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0x37f` | `0x3d0` | **`+0x51`** |
| `__TEXT.__objc_stubs` | `0x520` | `0x560` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x3cc` | `0x40c` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x9e0` | `0xa18` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x11a0` | `0x11c0` | **`+0x20`** |
| `__TEXT.__const` | `0x1568` | `0x1580` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x168` | `0x178` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x8d8` | `0x8e8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6e0` | `0x6f0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x616` | `0x624` | **`+0xe`** |
| `__DATA.__data` | `0x7c0` | `0x7c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-3600.138.6.501.17
+3600.144.5.501.3

-  Functions: 710
-  Symbols:   164
-  CStrings:  126
+  Functions: 731
+  Symbols:   168
+  CStrings:  137
Symbols:
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_NSError
+ _objc_retain_x28
+ _swift_retain_x22
CStrings:
+ "---\n# IntelligenceFlowDiagnostics was invoked without a session ID\nvalidation: \"none\"\nresult: \"error\"\ninput: \"No session ID provided to IntelligenceFlowDiagnostics\"\n"
+ "---\n# No SecurityValidationEvents were retrieved for the requested interactionIds\nvalidation: \"none\"\nresult: \"none\"\ninput: \"\"\n"
+ "IntelligenceFlowDiagnostics: missing-session-id placeholder error: %@"
+ "No app group container for group.com.apple.intelligenceflow"
+ "SecurityDiagnosticsAttachment: no events found - writing placeholder attachment"
+ "SecurityDiagnosticsAttachment: writing missing-session-id placeholder to %s"
+ "com.apple.TapToRadar"
+ "com.apple.taptoradard"
+ "containerURLForSecurityApplicationGroupIdentifier:"
+ "group.com.apple.intelligenceflow"
+ "initWithDomain:code:userInfo:"
```
