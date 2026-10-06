## BrightnessControl

> `/System/Library/PrivateFrameworks/BrightnessControl.framework/BrightnessControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b8fc` | `0x1bce4` | **`+0x3e8`** |
| `__AUTH_CONST.__objc_intobj` | `0xc0` | `0x240` | **`+0x180`** |
| `__DATA_CONST.__objc_arraydata` | `0x2e0` | `0x400` | **`+0x120`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x10` | `0x100` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x2c80` | `0x2ce0` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x3688` | `0x36e0` | **`+0x58`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x108` | `0x150` | **`+0x48`** |
| `__AUTH_CONST.__objc_floatobj` | `0x120` | `0x160` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x918` | `0x940` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x4c0` | `0x4e8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x13d4` | `0x13fc` | **`+0x28`** |
| `__TEXT.__const` | `0x4020` | `0x4038` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x7b8` | `0x7d0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x2077` | `0x2087` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x558` | `0x560` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-2300.40.39.0.0
+2300.40.47.0.4

-  Functions: 664
-  Symbols:   1162
-  CStrings:  606
+  Functions: 668
+  Symbols:   1172
+  CStrings:  608
Symbols:
+ -[NSArray(PrimitiveDataProvider) copyFloatVector]
+ -[NSSet(PrettyDescription) prettyDescription]
+ GCC_except_table150
+ GCC_except_table153
+ GCC_except_table154
+ GCC_except_table158
+ GCC_except_table159
+ GCC_except_table162
+ GCC_except_table163
+ GCC_except_table167
+ GCC_except_table168
+ GCC_except_table177
+ GCC_except_table178
+ GCC_except_table182
+ GCC_except_table183
+ GCC_except_table20
+ GCC_except_table69
+ GCC_except_table72
+ GCC_except_table77
+ _MGIsDeviceOneOfType
+ _OBJC_CLASS_$_NSSet
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSSet_$_PrettyDescription
+ __OBJC_$_CATEGORY_NSSet_$_PrettyDescription
+ __OBJC_$_PROP_LIST_NSSet_$_PrettyDescription
+ _device_specific_capabilities_patching
+ _parseSemanticAmbientLuxLevels
- GCC_except_table138
- GCC_except_table140
- GCC_except_table152
- GCC_except_table156
- GCC_except_table157
- GCC_except_table160
- GCC_except_table161
- GCC_except_table165
- GCC_except_table166
- GCC_except_table174
- GCC_except_table175
- GCC_except_table180
- GCC_except_table181
- GCC_except_table65
- GCC_except_table70
- GCC_except_table73
CStrings:
+ "[%@]"
+ "semantic-lux-levels"
```
