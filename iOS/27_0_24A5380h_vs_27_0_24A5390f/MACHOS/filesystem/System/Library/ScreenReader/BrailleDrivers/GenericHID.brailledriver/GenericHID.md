## GenericHID

> `/System/Library/ScreenReader/BrailleDrivers/GenericHID.brailledriver/GenericHID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47a4` | `0x4ee8` | **`+0x744`** |
| `__TEXT.__objc_methname` | `0xc49` | `0xfd7` | **`+0x38e`** |
| `__TEXT.__objc_stubs` | `0xbe0` | `0xec0` | **`+0x2e0`** |
| `__DATA_CONST.__objc_intobj` | `0x408` | `0x288` | **`-0x180`** |
| `__DATA.__objc_const` | `0x890` | `0x9d8` | **`+0x148`** |
| `__DATA.__objc_selrefs` | `0x458` | `0x570` | **`+0x118`** |
| `__TEXT.__objc_methlist` | `0x59c` | `0x6a4` | **`+0x108`** |
| `__DATA_CONST.__objc_arraydata` | `0x270` | `0x1c8` | **`-0xa8`** |
| `__TEXT.__oslogstring` | `0x4f7` | `0x571` | **`+0x7a`** |
| `__DATA_CONST.__const` | `0x110` | `0xa8` | **`-0x68`** |
| `__DATA.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x2c8` | `0x310` | **`+0x48`** |
| `__DATA_CONST.__objc_arrayobj` | `0x108` | `0xd8` | **`-0x30`** |
| `__TEXT.__auth_stubs` | `0x480` | `0x4b0` | **`+0x30`** |
| `__DATA_CONST.__objc_dictobj` | `0xc8` | `0xf0` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x8b` | `0xa6` | **`+0x1b`** |
| `__DATA_CONST.__auth_got` | `0x248` | `0x260` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x100` | `0x118` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x78` | `0x8c` | **`+0x14`** |
| `__TEXT.__cstring` | `0x202` | `0x1ef` | **`-0x13`** |
| `__DATA.__bss` | `0x10` | `—` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x90` | `0x98` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__const` | `0x40` | `0x48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-460.0.0.0.0
+462.0.0.0.0

-  Functions: 70
-  Symbols:   99
-  CStrings:  284
+  Functions: 89
+  Symbols:   105
+  CStrings:  331
Symbols:
+ _IOHIDDeviceSetReport
+ _IOHIDElementGetReportID
+ _OBJC_CLASS_$_NSMutableData
+ _OBJC_CLASS_$_SCRO2DBrailleCanvas
+ _OBJC_CLASS_$_SCRO2DBrailleCanvasDescriptor
+ _OBJC_METACLASS_$_SCRO2DBrailleCanvas
+ _objc_alloc
+ _objc_retainAutorelease
+ _objc_retainAutoreleaseReturnValue
- _OBJC_CLASS_$_NSMutableIndexSet
- _dispatch_once
- _objc_retain_x21
CStrings:
+ "@\"SCRO2DBrailleCanvas\""
+ "@32@0:8Q16Q24"
+ "C"
+ "Failed to send tactile graphics report (result: 0x%x)"
+ "SCROMonarch2DBrailleCanvas"
+ "TI,N,V_groupOrdinal"
+ "Tactile graphics canvas ready: %ld x %ld pins, output reportID 0x%x"
+ "^{__IOHIDElement=}16@0:8"
+ "_assignGroupOrdinalsToControls:"
+ "_brailleCellsPerRow"
+ "_canvas"
+ "_copyTactileGraphicsPinOutputElement"
+ "_groupOrdinal"
+ "_setupTactileGraphicsCanvas"
+ "_tactileGraphicsHeight"
+ "_tactileGraphicsReportID"
+ "_tactileGraphicsWidth"
+ "appendBytes:length:"
+ "appendData:"
+ "brailleCellData"
+ "bytes"
+ "containsObject:"
+ "d16@0:8"
+ "dataWithCapacity:"
+ "detentCount"
+ "groupOrdinal"
+ "hasConsistentHorizontalPinSpacing"
+ "hasConsistentVerticalPinSpacing"
+ "horizontalPinSpacing"
+ "initWithCanvasDescriptor:"
+ "initWithWidth:height:"
+ "interCellHorizontalSpacing"
+ "interCellVerticalSpacing"
+ "modelIdentifierForPlist"
+ "pinHeightStyle"
+ "setCellHeight:"
+ "setCellWidth:"
+ "setDetentCount:"
+ "setGroupOrdinal:"
+ "setHasConsistentHorizontalPinSpacing:"
+ "setHasConsistentVerticalPinSpacing:"
+ "setHeight:"
+ "setHorizontalPinSpacing:"
+ "setInterCellHorizontalSpacing:"
+ "setInterCellVerticalSpacing:"
+ "setPinHeightStyle:"
+ "setSkipPinBetweenCellsHorizontally:"
+ "setSkipPinBetweenCellsVertically:"
+ "setVerticalPinSpacing:"
+ "setWidth:"
+ "skipPinBetweenCellsHorizontally"
+ "skipPinBetweenCellsVertically"
+ "supportsBrailleText"
+ "verticalPinSpacing"
- "enumerateIndexesUsingBlock:"
- "indexSetWithIndexesInRange:"
- "removeIndex:"
- "removeIndexesInRange:"
- "removeObjectsInArray:"
- "v24@?0Q8^B16"
- "v8@?0"
```
