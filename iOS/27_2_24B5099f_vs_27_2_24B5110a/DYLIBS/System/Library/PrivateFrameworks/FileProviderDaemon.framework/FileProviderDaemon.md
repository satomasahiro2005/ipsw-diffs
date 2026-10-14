## FileProviderDaemon

> `/System/Library/PrivateFrameworks/FileProviderDaemon.framework/FileProviderDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaa0f40` | `0xaa10e8` | **`+0x1a8`** |
| `__AUTH_CONST.__objc_const` | `0x28320` | `0x28370` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x7860` | `0x7880` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x4ccc8` | `0x4cce8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x500b5` | `0x500d5` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x21972` | `0x21992` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x6438` | `0x6450` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x9b54` | `0x9b6c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x16d68` | `0x16d78` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xbf8` | `0xc00` | **`+0x8`** |

### Other Changes

```diff

-4838.40.130.0.2
+4838.42.2.0.0

-  Functions: 31851
-  Symbols:   12742
+  Functions: 31853
+  Symbols:   12747
Symbols:
+ -[FPDProviderDescriptor owningApplicationIsInstallationHeld]
+ -[FPDProviderDescriptor setOwningApplicationIsInstallationHeld:]
+ _OBJC_IVAR_$_FPDExtensionManager._installationHeldProviderUUIDs
+ _OBJC_IVAR_$_FPDProviderDescriptor._owningApplicationIsInstallationHeld
+ ___49-[FPDExtensionManager synchronousProviderUpdate:]_block_invoke_2
Functions:
~ -[FPDProviderDescriptor initWithExtensionRecord:] : 6552 -> 6604
~ -[FPDDomain disconnectionState] : 448 -> 500
~ -[FPDProviderDescriptor initWithCoder:] : 2132 -> 2152
~ -[FPDProviderDescriptor encodeWithCoder:] : 908 -> 928
~ -[FPDProviderDescriptor isEqual:] : 320 -> 344
- -[FPDProviderDescriptor setPurposeIdentifier:]
+ -[FPDProviderDescriptor purposeIdentifier]
+ -[FPDProviderDescriptor setPersonaIdentifier:]
+ -[FPDProviderDescriptor setManagedPersona:]
~ -[FPDProvider providerDomainForDomain:] : 1464 -> 1484
~ ___49-[FPDExtensionManager synchronousProviderUpdate:]_block_invoke : 572 -> 724
+ ___49-[FPDExtensionManager synchronousProviderUpdate:]_block_invoke_2
~ -[FPDExtensionManager .cxx_destruct] : 208 -> 220
- ___49-[FPDExtensionManager synchronousProviderUpdate:]_block_invoke.cold.2
CStrings:
+ "[DEBUG] Updating extensions: %@ -> %@ (held: %@ -> %@)"
+ "_owningApplicationIsInstallationHeld"
+ "\xe1"
- "\r"
- "[DEBUG] Updating extensions: %@ -> %@"
- "\xd1"
```
