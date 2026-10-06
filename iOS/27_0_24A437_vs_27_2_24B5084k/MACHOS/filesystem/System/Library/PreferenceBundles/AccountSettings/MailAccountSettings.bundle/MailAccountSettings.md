## MailAccountSettings

> `/System/Library/PreferenceBundles/AccountSettings/MailAccountSettings.bundle/MailAccountSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x790e0` | `0x78474` | **`-0xc6c`** |
| `__DATA.__objc_const` | `0xb060` | `0xada8` | **`-0x2b8`** |
| `__TEXT.__objc_methname` | `0xdb4e` | `0xd907` | **`-0x247`** |
| `__TEXT.__gcc_except_tab` | `0x11ec0` | `0x11d54` | **`-0x16c`** |
| `__TEXT.__objc_stubs` | `0xa2c0` | `0xa1a0` | **`-0x120`** |
| `__TEXT.__objc_methlist` | `0x63f0` | `0x62d8` | **`-0x118`** |
| `__TEXT.__objc_methtype` | `0x2c84` | `0x2bb8` | **`-0xcc`** |
| `__DATA.__objc_data` | `0x2990` | `0x28f0` | **`-0xa0`** |
| `__DATA.__objc_selrefs` | `0x3948` | `0x38b8` | **`-0x90`** |
| `__TEXT.__cstring` | `0x4e00` | `0x4d75` | **`-0x8b`** |
| `__DATA.__data` | `0xb00` | `0xaa0` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x12f8` | `0x12a8` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x3b58` | `0x3b10` | **`-0x48`** |
| `__TEXT.__objc_classname` | `0x10f1` | `0x10b0` | **`-0x41`** |
| `__DATA.__objc_ivar` | `0x6b0` | `0x698` | **`-0x18`** |
| `__DATA_CONST.__got` | `0xa20` | `0xa08` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x428` | `0x418` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x3e8` | `0x3d8` | **`-0x10`** |
| `__DATA.__common` | `0xb0` | `0xa8` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xe8` | `0xe0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-3901.100.1.2.14
+3901.200.34.0.0

-  Functions: 2037
-  Symbols:   875
-  CStrings:  3641
+  Functions: 2018
+  Symbols:   868
+  CStrings:  3600
Symbols:
- _OBJC_CLASS_$_BYODDataCardEditableCell
- _OBJC_CLASS_$_BYODServiceManager
- _OBJC_CLASS_$_NSHTTPURLResponse
- _OBJC_CLASS_$_NSOperationQueue
- _OBJC_CLASS_$_NSURLSession
- _OBJC_METACLASS_$_BYODDataCardEditableCell
- _OBJC_METACLASS_$_BYODServiceManager
CStrings:
- "!_dataTask"
- "!_request"
- "-[BYODServiceManager loadRequest:withCompletion:]"
- "@\"NSURLRequest\""
- "@\"NSURLSession\""
- "@\"NSURLSessionDataTask\""
- "BYODDataCardEditableCell"
- "BYODServiceManager"
- "BYODServiceManager.m"
- "NSURLSessionDelegate"
- "T@\"UILabel\",&,N,V_title"
- "T@\"UIStackView\",&,N,V_container"
- "T@\"UITextField\",&,N,V_text"
- "URLSession:didBecomeInvalidWithError:"
- "URLSession:didReceiveChallenge:completionHandler:"
- "URLSessionDidFinishEventsForBackgroundURLSession:"
- "_container"
- "_dataTask"
- "_editableFont"
- "_finishedLoading"
- "_getUserFullName"
- "_mailAccountNameChanged"
- "_preLoadCancel"
- "_request"
- "_text"
- "_title"
- "_urlSession"
- "centerXAnchor"
- "container"
- "dataTaskWithRequest:completionHandler:"
- "initWithTitle:"
- "loadRequest:withCompletion:"
- "mainQueue"
- "receivedValidResponse:forRequest:"
- "resume"
- "sessionWithConfiguration:delegate:delegateQueue:"
- "setContainer:"
- "v24@0:8@\"NSURLSession\"16"
- "v32@0:8@\"NSURLSession\"16@\"NSError\"24"
- "v32@?0@\"NSData\"8@\"NSURLResponse\"16@\"NSError\"24"
- "v40@0:8@\"NSURLSession\"16@\"NSURLAuthenticationChallenge\"24@?<v@?q@\"NSURLCredential\">32"
```
