## assistant_cdmd

> `/System/Library/PrivateFrameworks/ContinuousDialogManagerService.framework/assistant_cdmd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x86dc` | `0x9400` | **`+0xd24`** |
| `__DATA_CONST.__const` | `0x920` | `0xbf0` | **`+0x2d0`** |
| `__TEXT.__cstring` | `0x6ba` | `0x86a` | **`+0x1b0`** |
| `__TEXT.__swift5_capture` | `0x220` | `0x334` | **`+0x114`** |
| `__TEXT.__objc_methname` | `0x92f` | `0xa30` | **`+0x101`** |
| `__TEXT.__objc_stubs` | `0x400` | `0x460` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x28c` | `0x2d8` | **`+0x4c`** |
| `__DATA.__objc_selrefs` | `0x220` | `0x250` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0xd8` | `0xf8` | **`+0x20`** |
| `__DATA.__objc_const` | `0xa30` | `0xa48` | **`+0x18`** |
| `__DATA.__objc_data` | `0x330` | `0x348` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x3c8` | `0x3e0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x390` | `0x3a8` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.31.14.0.0
+3605.16.1.0.0

-  Functions: 340
+  Functions: 410

-  CStrings:  196
+  CStrings:  208
CStrings:
+ "Process Magic Compose NLU request called by XPC client."
+ "Process Magic Compose NLU request response is ready. Sending to client."
+ "Process TrustedAgent NLU request called by XPC client."
+ "Process TrustedAgent NLU request response is ready. Sending to client."
+ "Process contact NLU request called by XPC client."
+ "Process contact NLU request response is ready. Sending to client."
+ "processContactNluRequest:completionHandler:"
+ "processContactNluRequestWithCdmNluRequest:completionHandler:"
+ "processMagicComposeNluRequest:completionHandler:"
+ "processMagicComposeNluRequestWithCdmNluRequest:completionHandler:"
+ "processTrustedAgentNluRequest:completionHandler:"
+ "processTrustedAgentNluRequestWithCdmNluRequest:completionHandler:"
```
