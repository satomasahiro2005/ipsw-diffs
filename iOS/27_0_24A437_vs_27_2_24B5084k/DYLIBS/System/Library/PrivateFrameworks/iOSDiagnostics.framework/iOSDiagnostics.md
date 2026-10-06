## iOSDiagnostics

> `/System/Library/PrivateFrameworks/iOSDiagnostics.framework/iOSDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58d8` | `0x64c0` | **`+0xbe8`** |
| `__AUTH_CONST.__objc_const` | `0x1c08` | `0x2298` | **`+0x690`** |
| `__TEXT.__cstring` | `0xb11` | `0xdd4` | **`+0x2c3`** |
| `__TEXT.__objc_methlist` | `0xa44` | `0xc4c` | **`+0x208`** |
| `__TEXT.__oslogstring` | `0x4f5` | `0x65c` | **`+0x167`** |
| `__DATA_CONST.__objc_selrefs` | `0x740` | `0x878` | **`+0x138`** |
| `__AUTH_CONST.__cfstring` | `0x5a0` | `0x680` | **`+0xe0`** |
| `__DATA.__data` | `0x4e0` | `0x5a0` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x2d0` | `0x370` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x228` | `0x260` | **`+0x38`** |
| `__AUTH_CONST.__objc_dictobj` | `—` | `0x28` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x148` | `0x170` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x3a8` | `0x3c8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x80` | `0x90` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x8` | `0x18` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x58` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x68` | `0x78` | **`+0x10`** |

### Other Changes

```diff

-1374.2.2.0.0
+1374.40.35.0.0

-  Functions: 195
-  Symbols:   494
-  CStrings:  95
+  Functions: 218
+  Symbols:   547
+  CStrings:  114
Symbols:
+ -[DAAccessorySceneDelegate .cxx_destruct]
+ -[DAAccessorySceneDelegate hostingController]
+ -[DAAccessorySceneDelegate scene:willConnectToSession:options:]
+ -[DAAccessorySceneDelegate setHostingController:]
+ -[DAAccessorySceneDelegate setWindow:]
+ -[DAAccessorySceneDelegate window]
+ -[DADiagnosticsCompanionSceneSpecification userActivity]
+ -[DADiagnosticsRemoteViewController accessoryRegistration]
+ -[DADiagnosticsRemoteViewController serviceSupportedInterfaceOrientations]
+ -[DADiagnosticsRemoteViewController setAccessoryRegistration:]
+ -[DADiagnosticsRemoteViewController setServiceSupportedInterfaceOrientations:]
+ -[DADiagnosticsRemoteViewController supportedInterfaceOrientations]
+ -[DADiagnosticsRemoteViewController viewServiceDidDismissAccessoryContent]
+ -[DADiagnosticsRemoteViewController viewServiceDidRequestAccessoryContent]
+ -[DADiagnosticsRemoteViewController viewServiceDidSetSupportedInterfaceOrientations:]
+ _OBJC_CLASS_$_DAAccessorySceneDelegate
+ _OBJC_CLASS_$_DADiagnosticsCompanionSceneSpecification
+ _OBJC_CLASS_$_NSConstantDictionary
+ _OBJC_CLASS_$_UIResponder
+ _OBJC_CLASS_$_UISceneAccessory
+ _OBJC_CLASS_$_UISceneConfiguration
+ _OBJC_CLASS_$_UIWindow
+ _OBJC_IVAR_$_DAAccessorySceneDelegate._hostingController
+ _OBJC_IVAR_$_DAAccessorySceneDelegate._window
+ _OBJC_IVAR_$_DADiagnosticsRemoteViewController._accessoryRegistration
+ _OBJC_IVAR_$_DADiagnosticsRemoteViewController._serviceSupportedInterfaceOrientations
+ _OBJC_METACLASS_$_DAAccessorySceneDelegate
+ _OBJC_METACLASS_$_DADiagnosticsCompanionSceneSpecification
+ _OBJC_METACLASS_$_UIResponder
+ __OBJC_$_INSTANCE_METHODS_DAAccessorySceneDelegate
+ __OBJC_$_INSTANCE_METHODS_DADiagnosticsCompanionSceneSpecification
+ __OBJC_$_INSTANCE_VARIABLES_DAAccessorySceneDelegate
+ __OBJC_$_PROP_LIST_DAAccessorySceneDelegate
+ __OBJC_$_PROP_LIST_UIWindowSceneDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_DADiagnosticsRemoteViewControllerInterface
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UISceneDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UIWindowSceneDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UISceneDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UIWindowSceneDelegate
+ __OBJC_$_PROTOCOL_REFS_UISceneDelegate
+ __OBJC_$_PROTOCOL_REFS_UIWindowSceneDelegate
+ __OBJC_CLASS_PROTOCOLS_$_DAAccessorySceneDelegate
+ __OBJC_CLASS_RO_$_DAAccessorySceneDelegate
+ __OBJC_CLASS_RO_$_DADiagnosticsCompanionSceneSpecification
+ __OBJC_LABEL_PROTOCOL_$_UISceneDelegate
+ __OBJC_LABEL_PROTOCOL_$_UIWindowSceneDelegate
+ __OBJC_METACLASS_RO_$_DAAccessorySceneDelegate
+ __OBJC_METACLASS_RO_$_DADiagnosticsCompanionSceneSpecification
+ __OBJC_PROTOCOL_$_UISceneDelegate
+ __OBJC_PROTOCOL_$_UIWindowSceneDelegate
+ ___74-[DADiagnosticsRemoteViewController viewServiceDidDismissAccessoryContent]_block_invoke
+ ___74-[DADiagnosticsRemoteViewController viewServiceDidRequestAccessoryContent]_block_invoke
+ ___85-[DADiagnosticsRemoteViewController viewServiceDidSetSupportedInterfaceOrientations:]_block_invoke
CStrings:
+ "$"
+ "%s Failed to register accessory scene; the accessory surface will not appear"
+ "%s Nil hosting controller; cannot host accessory content"
+ "%s Nil process identity; cannot host accessory content"
+ "%s View service requires mask %lu but host supports %lu; keeping the host's"
+ "%s supportedInterfaceOrientations: %lu"
+ "-[DAAccessorySceneDelegate scene:willConnectToSession:options:]"
+ "-[DADiagnosticsRemoteViewController supportedInterfaceOrientations]"
+ "-[DADiagnosticsRemoteViewController viewServiceDidDismissAccessoryContent]"
+ "-[DADiagnosticsRemoteViewController viewServiceDidRequestAccessoryContent]"
+ "-[DADiagnosticsRemoteViewController viewServiceDidRequestAccessoryContent]_block_invoke"
+ "-[DADiagnosticsRemoteViewController viewServiceDidSetSupportedInterfaceOrientations:]"
+ "Accessory scene connected; hosting Diagnostics content"
+ "ServiceToHostActionType(unknown %ld)"
+ "ServiceToHostActionTypeDidDismissAccessoryContent"
+ "ServiceToHostActionTypeDidRequestAccessoryContent"
+ "ServiceToHostActionTypeDidSetSupportedInterfaceOrientations"
+ "com.apple.diagnostics.rvc.companion"
+ "companion"
+ "surface"
- "#"
```
