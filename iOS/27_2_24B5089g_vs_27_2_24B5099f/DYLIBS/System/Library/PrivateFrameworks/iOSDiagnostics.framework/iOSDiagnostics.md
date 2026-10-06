## iOSDiagnostics

> `/System/Library/PrivateFrameworks/iOSDiagnostics.framework/iOSDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x64c0` | `0x5c9c` | **`-0x824`** |
| `__AUTH_CONST.__objc_const` | `0x2298` | `0x1c68` | **`-0x630`** |
| `__TEXT.__cstring` | `0xdd4` | `0xc0c` | **`-0x1c8`** |
| `__TEXT.__objc_methlist` | `0xc4c` | `0xa8c` | **`-0x1c0`** |
| `__DATA_CONST.__objc_selrefs` | `0x878` | `0x778` | **`-0x100`** |
| `__TEXT.__oslogstring` | `0x65c` | `0x568` | **`-0xf4`** |
| `__DATA.__data` | `0x5a0` | `0x4e0` | **`-0xc0`** |
| `__AUTH.__objc_data` | `0x370` | `0x2d0` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x680` | `0x5e0` | **`-0xa0`** |
| `__AUTH_CONST.__objc_dictobj` | `0x28` | `—` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x170` | `0x148` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x260` | `0x240` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x3c8` | `0x3b8` | **`-0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x18` | `0x8` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x58` | `0x48` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x78` | `0x68` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x90` | `0x84` | **`-0xc`** |

### Other Changes

```diff

-1374.40.40.0.0
+1374.40.54.0.0

-  Functions: 218
-  Symbols:   547
-  CStrings:  114
+  Functions: 201
+  Symbols:   501
+  CStrings:  101
Symbols:
- -[DAAccessorySceneDelegate .cxx_destruct]
- -[DAAccessorySceneDelegate hostingController]
- -[DAAccessorySceneDelegate scene:willConnectToSession:options:]
- -[DAAccessorySceneDelegate setHostingController:]
- -[DAAccessorySceneDelegate setWindow:]
- -[DAAccessorySceneDelegate window]
- -[DADiagnosticsCompanionSceneSpecification userActivity]
- -[DADiagnosticsRemoteViewController accessoryRegistration]
- -[DADiagnosticsRemoteViewController setAccessoryRegistration:]
- -[DADiagnosticsRemoteViewController viewServiceDidDismissAccessoryContent]
- -[DADiagnosticsRemoteViewController viewServiceDidRequestAccessoryContent]
- _OBJC_CLASS_$_DAAccessorySceneDelegate
- _OBJC_CLASS_$_DADiagnosticsCompanionSceneSpecification
- _OBJC_CLASS_$_NSConstantDictionary
- _OBJC_CLASS_$_UIResponder
- _OBJC_CLASS_$_UISceneAccessory
- _OBJC_CLASS_$_UISceneConfiguration
- _OBJC_CLASS_$_UIWindow
- _OBJC_IVAR_$_DAAccessorySceneDelegate._hostingController
- _OBJC_IVAR_$_DAAccessorySceneDelegate._window
- _OBJC_IVAR_$_DADiagnosticsRemoteViewController._accessoryRegistration
- _OBJC_METACLASS_$_DAAccessorySceneDelegate
- _OBJC_METACLASS_$_DADiagnosticsCompanionSceneSpecification
- _OBJC_METACLASS_$_UIResponder
- __OBJC_$_INSTANCE_METHODS_DAAccessorySceneDelegate
- __OBJC_$_INSTANCE_METHODS_DADiagnosticsCompanionSceneSpecification
- __OBJC_$_INSTANCE_VARIABLES_DAAccessorySceneDelegate
- __OBJC_$_PROP_LIST_DAAccessorySceneDelegate
- __OBJC_$_PROP_LIST_UIWindowSceneDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UISceneDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UIWindowSceneDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_UISceneDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_UIWindowSceneDelegate
- __OBJC_$_PROTOCOL_REFS_UISceneDelegate
- __OBJC_$_PROTOCOL_REFS_UIWindowSceneDelegate
- __OBJC_CLASS_PROTOCOLS_$_DAAccessorySceneDelegate
- __OBJC_CLASS_RO_$_DAAccessorySceneDelegate
- __OBJC_CLASS_RO_$_DADiagnosticsCompanionSceneSpecification
- __OBJC_LABEL_PROTOCOL_$_UISceneDelegate
- __OBJC_LABEL_PROTOCOL_$_UIWindowSceneDelegate
- __OBJC_METACLASS_RO_$_DAAccessorySceneDelegate
- __OBJC_METACLASS_RO_$_DADiagnosticsCompanionSceneSpecification
- __OBJC_PROTOCOL_$_UISceneDelegate
- __OBJC_PROTOCOL_$_UIWindowSceneDelegate
- ___74-[DADiagnosticsRemoteViewController viewServiceDidDismissAccessoryContent]_block_invoke
- ___74-[DADiagnosticsRemoteViewController viewServiceDidRequestAccessoryContent]_block_invoke
CStrings:
+ "#"
- "$"
- "%s Failed to register accessory scene; the accessory surface will not appear"
- "%s Nil hosting controller; cannot host accessory content"
- "%s Nil process identity; cannot host accessory content"
- "-[DAAccessorySceneDelegate scene:willConnectToSession:options:]"
- "-[DADiagnosticsRemoteViewController viewServiceDidDismissAccessoryContent]"
- "-[DADiagnosticsRemoteViewController viewServiceDidRequestAccessoryContent]"
- "-[DADiagnosticsRemoteViewController viewServiceDidRequestAccessoryContent]_block_invoke"
- "Accessory scene connected; hosting Diagnostics content"
- "ServiceToHostActionTypeDidDismissAccessoryContent"
- "ServiceToHostActionTypeDidRequestAccessoryContent"
- "com.apple.diagnostics.rvc.companion"
- "companion"
- "surface"
```
