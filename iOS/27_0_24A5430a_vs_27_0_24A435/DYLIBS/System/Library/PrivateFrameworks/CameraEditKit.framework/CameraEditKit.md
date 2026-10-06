## CameraEditKit

> `/System/Library/PrivateFrameworks/CameraEditKit.framework/CameraEditKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x422d8` | `0x432c4` | **`+0xfec`** |
| `__AUTH_CONST.__cfstring` | `0x1760` | `0x1980` | **`+0x220`** |
| `__TEXT.__cstring` | `0x143e` | `0x162e` | **`+0x1f0`** |
| `__AUTH_CONST.__objc_const` | `0x9260` | `0x93c8` | **`+0x168`** |
| `__TEXT.__objc_methlist` | `0x5704` | `0x5844` | **`+0x140`** |
| `__DATA_CONST.__objc_selrefs` | `0x34a0` | `0x3530` | **`+0x90`** |
| `__AUTH_CONST.__objc_intobj` | `0x588` | `0x600` | **`+0x78`** |
| `__DATA_CONST.__objc_arraydata` | `0x2f8` | `0x358` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x13c8` | `0x1420` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x14a0` | `0x14f0` | **`+0x50`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xf0` | `0x138` | **`+0x48`** |
| `__DATA_CONST.__const` | `0xd60` | `0xda8` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x728` | `0x768` | **`+0x40`** |
| `__DATA.__bss` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x528` | `0x548` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x708` | `0x714` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x980` | `0x988` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x138` | `0x140` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 2059
-  Symbols:   3387
-  CStrings:  267
+  Functions: 2093
+  Symbols:   3439
+  CStrings:  284
Symbols:
+ +[CEKTextureStyle _cmiPresetNameForPreset:]
+ +[CEKTextureStyle _defaultValuesForPreset:intensity:grain:]
+ +[CEKTextureStyle _indexForPresetString:]
+ +[CEKTextureStyle canCustomizeGrainForPreset:]
+ +[CEKTextureStyle canCustomizeIntensityForPreset:]
+ +[CEKTextureStyle defaultStyles]
+ +[CEKTextureStyle identityStyle]
+ +[CEKTextureStyle persistenceStringForPreset:]
+ +[CEKTextureStyle presetFromPersistenceString:success:]
+ +[CEKTextureStyle styleWithDictionary:referenceStyle:error:]
+ -[CEKTextureStyle _analyticsDictionary]
+ -[CEKTextureStyle analyticsDictionaryForCapture]
+ -[CEKTextureStyle analyticsDictionaryForPreferences]
+ -[CEKTextureStyle description]
+ -[CEKTextureStyle dictionaryRepresentationUsingReferenceStyle:]
+ -[CEKTextureStyle grain]
+ -[CEKTextureStyle hash]
+ -[CEKTextureStyle initWithPreset:]
+ -[CEKTextureStyle initWithPreset:intensity:grain:]
+ -[CEKTextureStyle intensity]
+ -[CEKTextureStyle isCustomizable]
+ -[CEKTextureStyle isCustomized]
+ -[CEKTextureStyle isEqual:]
+ -[CEKTextureStyle isEqualToTextureStyle:]
+ -[CEKTextureStyle preset]
+ _AVGQGYSWMQKMTMQOUYQ2AKUCKEN6AA
+ _AVGestaltGetIntegerAnswerWithDefault
+ _CEKDebugStringForTextureStylePreset
+ _CEKTextureStyleAllPresets
+ _CEKTextureStyleCameraAvailablePresets
+ _CEKTextureStyleSystemStylePresets
+ _CMITextureStylePresetNameFilmic
+ _CMITextureStylePresetNameGlowy
+ _CMITextureStylePresetNameSoft
+ _CMITextureStylePresetNameStandard
+ _CMITextureStylePresetNameStudio
+ _OBJC_CLASS_$_CEKTextureStyle
+ _OBJC_CLASS_$_CMITextureStyleTuningLookup
+ _OBJC_IVAR_$_CEKTextureStyle._grain
+ _OBJC_IVAR_$_CEKTextureStyle._intensity
+ _OBJC_IVAR_$_CEKTextureStyle._preset
+ _OBJC_METACLASS_$_CEKTextureStyle
+ __OBJC_$_CLASS_METHODS_CEKTextureStyle
+ __OBJC_$_CLASS_PROP_LIST_CEKTextureStyle
+ __OBJC_$_INSTANCE_METHODS_CEKTextureStyle
+ __OBJC_$_INSTANCE_VARIABLES_CEKTextureStyle
+ __OBJC_$_PROP_LIST_CEKTextureStyle
+ __OBJC_CLASS_RO_$_CEKTextureStyle
+ __OBJC_METACLASS_RO_$_CEKTextureStyle
+ ___32+[CEKTextureStyle identityStyle]_block_invoke
+ ___41+[CEKTextureStyle _indexForPresetString:]_block_invoke
+ ___41+[CEKTextureStyle _indexForPresetString:]_block_invoke_2
CStrings:
+ "Analog"
+ "CEKTextureStyleErrorDomain"
+ "Glowy"
+ "Grain"
+ "Intensity"
+ "People"
+ "Preset"
+ "Scene"
+ "TextureStyle(Preset:%@)"
+ "TextureStyle(Preset:%@, Intensity:%.2f, Grain:%.2f)"
+ "TextureStyleCustomized"
+ "TextureStyleGrain"
+ "TextureStyleIntensity"
+ "TextureStylePreset"
+ "Unexpected CEKTextureStyle dictionary structure, incorrect type for values of known keys"
+ "Unexpected CEKTextureStyle dictionary structure, incorrect value for PresetKey: no preset match found"
+ "Unexpected CEKTextureStyle dictionary structure, missing required keys"
```
