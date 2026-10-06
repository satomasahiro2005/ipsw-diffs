## modelmanagerd

> `/usr/libexec/modelmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ac8b0` | `0x1b4730` | **`+0x7e80`** |
| `__DATA_CONST.__const` | `0x7ca8` | `0x82d8` | **`+0x630`** |
| `__TEXT.__oslogstring` | `0x9c49` | `0x9e69` | **`+0x220`** |
| `__TEXT.__swift5_capture` | `0x2304` | `0x2504` | **`+0x200`** |
| `__TEXT.__eh_frame` | `0x1664c` | `0x16514` | **`-0x138`** |
| `__TEXT.__swift5_reflstr` | `0x2513` | `0x25b3` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1ee0` | `0x1f50` | **`+0x70`** |
| `__TEXT.__auth_stubs` | `0x3d50` | `0x3da0` | **`+0x50`** |
| `__DATA.__common` | `0x5f8` | `0x640` | **`+0x48`** |
| `__DATA.__data` | `0x6348` | `0x6378` | **`+0x30`** |
| `__TEXT.__const` | `0x6786` | `0x67b6` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x2178` | `0x21a8` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1eb0` | `0x1ed8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x6c70` | `0x6c98` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x2d3c` | `0x2d5c` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0xac4` | `0xad0` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xf38` | `0xf30` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x94c` | `0x954` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1220` | `0x121c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-698.0.0.502.1
+703.0.11.0.0

-  Functions: 8915
-  Symbols:   1677
-  CStrings:  1204
+  Functions: 9078
+  Symbols:   1681
+  CStrings:  1214
Symbols:
+ _$s20ModelManagerServices16RemoteIPCRequestO07ExecuteD16StreamingRequestV17useCaseIdentifierSSSgvg
+ _$s20ModelManagerServices16RemoteIPCRequestO07ExecuteD7RequestV17useCaseIdentifierSSSgvg
+ _$ss15ContinuousClockV3nowAB7InstantVvg
+ _$ss15ContinuousClockV7InstantV8duration2tos8DurationVAD_tF
+ _$ss15ContinuousClockVABycfC
+ _$ss8DurationV11descriptionSSvg
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "Aborting in-flight unload of re-acquired asset %s before dispatch"
+ "Created session %s on behalf of pid %d with priority %s, task priority %s"
+ "EchoFullBudgetBundleID"
+ "EchoFullBudgetSecondInstanceBundleID"
+ "Foreground group %s is blocked behind background slot-holder %s; preempting its requests %s"
+ "HostFullBudgetBundleID"
+ "Prewarm request %s: task priority %s, process priority %s"
+ "Skipping foreground asset claim for session %s: bundle not yet resolved"
+ "Skipping full prewarm for session %s: already prewarmed and all assets loaded"
+ "Skipping prewarmBundle for session %s: already prewarmed and assets are loaded"
+ "prewarmBundle completed for session %s in %s"
- "Created session %s on behalf of pid %d with priority %s"
```
