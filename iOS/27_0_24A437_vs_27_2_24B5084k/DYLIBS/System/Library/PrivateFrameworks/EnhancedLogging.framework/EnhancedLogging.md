## EnhancedLogging

> `/System/Library/PrivateFrameworks/EnhancedLogging.framework/EnhancedLogging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x46e3c` | `0x47f00` | **`+0x10c4`** |
| `__DATA.__bss` | `0x7980` | `0x7e00` | **`+0x480`** |
| `__AUTH_CONST.__const` | `0x5e68` | `0x6260` | **`+0x3f8`** |
| `__TEXT.__const` | `0x4764` | `0x4b04` | **`+0x3a0`** |
| `__TEXT.__swift5_typeref` | `0x12fe` | `0x140e` | **`+0x110`** |
| `__TEXT.__cstring` | `0x106b` | `0x116b` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x108c` | `0x1178` | **`+0xec`** |
| `__TEXT.__swift5_reflstr` | `0xc58` | `0xd18` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x9e8` | `0xa78` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x13f8` | `0x1480` | **`+0x88`** |
| `__TEXT.__swift5_assocty` | `0x2a0` | `0x2e8` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x17d0` | `0x1808` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x3cc` | `0x3f8` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x9d8` | `0xa00` | **`+0x28`** |
| `__DATA.__data` | `0xe78` | `0xea0` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0xc0a` | `0xbea` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x13f4` | `0x1414` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0x8c` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x2b8` | `0x2c8` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x11c` | `0x12c` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-267.2.3.0.0
+277.40.4.0.0

-  Functions: 2318
-  Symbols:   961
-  CStrings:  176
+  Functions: 2372
+  Symbols:   978
+  CStrings:  188
Symbols:
+ ___swift_memcpy41_8
+ _associated conformance 15EnhancedLogging0aB14AnalyticsEventO11InteractionOSHAASQ
+ _associated conformance 15EnhancedLogging0aB14AnalyticsEventO16NetworkInterfaceOSHAASQ
+ _associated conformance 15EnhancedLogging0aB14AnalyticsEventO18CancellationReasonOSHAASQ
+ _get_enum_tag_for_layout_string 15EnhancedLogging0aB14AnalyticsEventO
+ _swift_getAssociatedTypeWitness
+ _symbolic $s15EnhancedLogging16DeviceConstraintP
+ _symbolic SS14callingProcess_t
+ _symbolic Sd15durationSeconds______9interfaceSS11errorDomainSi0D4Codet 15EnhancedLogging0aB14AnalyticsEventO16NetworkInterfaceO
+ _symbolic Sd15durationSeconds______9interfaceSi9fileCount_____04byteE0t 15EnhancedLogging0aB14AnalyticsEventO16NetworkInterfaceO s5Int64V
+ _symbolic _____ 15EnhancedLogging0aB14AnalyticsEventO
+ _symbolic _____ 15EnhancedLogging0aB14AnalyticsEventO11InteractionO
+ _symbolic _____ 15EnhancedLogging0aB14AnalyticsEventO16NetworkInterfaceO
+ _symbolic _____ 15EnhancedLogging0aB14AnalyticsEventO18CancellationReasonO
+ _symbolic _____11interaction_t 15EnhancedLogging0aB14AnalyticsEventO11InteractionO
+ _symbolic _____6reason_t 15EnhancedLogging0aB14AnalyticsEventO18CancellationReasonO
+ _type_layout_string 15EnhancedLogging0aB14AnalyticsEventO
CStrings:
+ "Checking WAPI for a TargetDevice that does not have WAPI set"
+ "Headless"
+ "Interactive"
+ "cellular"
+ "com.apple.EnhancedLogging.CollectionStarted"
+ "com.apple.EnhancedLogging.SessionCancelled"
+ "com.apple.EnhancedLogging.UploadCompleted"
+ "com.apple.EnhancedLogging.UploadFailed"
+ "remote"
+ "unknown"
+ "user"
+ "wifi"
+ "wired"
- "Checking WAPI for a TargetDevice that does not have WAPI set (likely a bad compatable call)."
```
