## XPCAcmeService

> `/System/Library/Frameworks/Security.framework/XPCServices/XPCAcmeService.xpc/XPCAcmeService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methtype` | `0x65` | `0x6c4` | **`+0x65f`** |
| `__TEXT.__objc_methname` | `0x2db` | `0x8cb` | **`+0x5f0`** |
| `__TEXT.__text` | `0x3744` | `0x3c24` | **`+0x4e0`** |
| `__DATA.__objc_const` | `0x130` | `0x3f0` | **`+0x2c0`** |
| `__TEXT.__objc_stubs` | `0x3c0` | `0x600` | **`+0x240`** |
| `__TEXT.__objc_methlist` | `0x8c` | `0x28c` | **`+0x200`** |
| `__DATA.__objc_selrefs` | `0x120` | `0x2c8` | **`+0x1a8`** |
| `__DATA.__data` | `0x40` | `0x1c0` | **`+0x180`** |
| `__DATA_CONST.__cfstring` | `0x2a0` | `0x320` | **`+0x80`** |
| `__TEXT.__objc_classname` | `0xb` | `0x75` | **`+0x6a`** |
| `__DATA.__objc_data` | `0x50` | `0xa0` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x9c0` | `0x970` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0x4f0` | `0x4c8` | **`-0x28`** |
| `__DATA_CONST.__const` | `0x220` | `0x1f8` | **`-0x28`** |
| `__DATA_CONST.__objc_protolist` | `—` | `0x20` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xf8` | `0x110` | **`+0x18`** |
| `__TEXT.__cstring` | `0x35a` | `0x36d` | **`+0x13`** |
| `__DATA.__objc_ivar` | `0xc` | `0x14` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__const` | `0xb8` | `0xb0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.0.55.0.1
+62460.2.1.0.0
+  - /System/Library/Frameworks/CFNetwork.framework/CFNetwork

+  - /usr/lib/libbsm.0.dylib

-  Functions: 61
-  Symbols:   200
-  CStrings:  103
+  Functions: 58
+  Symbols:   198
+  CStrings:  213
Symbols:
+ _OBJC_CLASS_$_NSMutableData
+ _OBJC_CLASS_$_NSURLComponents
+ _OBJC_CLASS_$_NSURLSession
+ _OBJC_CLASS_$_NSURLSessionConfiguration
+ _OBJC_CLASS_$__NSHSTSStorage
+ _audit_token_to_pid
+ _objc_autorelease
+ _objc_retain_x21
+ _objc_retain_x3
+ _objc_retain_x8
- _OBJC_CLASS_$_NSOperationQueue
- _OBJC_CLASS_$_NSURLConnection
- _dispatch_async
- _objc_alloc_init
- _objc_destroyWeak
- _objc_getProperty
- _objc_loadWeakRetained
- _objc_retain_x24
- _objc_retain_x25
- _objc_retain_x4
- _objc_setProperty_atomic
- _objc_storeWeak
CStrings:
+ "#16@0:8"
+ "@\"NSMutableData\""
+ "@\"NSString\"16@0:8"
+ "@\"NSURLResponse\""
+ "@24@0:8:16"
+ "@32@0:8:16@24"
+ "@32@0:8Q16@?24"
+ "@40@0:8:16@24@32"
+ "@40@0:8r*16Q24^@32"
+ "@?"
+ "AcmeSessionDelegate"
+ "B"
+ "B16@0:8"
+ "B24@0:8#16"
+ "B24@0:8:16"
+ "B24@0:8@\"Protocol\"16"
+ "B24@0:8@16"
+ "B32@0:8@16Q24"
+ "GET"
+ "HEAD"
+ "NSObject"
+ "NSURLSessionDataDelegate"
+ "NSURLSessionDelegate"
+ "NSURLSessionTaskDelegate"
+ "Q"
+ "Q16@0:8"
+ "SecXPCNetworkURL"
+ "T#,R"
+ "T@\"NSString\",?,R,C"
+ "T@\"NSString\",R,C"
+ "TQ,R"
+ "URL"
+ "URLSession:dataTask:didBecomeDownloadTask:"
+ "URLSession:dataTask:didBecomeStreamTask:"
+ "URLSession:dataTask:didReceiveData:"
+ "URLSession:dataTask:didReceiveResponse:completionHandler:"
+ "URLSession:dataTask:willCacheResponse:completionHandler:"
+ "URLSession:didBecomeInvalidWithError:"
+ "URLSession:didCreateTask:"
+ "URLSession:didReceiveChallenge:completionHandler:"
+ "URLSession:task:didCompleteWithError:"
+ "URLSession:task:didFinishCollectingMetrics:"
+ "URLSession:task:didReceiveChallenge:completionHandler:"
+ "URLSession:task:didReceiveInformationalResponse:"
+ "URLSession:task:didSendBodyData:totalBytesSent:totalBytesExpectedToSend:"
+ "URLSession:task:needNewBodyStream:"
+ "URLSession:task:needNewBodyStreamFromOffset:completionHandler:"
+ "URLSession:task:willBeginDelayedRequest:completionHandler:"
+ "URLSession:task:willPerformHTTPRedirection:newRequest:completionHandler:"
+ "URLSession:taskIsWaitingForConnectivity:"
+ "URLSessionDidFinishEventsForBackgroundURLSession:"
+ "URLWithString:"
+ "Vv16@0:8"
+ "^{_NSZone=}16@0:8"
+ "_completion"
+ "_data"
+ "_exceededCap"
+ "_maxBytes"
+ "_response"
+ "allowedURLFromCString:options:error:"
+ "appendData:"
+ "autorelease"
+ "cancel"
+ "class"
+ "componentsWithString:"
+ "conformsToProtocol:"
+ "copy"
+ "data"
+ "dataTaskWithRequest:"
+ "debugDescription"
+ "ephemeralSessionConfiguration"
+ "finishTasksAndInvalidate"
+ "hash"
+ "host"
+ "http"
+ "https"
+ "initInMemoryStore"
+ "initWithMaxBytes:callback:"
+ "initWithUTF8String:"
+ "isAllowedURL:options:"
+ "isEqual:"
+ "isKindOfClass:"
+ "isMemberOfClass:"
+ "isProxy"
+ "lowercaseString"
+ "performSelector:"
+ "performSelector:withObject:"
+ "performSelector:withObject:withObject:"
+ "release"
+ "respondsToSelector:"
+ "resume"
+ "retain"
+ "retainCount"
+ "scheme"
+ "scheme:isAllowedByOptions:"
+ "self"
+ "sessionWithConfiguration:delegate:delegateQueue:"
+ "setError:code:"
+ "setHTTPAdditionalHeaders:"
+ "setHTTPCookieStorage:"
+ "setURLCache:"
+ "setURLCredentialStorage:"
+ "set_hstsStorage:"
+ "superclass"
+ "v24@0:8@\"NSURLSession\"16"
+ "v32@0:8@\"NSURLSession\"16@\"NSError\"24"
+ "v32@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24"
+ "v32@0:8@16@24"
+ "v32@0:8^@16q24"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLAuthenticationChallenge\"24@?<v@?q@\"NSURLCredential\">32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionDataTask\"24@\"NSData\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionDataTask\"24@\"NSURLSessionDownloadTask\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionDataTask\"24@\"NSURLSessionStreamTask\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSError\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSHTTPURLResponse\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSURLSessionTaskMetrics\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@?<v@?@\"NSInputStream\">32"
+ "v40@0:8@16@24@?32"
+ "v48@0:8@\"NSURLSession\"16@\"NSURLSessionDataTask\"24@\"NSCachedURLResponse\"32@?<v@?@\"NSCachedURLResponse\">40"
+ "v48@0:8@\"NSURLSession\"16@\"NSURLSessionDataTask\"24@\"NSURLResponse\"32@?<v@?q>40"
+ "v48@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSURLAuthenticationChallenge\"32@?<v@?q@\"NSURLCredential\">40"
+ "v48@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSURLRequest\"32@?<v@?q@\"NSURLRequest\">40"
+ "v48@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24q32@?<v@?@\"NSInputStream\">40"
+ "v48@0:8@16@24@32@?40"
+ "v48@0:8@16@24q32@?40"
+ "v56@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSHTTPURLResponse\"32@\"NSURLRequest\"40@?<v@?@\"NSURLRequest\">48"
+ "v56@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24q32q40q48"
+ "v56@0:8@16@24@32@40@?48"
+ "v56@0:8@16@24q32q40q48"
+ "zone"
- "@"
- "@\"NSMutableURLRequest\""
- "@\"NSURL\""
- "@24@0:8@16"
- "AcmeClient"
- "T@,&,Vurl"
- "T@,&,VurlRequest"
- "T@,W,Vdelegate"
- "delegate"
- "initWithString:"
- "initWithURLString:"
- "post:withMethod:contentType:"
- "sendAsynchronousRequest:queue:completionHandler:"
- "setDelegate:"
- "setUrl:"
- "setUrlRequest:"
- "start3:"
- "stringByAddingPercentEscapesUsingEncoding:"
- "urlRequest"
- "v24@0:8@?16"
```
