## MIME

> `/System/Library/PrivateFrameworks/MIME.framework/MIME`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34424` | `0x3454c` | **`+0x128`** |
| `__TEXT.__oslogstring` | `0x1213` | `0x1244` | **`+0x31`** |
| `__TEXT.__const` | `0x7a5` | `0x790` | **`-0x15`** |
| `__TEXT.__gcc_except_tab` | `0x41b4` | `0x41c8` | **`+0x14`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3901.100.1.2.14
+3901.200.34.0.0

-  Functions: 1214
-  Symbols:   2484
-  CStrings:  651
+  Functions: 1216
+  Symbols:   2486
+  CStrings:  652
Symbols:
+ -[MFMessageStore flushAllCaches]
+ _OUTLINED_FUNCTION_4
+ __OBJC_$_CATEGORY_NSData_$_MimeDataEncoding
+ __OBJC_$_CATEGORY_NSString_$_MimeCharsetSupport
+ __OBJC_$_CLASS_METHODS_NSString(MimeCharsetSupport|MimeHeaderEncoding|NSEmailAddressString|MFStringTransform|MFStringUtils)
+ __OBJC_$_INSTANCE_METHODS_MFMimePart(DecodeApplication|DecodeMultipart|MessageSupport|IMAPSupport|DecodingSupport)
+ __OBJC_$_INSTANCE_METHODS_NSData(MimeDataEncoding|NSDataExtensions|NSDataUtils|MFUUDecoder)
+ __OBJC_$_INSTANCE_METHODS_NSString(MimeCharsetSupport|MimeHeaderEncoding|NSEmailAddressString|MFStringTransform|MFStringUtils)
+ _kMaxNumberOfRecursiveSubParts
- -[MFMessageStore _flushAllCaches]
- __OBJC_$_CATEGORY_NSData_$_NSDataExtensions
- __OBJC_$_CATEGORY_NSString_$_NSEmailAddressString
- __OBJC_$_CLASS_METHODS_NSString(NSEmailAddressString|MFStringTransform|MFStringUtils|MimeCharsetSupport|MimeHeaderEncoding)
- __OBJC_$_INSTANCE_METHODS_MFMimePart(MessageSupport|IMAPSupport|DecodingSupport|DecodeApplication|DecodeMultipart)
- __OBJC_$_INSTANCE_METHODS_NSData(NSDataExtensions|MimeDataEncoding|NSDataUtils|MFUUDecoder)
- __OBJC_$_INSTANCE_METHODS_NSString(NSEmailAddressString|MFStringTransform|MFStringUtils|MimeCharsetSupport|MimeHeaderEncoding)
CStrings:
+ "<%@: %p> %@\n"
+ "Reached the maximum MIME part parsing depth: %lu"
- "<%@: %p> %s\n"
```
