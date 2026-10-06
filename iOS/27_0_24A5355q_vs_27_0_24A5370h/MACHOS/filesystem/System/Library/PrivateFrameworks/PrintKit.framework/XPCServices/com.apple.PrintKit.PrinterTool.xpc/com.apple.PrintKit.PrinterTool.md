## com.apple.PrintKit.PrinterTool

> `/System/Library/PrivateFrameworks/PrintKit.framework/XPCServices/com.apple.PrintKit.PrinterTool.xpc/com.apple.PrintKit.PrinterTool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c5b4` | `0x5bff4` | **`-0x5c0`** |
| `__TEXT.__gcc_except_tab` | `0xaadc` | `0xaa08` | **`-0xd4`** |
| `__DATA_CONST.__cfstring` | `0xed40` | `0xeca0` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x954d` | `0x94be` | **`-0x8f`** |
| `__TEXT.__objc_methlist` | `0x2ec8` | `0x2e48` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x2e88` | `0x2e40` | **`-0x48`** |
| `__TEXT.__objc_methname` | `0x6a8a` | `0x6a4a` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0x2079` | `0x2043` | **`-0x36`** |
| `__DATA.__objc_const` | `0x5820` | `0x57f8` | **`-0x28`** |
| `__DATA_CONST.__const` | `0xed80` | `0xed58` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x590` | `0x5b8` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x42fd` | `0x4322` | **`+0x25`** |
| `__DATA.__objc_selrefs` | `0x1e20` | `0x1e08` | **`-0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-324.0.0.0.0
+326.0.0.0.0

-  Functions: 1636
-  Symbols:   934
-  CStrings:  4139
+  Functions: 1628
+  Symbols:   939
+  CStrings:  4131
Symbols:
+ _PKiCloudCommandKey
+ _PKiCloudPrinterInfoKey
+ _PKiCloudPrinterNewInfo
+ _PKiCloudPrinterNewInfoKey
+ _PKiCloudPrintersKey
CStrings:
+ "iCloudPrintingCommand:"
+ "iCloudPrintingCommand:withCompletionHandler:"
+ "logiCloudPrintersReply"
+ "removePrinterFromiCloudWithInfo"
+ "v32@0:8@\"NSDictionary\"16@?<v@?@\"NSArray\">24"
- " customLocation:'%@'"
- " customName:'%@'"
- " network:'%@'"
- "************************** log_iCloudPrinters numPrinters:%ld, Network '%@'"
- "getiCloudPrintersReply:"
- "logiCloudPrinters"
- "logiCloudPrintersReply:"
- "name:%@ %@%@%@"
- "setiCloudPrinters:"
- "updateiCloudPrinterInfo:withNewInfo:forInfoKey:"
- "v24@0:8@\"NSArray\"16"
- "v24@0:8@?<v@?@\"NSArray\">16"
- "v40@0:8@\"NSDictionary\"16@\"NSObject\"24@\"NSString\"32"
```
