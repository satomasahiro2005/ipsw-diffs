## MailSupport

> `/System/Library/PrivateFrameworks/MailSupport.framework/MailSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4c1b` | `0x4ddb` | **`+0x1c0`** |
| `__TEXT.__text` | `0x22c78` | `0x22dd4` | **`+0x15c`** |
| `__AUTH.__objc_data` | `0x120` | `0x170` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x1218` | `0x11c8` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x27e4` | `0x280c` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x49a0` | `0x49c0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x668` | `0x678` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1670` | `0x1678` | **`+0x8`** |

### Other Changes

```diff

-3897.100.8.2.5
+3901.100.1.2.7

-  CStrings:  725
+  CStrings:  726
Symbols:
+ +[MSWritingToolsNodePreservation preserveNodesInWebView:completionHandler:]
+ _OBJC_CLASS_$_MSWritingToolsNodePreservation
+ _OBJC_METACLASS_$_MSWritingToolsNodePreservation
+ __OBJC_$_CLASS_METHODS_MSWritingToolsNodePreservation
+ __OBJC_CLASS_RO_$_MSWritingToolsNodePreservation
+ __OBJC_METACLASS_RO_$_MSWritingToolsNodePreservation
+ ___75+[MSWritingToolsNodePreservation preserveNodesInWebView:completionHandler:]_block_invoke
- +[MSWritingToolsSignaturePreservation preserveSignatureNodeInWebView:completionHandler:]
- _OBJC_CLASS_$_MSWritingToolsSignaturePreservation
- _OBJC_METACLASS_$_MSWritingToolsSignaturePreservation
- __OBJC_$_CLASS_METHODS_MSWritingToolsSignaturePreservation
- __OBJC_CLASS_RO_$_MSWritingToolsSignaturePreservation
- __OBJC_METACLASS_RO_$_MSWritingToolsSignaturePreservation
- ___88+[MSWritingToolsSignaturePreservation preserveSignatureNodeInWebView:completionHandler:]_block_invoke
Functions:
~ ___88+[MSWritingToolsSignaturePreservation preserveSignatureNodeInWebView:completionHandler:]_block_invoke -> ___75+[MSWritingToolsNodePreservation preserveNodesInWebView:completionHandler:]_block_invoke : 300 -> 648
CStrings:
+ "(function() {var preserved = [];var signatures = document.querySelectorAll('div[id=\"AppleMailSignature\"]');for (var i = 0; i < signatures.length; i++) {  if (!signatures[i].closest('blockquote[type=\"cite\"], blockquote.gmail_quote')) {    preserved.push(signatures[i]);    break;  }}var quotes = document.querySelectorAll('blockquote[type=\"cite\"], blockquote.gmail_quote');for (var j = 0; j < quotes.length; j++) {  var quote = quotes[j];  if (!quote.parentElement || !quote.parentElement.closest('blockquote[type=\"cite\"], blockquote.gmail_quote')) {    preserved.push(quote);  }}return preserved.map(function(node) { return window.webkit.createJSHandle(node); });})()"
+ "WKJSHandle"
+ "[Writing Tools] Failed to create preserved-node JSHandles: %@"
- "(function() {var nodes = document.querySelectorAll('div[id=\"AppleMailSignature\"]');for (var i = 0; i < nodes.length; i++) {  if (!nodes[i].closest('blockquote[type=\"cite\"]'))    return window.webkit.createJSHandle(nodes[i]);}})()"
- "[Writing Tools] Failed to create signature JSHandle: %@"
```
