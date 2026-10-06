## AccessoryTransportExtension

> `/System/Library/Frameworks/AccessoryTransportExtension.framework/AccessoryTransportExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22700` | `0x24e2c` | **`+0x272c`** |
| `__DATA.__bss` | `0x3480` | `0x3780` | **`+0x300`** |
| `__TEXT.__const` | `0x22ec` | `0x250c` | **`+0x220`** |
| `__TEXT.__oslogstring` | `0x7e4` | `0x8aa` | **`+0xc6`** |
| `__AUTH.__data` | `0x7b0` | `0x870` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x9df` | `0xa5f` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x538` | `0x5ab` | **`+0x73`** |
| `__TEXT.__constg_swiftt` | `0x1058` | `0x10c8` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0xa78` | `0xae8` | **`+0x70`** |
| `__TEXT.__swift5_assocty` | `0xc0` | `0x120` | **`+0x60`** |
| `__DATA.__data` | `0x878` | `0x8d0` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x82c` | `0x878` | **`+0x4c`** |
| `__AUTH_CONST.__auth_got` | `0x7d8` | `0x820` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x1891` | `0x1851` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0xf30` | `0xef8` | **`-0x38`** |
| `__TEXT.__swift5_proto` | `0x1b4` | `0x1cc` | **`+0x18`** |
| `__TEXT.__cstring` | `0x6d8` | `0x6ed` | **`+0x15`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__const` | `0xf0` | `0x100` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f0` | `0x200` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x98` | `0x9c` | **`+0x4`** |

### Other Changes

```diff

-2700.22.0.0.0
+2700.26.0.0.0

-  Functions: 873
-  Symbols:   470
-  CStrings:  92
+  Functions: 935
+  Symbols:   484
+  CStrings:  96
Symbols:
+ _OBJC_CLASS_$_DAExtensionCapabilityXPCStartConfiguration
+ _OBJC_CLASS_$_NSXPCConnection
+ ___swift_closure_destructor.55Tm
+ ___unnamed_13
+ ___unnamed_18
+ _associated conformance So26DAExtensionCapabilityFlagsVSH27AccessoryTransportExtensionSQ
+ _associated conformance So26DAExtensionCapabilityFlagsVs10SetAlgebraSCSQ
+ _associated conformance So26DAExtensionCapabilityFlagsVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So26DAExtensionCapabilityFlagsVs9OptionSetSCSY
+ _associated conformance So26DAExtensionCapabilityFlagsVs9OptionSetSCs0E7Algebra
+ _free
+ _objc_retain_x9
+ _swift_coroFrameAlloc
+ _swift_dynamicCastObjCClass
+ _symbolic $ss10SetAlgebraP
+ _symbolic $ss25ExpressibleByArrayLiteralP
+ _symbolic $ss9OptionSetP
+ _symbolic So42DAExtensionCapabilityXPCStartConfigurationC
+ _symbolic _____ So26DAExtensionCapabilityFlagsV
+ _symbolic _____ s6UInt64V
+ _type_layout_string So26DAExtensionCapabilityFlagsV
- ___swift_closure_destructor.47Tm
- ___swift_memcpy8_8
- ___unnamed_10
- ___unnamed_5
- _swift_release_n
- _symbolic So32DAExtensionXPCStartConfigurationC
- _type_layout_string 27AccessoryTransportExtension0A17CapabilitySessionC5StateV
CStrings:
+ "### Expected capability start configuration, received %s"
+ "### Failed to cast capability to private accessory feature"
+ "### Failed to create feature session: %@"
+ "### Feature session rejected XPC connection"
+ "### Start already called"
+ "Creating feature session for %s, SessionID '%s'"
+ "Host XPC connection started: PID %d, ID: '%s'"
+ "Start feature session: waiting for feature-session XPC connection"
+ "Start feature session: waiting for host XPC connection"
+ "Start for BundleID '%s', SessionID '%s'"
+ "capabilityFlag"
- "### Conditional downcast to PrivateAccessoryFeature failed"
- "### Feature session already activated"
- "### accept(connection:) failed: %@"
- "Capability XPC connection started: PID %d, ID: '%s'"
- "Creating feature session for %s, RestorationID '%s'"
- "Start for %@"
- "Start for BundleID '%s', RestorationID '%s'"
```
