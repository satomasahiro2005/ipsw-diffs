## Preview

> `/private/var/staged_system_apps/Preview.app/Preview`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19f7b8` | `0x1a22e0` | **`+0x2b28`** |
| `__TEXT.__const` | `0x11cb8` | `0x11fa8` | **`+0x2f0`** |
| `__DATA.__data` | `0xc784` | `0xc9cc` | **`+0x248`** |
| `__TEXT.__eh_frame` | `0x7640` | `0x7888` | **`+0x248`** |
| `__DATA.__objc_const` | `0x6188` | `0x6378` | **`+0x1f0`** |
| `__DATA_CONST.__const` | `0xc0c8` | `0xc290` | **`+0x1c8`** |
| `__TEXT.__swift5_typeref` | `0xacb6` | `0xae0c` | **`+0x156`** |
| `__TEXT.__constg_swiftt` | `0x6780` | `0x6888` | **`+0x108`** |
| `__TEXT.__unwind_info` | `0x66f0` | `0x67f8` | **`+0x108`** |
| `__TEXT.__swift5_fieldmd` | `0x4684` | `0x473c` | **`+0xb8`** |
| `__TEXT.__objc_classname` | `0x1981` | `0x1a21` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x65ff` | `0x669f` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x20cc` | `0x2158` | **`+0x8c`** |
| `__TEXT.__swift5_reflstr` | `0x4805` | `0x4885` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x55a0` | `0x55f0` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x2888` | `0x28b8` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x1752` | `0x1782` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x1c19` | `0x1c49` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x2ae8` | `0x2b10` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x4c0` | `0x4e8` | **`+0x28`** |
| `__DATA.__objc_data` | `0x2e58` | `0x2e78` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1888` | `0x18a0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x12e4` | `0x12fc` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x244` | `0x258` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x260` | `0x274` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x1b8` | `0x1cc` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x300` | `0x310` | **`+0x10`** |
| `__TEXT.__cstring` | `0x6e2b` | `0x6e1b` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x540` | `0x54c` | **`+0xc`** |
| `__DATA.__common` | `0x5f0` | `0x5f8` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x15d8` | `0x15e0` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x3c` | `0x44` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x8c4` | `0x8c8` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x8c` | `0x90` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-1027.1.0.0.0
+1029.0.0.0.0

-  Functions: 9057
-  Symbols:   2604
-  CStrings:  2137
+  Functions: 9132
+  Symbols:   2611
+  CStrings:  2146
Symbols:
+ _$s10Foundation17URLResourceValuesV22UniformTypeIdentifiersE07contentE0AD6UTTypeVSgvg
+ _$s7SwiftUI4ViewPAAE9statusBar6hiddenQrSb_tF
+ _$s7SwiftUI4ViewPAAE9statusBar6hiddenQrSb_tFQOMQ
+ _$s8PaperKit14CanvasDelegateP6canvas_13didAcceptDropyAA03AnyC0C_AA0H4InfoVtFTq
+ _$s8PaperKit14CanvasDelegateP6canvas_16shouldAcceptDropSbAA03AnyC0C_AA0H4InfoVtFTq
+ _$s8PaperKit14CanvasDelegatePAAE6canvas_13didAcceptDropyAA03AnyC0C_AA0H4InfoVtF
+ _$s8PaperKit14CanvasDelegatePAAE6canvas_16shouldAcceptDropSbAA03AnyC0C_AA0H4InfoVtF
+ _NSURLContentTypeKey
- _swift_release_x10
CStrings:
+ "Could not fetch FPItem for %{private}s: %@"
+ "PreviewDocumentItemContentDidChange"
+ "_TtC17PreviewFoundation15PreviewDocument"
+ "_TtC17PreviewFoundation30DocumentItemContentObservation"
+ "_TtC17PreviewFoundationP33_068119E44FEA94F5F134B3379F0E872226NotificationObserverHolder"
+ "_statusBarHidden"
+ "currentTraitCollection"
+ "documentItemContentObservation"
+ "fetchItemForURL:completionHandler:"
+ "fetchItemResult(for:)"
+ "observerHolder"
+ "presentedItemDidChange"
+ "token"
+ "userInterfaceIdiom"
+ "v24@?0@\"FPItem\"8@\"NSError\"16"
- "PreviewFoundation/PreviewTelemetryLogger.swift"
- "_TtC17PreviewFoundation8Document"
- "com.apple.FileProvider.LocalStorage"
- "itemForURL:error:"
- "itemIDForURL:error:"
- "providerID"
```
