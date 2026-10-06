## safarifetcherd

> `/usr/libexec/safarifetcherd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x96b4` | `0x933c` | **`-0x378`** |
| `__TEXT.__unwind_info` | `0x498` | `0x5c0` | **`+0x128`** |
| `__TEXT.__objc_methname` | `0x5445` | `0x54b0` | **`+0x6b`** |
| `__TEXT.__objc_methtype` | `0x24e4` | `0x251d` | **`+0x39`** |
| `__DATA.__objc_const` | `0x1628` | `0x1630` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1188` | `0x1190` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x138c` | `0x1394` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-7625.1.29.10.28
+7625.1.29.10.29

-  CStrings:  1021
+  CStrings:  1023
CStrings:
+ "_webView:requestWebAuthenticationConditionalMediationRegistrationForUser:relatedOrigins:completionHandler:"
+ "v48@0:8@\"WKWebView\"16@\"NSString\"24@\"NSArray\"32@?<v@?B>40"
```
