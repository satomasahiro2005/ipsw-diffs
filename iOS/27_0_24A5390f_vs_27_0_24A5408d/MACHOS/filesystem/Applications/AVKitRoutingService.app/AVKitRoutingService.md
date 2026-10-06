## AVKitRoutingService

> `/Applications/AVKitRoutingService.app/AVKitRoutingService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b914` | `0x5d89c` | **`+0x1f88`** |
| `__DATA.__data` | `0x1a90` | `0x1b70` | **`+0xe0`** |
| `__TEXT.__eh_frame` | `0x452c` | `0x4474` | **`-0xb8`** |
| `__TEXT.__objc_methname` | `0x36cf` | `0x377f` | **`+0xb0`** |
| `__DATA.__objc_const` | `0x23b8` | `0x2458` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0xcf8` | `0xd88` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0xf50` | `0xfd8` | **`+0x88`** |
| `__TEXT.__const` | `0x2d50` | `0x2dc0` | **`+0x70`** |
| `__TEXT.__cstring` | `0x1482` | `0x14ec` | **`+0x6a`** |
| `__TEXT.__swift5_typeref` | `0x3688` | `0x36d6` | **`+0x4e`** |
| `__TEXT.__oslogstring` | `0x135f` | `0x139f` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0xa49` | `0xa89` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x938` | `0x908` | **`-0x30`** |
| `__DATA_CONST.__cfstring` | `0x6a0` | `0x6c0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2608` | `0x2620` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x1c4` | `0x1dc` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1980` | `0x1968` | **`-0x18`** |
| `__DATA.__common` | `0x48` | `0x58` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x868` | `0x878` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1b20` | `0x1b30` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x520` | `0x530` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x2d0` | `0x2e0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xda0` | `0xda8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4c0` | `0x4b8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1360.69.1.0.0
+1360.75.1.3.0

-  Functions: 1727
-  Symbols:   814
-  CStrings:  893
+  Functions: 1754
+  Symbols:   815
+  CStrings:  901
Symbols:
+ _$s7SwiftUI7CapsuleVAA4ViewAAMc
+ _$s7SwiftUI7CapsuleVMa
+ _$s7SwiftUI7CapsuleVMn
- _$s7SwiftUI16RoundedRectangleVAA4ViewAAMc
- _$s7SwiftUI5ColorVN
CStrings:
+ "AVRoutingInputController.refreshPickedRoute"
+ "[%s] .AVInputContextCanSetInputGainDidChange received: canSetInputGain: %{bool}d"
+ "[%s] canSetInputGain: %{bool}d (raw: %{bool}d, isBuiltIn: %{bool}d)"
+ "[%s] refreshInputGain: gain: %f, settability: %{bool}d"
+ "com.apple.health.HealthMediaContentTester"
+ "computePickedRoute(skipNotify:)"
+ "highestCommittedPickedRouteTicket"
+ "highestNotifiedPickedRouteTicket"
+ "inputPickerContext"
+ "lastNotifiedPickedRouteCache"
+ "pendingCoalescedOperations"
+ "pickedRouteTicketCounter"
+ "refreshInputGain"
+ "taskGenerations"
- "[%s] .AVInputContextCanSetInputGainDidChange received"
- "[%s] got new input gain from context: %f, settability: %{bool}d"
- "[%s] input gain settability updated: %{bool}d"
- "inputPickercontext"
- "nextSequence"
- "updatePickedRoutesIfNeeded(skipNotify:)"
```
