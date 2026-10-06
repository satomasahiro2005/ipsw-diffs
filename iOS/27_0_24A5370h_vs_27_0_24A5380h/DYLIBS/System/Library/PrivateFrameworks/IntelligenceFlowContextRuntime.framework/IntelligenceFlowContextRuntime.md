## IntelligenceFlowContextRuntime

> `/System/Library/PrivateFrameworks/IntelligenceFlowContextRuntime.framework/IntelligenceFlowContextRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1022e0` | `0x1087bc` | **`+0x64dc`** |
| `__TEXT.__oslogstring` | `0x3457` | `0x3a00` | **`+0x5a9`** |
| `__DATA_DIRTY.__data` | `0x2dc0` | `0x3168` | **`+0x3a8`** |
| `__TEXT.__eh_frame` | `0x8270` | `0x8598` | **`+0x328`** |
| `__DATA.__bss` | `0x1670` | `0x13f0` | **`-0x280`** |
| `__DATA.__data` | `0xe70` | `0xc90` | **`-0x1e0`** |
| `__AUTH_CONST.__const` | `0x50a0` | `0x5230` | **`+0x190`** |
| `__TEXT.__const` | `0x4a90` | `0x4930` | **`-0x160`** |
| `__DATA_DIRTY.__bss` | `0xc80` | `0xd80` | **`+0x100`** |
| `__TEXT.__swift5_capture` | `0x162c` | `0x172c` | **`+0x100`** |
| `__AUTH.__data` | `0x640` | `0x558` | **`-0xe8`** |
| `__TEXT.__unwind_info` | `0x2ef0` | `0x2fa8` | **`+0xb8`** |
| `__AUTH_CONST.__auth_got` | `0x25b0` | `0x2658` | **`+0xa8`** |
| `__TEXT.__swift5_reflstr` | `0xd8a` | `0xcf1` | **`-0x99`** |
| `__DATA_CONST.__got` | `0xfd0` | `0x1030` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x398` | `0x348` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x4a0` | `0x4f0` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x124c` | `0x1204` | **`-0x48`** |
| `__TEXT.__constg_swiftt` | `0x1a9c` | `0x1a6c` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1d80` | `0x1d60` | **`-0x20`** |
| `__TEXT.__cstring` | `0x1ccc` | `0x1cec` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x2b2c` | `0x2b10` | **`-0x1c`** |
| `__TEXT.__swift_as_cont` | `0x64c` | `0x65c` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x204` | `0x1f8` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0x3b4` | `0x3c0` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x38c` | `0x394` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1e8` | `0x1e4` | **`-0x4`** |

### Other Changes

```diff

-3600.144.5.501.3
+3600.147.12.501.3

-  Functions: 4780
+  Functions: 4846

-  CStrings:  369
+  CStrings:  383
Symbols:
+ _OBJC_CLASS_$_NSError
+ _swift_deallocBox
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "[UserContextFetcher] Context menu source element: appIntentsPayloadCount=%ld, hasExportableData=%{bool}d"
+ "[UserContextFetcher] Context menu: direct entities excluded, falling back to exportable data (hasExportableData=%{bool}d)"
+ "[UserContextFetcher] Context menu: extracted %ld direct entities from source element"
+ "[UserContextFetcher] Direct fetch %s for targetWindow=%{public}s, bundle=%{public}s"
+ "[UserContextFetcher] Direct fetch for targetWindow=%{public}s returned no content"
+ "[UserContextFetcher] Direct window fetch without process-pinning (pid or pidVersion missing)"
+ "[UserContextFetcher] Layout scan returned window element with missing identifier or processInfo"
+ "[UserContextFetcher] No usable target window after retries for bundle=%{public}s; marking layout-scan target foreground"
+ "[UserContextFetcher] Screenshot requested for window %s but not received"
+ "[UserContextFetcher] Window %{public}s (bundle=%{public}s) found in layout scan but returned no content in detailed fetch."
+ "[UserContextFetcher] Window %{public}s (bundle=%{public}s) is access-excluded; returning content-free skeleton without scraping"
+ "[UserContextFetcher] fetch(screenshotActiveWindow: %{bool,public}d, invocationContext: %{public}s)"
+ "[UserContextFetcher] fetchWindow(%{public}s) — UIIS returned %ld root(s) but no usable window content"
+ "[UserContextFetcher] fetchWindow(%{public}s) — UIIS returned empty hierarchy (no roots). processInfo=%{public}s"
+ "fetchUserContext starting for %{public}s, screenshot=%{bool}d, invocationContext=%{public}s"
+ "fetchUserContext: failed to decode request: %@"
+ "skeleton (access-excluded)"
- "[UserContextFetcher] No usable target window after retries for bundle=%{public}s"
- "[UserContextFetcher] Screenshot was requested for window %s but not received"
- "fetchUserContext starting for %{public}s, screenshot=%{bool}d"
```
