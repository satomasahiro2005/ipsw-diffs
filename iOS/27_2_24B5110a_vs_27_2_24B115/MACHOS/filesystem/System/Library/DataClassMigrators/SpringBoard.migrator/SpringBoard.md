## SpringBoard

> `/System/Library/DataClassMigrators/SpringBoard.migrator/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe4cc` | `0xebbc` | **`+0x6f0`** |
| `__TEXT.__objc_stubs` | `0x19a0` | `0x1be0` | **`+0x240`** |
| `__TEXT.__objc_methname` | `0x19e1` | `0x1b92` | **`+0x1b1`** |
| `__TEXT.__oslogstring` | `0x139e` | `0x153e` | **`+0x1a0`** |
| `__DATA.__objc_const` | `0xd28` | `0xdb8` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0x7b8` | `0x848` | **`+0x90`** |
| `__DATA.__objc_data` | `0x280` | `0x2d0` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x5e0` | `0x610` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x64c` | `0x67c` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x11a` | `0x145` | **`+0x2b`** |
| `__DATA_CONST.__cfstring` | `0xf20` | `0xf40` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x228` | `0x248` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x270` | `0x290` | **`+0x20`** |
| `__TEXT.__cstring` | `0x18bb` | `0x18d9` | **`+0x1e`** |
| `__DATA_CONST.__auth_got` | `0x300` | `0x318` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-  Functions: 642
-  Symbols:   379
-  CStrings:  692
+  Functions: 647
+  Symbols:   387
+  CStrings:  717
Symbols:
+ _CATransform3DMakeTranslation
+ _CFPreferencesGetAppBooleanValue
+ _OBJC_CLASS_$_FBSDeviceEmulationConfiguration
+ _OBJC_CLASS_$_FBSDisplayConfigurationBuilder
+ _OBJC_CLASS_$_NSValue
+ _OBJC_CLASS_$_SBScreenEdgeCompensationDisplayTransformer
+ _OBJC_METACLASS_$_SBScreenEdgeCompensationDisplayTransformer
+ _SBLogDisplayTransforming
CStrings:
+ "%{public}@: screen edge compensation transform built: %{BOOL}u"
+ "Applying screen edge compensation: D76 main display size matched; rewriting bounds from %{public}@ to %{public}@"
+ "EdgeSwipeBandExpansionEnabled"
+ "SBScreenEdgeCompensationDisplayTransformer"
+ "Skipping screen edge compensation: isMainD76Display=%{BOOL}u"
+ "Unable to build screen edge compensated display configuration: %{public}@ from configuration: %{public}@"
+ "Unable to create redacted display configuration: %@ from configuration:%@"
+ "_copyWithOverrideSize:"
+ "_fbsDisplayConfiguration"
+ "_fbsDisplayIdentity"
+ "_nativeBounds"
+ "buildConfigurationWithError:"
+ "emulatedDeviceBounds"
+ "hasEmulatedDeviceBounds"
+ "initWithConfiguration:"
+ "isEmulatedDevice"
+ "isMainRootDisplay"
+ "isScreenEdgeCompensationEnabled"
+ "pixelSize"
+ "scale"
+ "sceneTransformForWindowScene:"
+ "setCurrentMode:preferredMode:otherModes:"
+ "setPixelSize:nativeBounds:bounds:"
+ "transformedConfigurationForConfiguration:"
+ "valueWithCATransform3D:"
```
