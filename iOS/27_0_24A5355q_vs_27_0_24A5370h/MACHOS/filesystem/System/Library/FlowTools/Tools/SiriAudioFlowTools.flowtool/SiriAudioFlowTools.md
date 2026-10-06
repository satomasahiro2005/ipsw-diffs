## SiriAudioFlowTools

> `/System/Library/FlowTools/Tools/SiriAudioFlowTools.flowtool/SiriAudioFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a670` | `0x63178` | **`+0x8b08`** |
| `__TEXT.__oslogstring` | `0x3598` | `0x3938` | **`+0x3a0`** |
| `__TEXT.__eh_frame` | `0x2458` | `0x2708` | **`+0x2b0`** |
| `__TEXT.__auth_stubs` | `0x16a0` | `0x18e0` | **`+0x240`** |
| `__DATA_CONST.__auth_got` | `0xb58` | `0xc78` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x1400` | `0x1480` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x3a8` | `0x420` | **`+0x78`** |
| `__DATA.__data` | `0x2458` | `0x24c0` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x1854` | `0x18bc` | **`+0x68`** |
| `__TEXT.__const` | `0x6cc0` | `0x6d10` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x20d0` | `0x2110` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x3340` | `0x3368` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x138` | `0x150` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x180` | `0x194` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x80` | `0x90` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xe8` | `0xf0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.27.4.0.0
+3600.33.2.0.0

-  Functions: 1632
-  Symbols:   189
-  CStrings:  300
+  Functions: 1656
+  Symbols:   192
+  CStrings:  309
Symbols:
+ __swiftEmptySetSingleton
+ _objc_retain_x24
+ _swift_release_x12
CStrings:
+ "AppIntentsWrapper.wrappedAppIntent for %s on device %s: %s"
+ "PlayAudioAppIntentExecutionStrategy.findMatchingTargetType() - no TypeDefinition for source type %s"
+ "PlayAudioAppIntentExecutionStrategy.findMatchingTargetType() - no matching type on %s (device %s) for schema %s"
+ "PlayAudioAppIntentExecutionStrategy.findMatchingTargetType() - schema match on %s: %s → %s"
+ "PlayAudioAppIntentExecutionStrategy.findMatchingTargetType() - source type has no AssistantSchema conformance"
+ "PlayAudioAppIntentExecutionStrategy.makeDeviceTargetedInvocation() - found %s (%s) on device %s"
+ "PlayAudioAppIntentExecutionStrategy.makeDeviceTargetedInvocation() - invocation target: %s"
+ "PlayAudioAppIntentExecutionStrategy.makeDeviceTargetedInvocation() - no PlayAudioIntent on device %s, falling back to local"
+ "PlayAudioAppIntentExecutionStrategy.makeDeviceTargetedInvocation() - targeting device %s with bundleId %s"
```
