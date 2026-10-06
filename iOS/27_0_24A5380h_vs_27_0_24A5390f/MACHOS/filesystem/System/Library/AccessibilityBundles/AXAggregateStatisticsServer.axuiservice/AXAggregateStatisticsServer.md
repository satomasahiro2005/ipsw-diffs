## AXAggregateStatisticsServer

> `/System/Library/AccessibilityBundles/AXAggregateStatisticsServer.axuiservice/AXAggregateStatisticsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3844` | `0x3b3f` | **`+0x2fb`** |
| `__TEXT.__text` | `0x119d0` | `0x11cbc` | **`+0x2ec`** |
| `__DATA_CONST.__cfstring` | `0x3560` | `0x3740` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0x1468` | `0x1488` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x8e0` | `0x8f0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x25c` | `0x268` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x480` | `0x488` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

-  Functions: 255
-  Symbols:   222
-  CStrings:  778
+  Functions: 256
+  Symbols:   223
+  CStrings:  793
Symbols:
+ __AXSReduceHighlightingEffectsEnabled
Functions:
~ sub_7280 : 6872 -> 7436
+ sub_a4a0
CStrings:
+ "com.apple.accessibility.reduce.bright.effects.enabled"
+ "com.apple.braille.driver.dot.pad"
+ "com.apple.scrod.braille.driver.alva.6.series"
+ "com.apple.scrod.braille.driver.baum"
+ "com.apple.scrod.braille.driver.eurobraille"
+ "com.apple.scrod.braille.driver.freedomscientific"
+ "com.apple.scrod.braille.driver.generic.hid"
+ "com.apple.scrod.braille.driver.handytech"
+ "com.apple.scrod.braille.driver.hims"
+ "com.apple.scrod.braille.driver.hims.braillesense"
+ "com.apple.scrod.braille.driver.humanware.braillenote.apex"
+ "com.apple.scrod.braille.driver.humanware.brailliant.2"
+ "com.apple.scrod.braille.driver.kgs"
+ "com.apple.scrod.braille.driver.mdv"
+ "com.apple.scrod.braille.driver.ninepointsystems"
+ "com.apple.scrod.braille.driver.nippon.telesoft.seika"
+ "com.apple.scrod.braille.driver.optelec.easylink"
+ "com.apple.scrod.braille.driver.papenmeier"
- "bt"
- "com.apple.scrod.braille.driver."
- "usb"
```
