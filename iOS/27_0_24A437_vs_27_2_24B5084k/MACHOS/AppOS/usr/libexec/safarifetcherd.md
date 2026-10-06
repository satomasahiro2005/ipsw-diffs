## safarifetcherd

> `/usr/libexec/safarifetcherd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methtype` | `0x251d` | `0x2a60` | **`+0x543`** |
| `__TEXT.__objc_methname` | `0x54b0` | `0x57db` | **`+0x32b`** |
| `__TEXT.__text` | `0x933c` | `0x94bc` | **`+0x180`** |
| `__DATA.__objc_const` | `0x1630` | `0x1768` | **`+0x138`** |
| `__DATA.__data` | `0x368` | `0x488` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x1394` | `0x149c` | **`+0x108`** |
| `__DATA.__objc_selrefs` | `0x1190` | `0x1210` | **`+0x80`** |
| `__TEXT.__objc_classname` | `0x162` | `0x1a9` | **`+0x47`** |
| `__TEXT.__objc_stubs` | `0x2480` | `0x24c0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x328` | `0x348` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xb10` | `0xb30` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2d8` | `0x2f0` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x48` | `0x60` | **`+0x18`** |
| `__DATA.__bss` | `0x40` | `0x50` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x7f0` | `0x800` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5c0` | `0x5d0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x410` | `0x418` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`

### Other Changes

```diff

-7625.1.29.10.29
+7625.2.4.1.0

-  Functions: 265
-  Symbols:   229
-  CStrings:  1023
+  Functions: 266
+  Symbols:   233
+  CStrings:  1062
Symbols:
+ _OBJC_CLASS_$_NSOperationQueue
+ _OBJC_CLASS_$_NSURLSession
+ _OBJC_CLASS_$_NSURLSessionConfiguration
+ _OBJC_CLASS_$__WKWebsiteDataStoreConfiguration
+ _objc_retain_x4
- _OBJC_CLASS_$_NSURLConnection
CStrings:
+ "@\"NSURLSessionDataTask\""
+ "NSURLSessionDataDelegate"
+ "NSURLSessionDelegate"
+ "NSURLSessionTaskDelegate"
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
+ "_dataTask"
+ "_sharedURLSession"
+ "dataTaskWithRequest:"
+ "initNonPersistentConfiguration"
+ "mainQueue"
+ "resume"
+ "safari_ephemeralSessionConfiguration"
+ "sessionWithConfiguration:delegate:delegateQueue:"
+ "setSourceApplicationBundleIdentifier:"
+ "v24@0:8@\"NSURLSession\"16"
+ "v32@0:8@\"NSURLSession\"16@\"NSError\"24"
+ "v32@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLAuthenticationChallenge\"24@?<v@?q@\"NSURLCredential\">32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionDataTask\"24@\"NSData\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionDataTask\"24@\"NSURLSessionDownloadTask\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionDataTask\"24@\"NSURLSessionStreamTask\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSError\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSHTTPURLResponse\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSURLSessionTaskMetrics\"32"
+ "v40@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@?<v@?@\"NSInputStream\">32"
+ "v48@0:8@\"NSURLSession\"16@\"NSURLSessionDataTask\"24@\"NSCachedURLResponse\"32@?<v@?@\"NSCachedURLResponse\">40"
+ "v48@0:8@\"NSURLSession\"16@\"NSURLSessionDataTask\"24@\"NSURLResponse\"32@?<v@?q>40"
+ "v48@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSURLAuthenticationChallenge\"32@?<v@?q@\"NSURLCredential\">40"
+ "v48@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSURLRequest\"32@?<v@?q@\"NSURLRequest\">40"
+ "v48@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24q32@?<v@?@\"NSInputStream\">40"
+ "v48@0:8@16@24q32@?40"
+ "v56@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24@\"NSHTTPURLResponse\"32@\"NSURLRequest\"40@?<v@?@\"NSURLRequest\">48"
+ "v56@0:8@\"NSURLSession\"16@\"NSURLSessionTask\"24q32q40q48"
+ "v56@0:8@16@24q32q40q48"
- "@\"NSURLConnection\""
- "_URLConnection"
- "_cancelConnectionAndFetchNextIcon"
- "cancelAuthenticationChallenge:"
- "connection:didFailWithError:"
- "connection:didReceiveAuthenticationChallenge:"
- "connection:didReceiveData:"
- "connection:didReceiveResponse:"
- "connectionDidFinishLoading:"
- "initWithRequest:delegate:"
- "nonPersistentDataStore"
- "sender"
- "useCredential:forAuthenticationChallenge:"
```
