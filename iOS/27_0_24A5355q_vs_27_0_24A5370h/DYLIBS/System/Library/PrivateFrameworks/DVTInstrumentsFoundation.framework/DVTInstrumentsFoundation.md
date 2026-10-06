## DVTInstrumentsFoundation

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/DVTInstrumentsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe7368` | `0xe4450` | **`-0x2f18`** |
| `__TEXT.__cstring` | `0x109bc` | `0xf31a` | **`-0x16a2`** |
| `__AUTH_CONST.__cfstring` | `0xb1c0` | `0xa1e0` | **`-0xfe0`** |
| `__TEXT.__objc_methlist` | `0x8e4c` | `0x8514` | **`-0x938`** |
| `__AUTH_CONST.__objc_const` | `0x12b08` | `0x123e8` | **`-0x720`** |
| `__TEXT.__oslogstring` | `0x577f` | `0x5ddf` | **`+0x660`** |
| `__DATA_CONST.__objc_selrefs` | `0x4868` | `0x4250` | **`-0x618`** |
| `__TEXT.__const` | `0x38da` | `0x3dd0` | **`+0x4f6`** |
| `__DATA.__bss` | `0x3f90` | `0x42f0` | **`+0x360`** |
| `__AUTH_CONST.__const` | `0x3208` | `0x34f8` | **`+0x2f0`** |
| `__DATA.__data` | `0x2cb8` | `0x2f68` | **`+0x2b0`** |
| `__TEXT.__constg_swiftt` | `0x1010` | `0x1294` | **`+0x284`** |
| `__DATA_CONST.__const` | `0x37a0` | `0x3520` | **`-0x280`** |
| `__TEXT.__eh_frame` | `0x168c` | `0x18dc` | **`+0x250`** |
| `__TEXT.__swift5_typeref` | `0xc18` | `0xe3c` | **`+0x224`** |
| `__TEXT.__swift5_reflstr` | `0xdb7` | `0xf97` | **`+0x1e0`** |
| `__TEXT.__swift5_fieldmd` | `0x1004` | `0x11dc` | **`+0x1d8`** |
| `__TEXT.__unwind_info` | `0x4028` | `0x3e58` | **`-0x1d0`** |
| `__AUTH.__data` | `0x1118` | `0x12d0` | **`+0x1b8`** |
| `__TEXT.__gcc_except_tab` | `0x6420` | `0x62d4` | **`-0x14c`** |
| `__DATA.__objc_ivar` | `0xcb8` | `0xbe4` | **`-0xd4`** |
| `__AUTH.__objc_data` | `0x4788` | `0x4848` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0xd00` | `0xd50` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x118` | `0x15c` | **`+0x44`** |
| `__AUTH_CONST.__auth_got` | `0x1fe8` | `0x2028` | **`+0x40`** |
| `__TEXT.__swift5_types` | `0x14c` | `0x180` | **`+0x34`** |
| `__DATA_CONST.__objc_superrefs` | `0x400` | `0x3d0` | **`-0x30`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x64` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x1f8` | `0x214` | **`+0x1c`** |
| `__DATA_CONST.__objc_protolist` | `0x240` | `0x258` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x698` | `0x688` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x78` | `0x88` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x8` | `0x18` | **`+0x10`** |

### Other Changes

```diff

-64578.129.2.0.0
+64578.141.1.0.0

+  - /usr/lib/swift/libswift_DarwinFoundation1.dylib

-  Functions: 5148
-  Symbols:   1931
-  CStrings:  2718
+  Functions: 4991
+  Symbols:   1881
+  CStrings:  2624
Symbols:
+ _CFDataGetTypeID
+ _CFPreferencesSynchronize
+ _CFStreamCreateBoundPair
+ _DTBACopySubjectAltNameIPAddressKey
+ _DTBASecGenerateSelfSignedCertificateWithError
+ _OBJC_CLASS_$_DTBAServerInfo
+ _OBJC_CLASS_$_DTBAServerSession
+ _OBJC_CLASS_$_OS_dispatch_source
+ _OBJC_CLASS_$__TtC24DVTInstrumentsFoundation17DTBATrustMaterial
+ _OBJC_METACLASS_$_DTBAServerInfo
+ _OBJC_METACLASS_$_DTBAServerSession
+ _OBJC_METACLASS_$__TtC24DVTInstrumentsFoundation17DTBATrustMaterial
+ _SecCertificateCopyCommonName
+ _SecCertificateCreateWithData
+ _SecCertificateNotValidAfter
+ _SecGenerateSelfSignedCertificate
+ _SecGenerateSelfSignedCertificateWithError
+ _SecIdentityCopyCertificate
+ _SecIdentityCreate
+ _SecIdentitySignCertificateWithParameters
+ _SecKeyCopyPublicKey
+ _SecKeyCreateRandomKey
+ _SecRandomCopyBytes
+ _SecTrustStoreCopyAll
+ _SecTrustStoreForDomain
+ _SecTrustStoreRemoveCertificate
+ _SecTrustStoreSetTrustSettings
+ __CFHTTPServerConnectionSetClient
+ __CFHTTPServerConnectionSetDispatchQueue
+ __CFHTTPServerCreateWithAcceptedSocket
+ __CFHTTPServerInvalidate
+ __CFHTTPServerRequestCopyProperty
+ __CFHTTPServerRequestCreateResponseMessage
+ __CFHTTPServerResponseCreateWithBodyStream
+ __CFHTTPServerResponseCreateWithData
+ __CFHTTPServerResponseEnqueue
+ __CFHTTPServerSetDispatchQueue
+ __CFHTTPServerSetProperty
+ __kCFHTTPServerRequestHeaderValuesKey
+ __kCFHTTPServerRequestHeaders
+ __kCFHTTPServerRequestMethod
+ __kCFHTTPServerRequestURL
+ __kCFHTTPServerSSLSettings
+ __kCFHTTPServerServerTrustChain
+ _kSecAttrCanWrap
+ _kSecAttrKeySizeInBits
+ _kSecAttrKeyType
+ _kSecAttrKeyTypeECSECPrimeRandom
+ _kSecCSRBasicConstraintsCA
+ _kSecCSRBasicContraintsPathLen
+ _kSecCertificateExtendedKeyUsage
+ _kSecCertificateExtensionsEncoded
+ _kSecCertificateKeyUsage
+ _kSecCertificateLifetime
+ _kSecCertificateSerialNumber
+ _kSecEKUServerAuth
+ _kSecOidCommonName
+ _kSecRandomDefault
+ _kSecSubjectAltName
+ _kSecSubjectAltNameDNSName
+ _kSecSubjectAltNameIPAddress
+ _swift_arrayDestroy
+ _swift_coroFrameAlloc
+ _swift_cvw_enumFn_getEnumTag
+ _swift_release_n
+ _swift_retain_n
+ _swift_willThrowTypedImpl
- OBJC_IVAR_$__DT_GCDAsyncReadPacket.buffer
- OBJC_IVAR_$__DT_GCDAsyncReadPacket.bufferOwner
- OBJC_IVAR_$__DT_GCDAsyncReadPacket.bytesDone
- OBJC_IVAR_$__DT_GCDAsyncReadPacket.maxLength
- OBJC_IVAR_$__DT_GCDAsyncReadPacket.originalBufferLength
- OBJC_IVAR_$__DT_GCDAsyncReadPacket.readLength
- OBJC_IVAR_$__DT_GCDAsyncReadPacket.startOffset
- OBJC_IVAR_$__DT_GCDAsyncReadPacket.tag
- OBJC_IVAR_$__DT_GCDAsyncReadPacket.term
- OBJC_IVAR_$__DT_GCDAsyncReadPacket.timeout
- OBJC_IVAR_$__DT_GCDAsyncSocketPreBuffer.preBuffer
- OBJC_IVAR_$__DT_GCDAsyncSocketPreBuffer.preBufferSize
- OBJC_IVAR_$__DT_GCDAsyncSocketPreBuffer.readPointer
- OBJC_IVAR_$__DT_GCDAsyncSocketPreBuffer.writePointer
- OBJC_IVAR_$__DT_GCDAsyncSpecialPacket.tlsSettings
- OBJC_IVAR_$__DT_GCDAsyncWritePacket.buffer
- OBJC_IVAR_$__DT_GCDAsyncWritePacket.bytesDone
- OBJC_IVAR_$__DT_GCDAsyncWritePacket.tag
- OBJC_IVAR_$__DT_GCDAsyncWritePacket.timeout
- _CFHTTPMessageAppendBytes
- _CFHTTPMessageCopyRequestMethod
- _CFHTTPMessageCopyRequestURL
- _CFHTTPMessageCopySerializedMessage
- _CFHTTPMessageCreateEmpty
- _CFHTTPMessageCreateResponse
- _CFHTTPMessageIsHeaderComplete
- _CFHTTPMessageSetBody
- _CFReadStreamClose
- _CFReadStreamCopyError
- _CFReadStreamGetStatus
- _CFReadStreamHasBytesAvailable
- _CFReadStreamOpen
- _CFReadStreamRead
- _CFReadStreamScheduleWithRunLoop
- _CFReadStreamSetClient
- _CFReadStreamSetProperty
- _CFReadStreamUnscheduleFromRunLoop
- _CFRunLoopGetCurrent
- _CFStreamCreatePairWithSocket
- _CFWriteStreamCanAcceptBytes
- _CFWriteStreamCopyError
- _CFWriteStreamGetStatus
- _CFWriteStreamScheduleWithRunLoop
- _CFWriteStreamSetClient
- _CFWriteStreamSetProperty
- _CFWriteStreamUnscheduleFromRunLoop
- _GCDAsyncSocketErrorDomain
- _GCDAsyncSocketException
- _GCDAsyncSocketManuallyEvaluateTrust
- _GCDAsyncSocketQueueName
- _GCDAsyncSocketSSLCipherSuites
- _GCDAsyncSocketSSLPeerID
- _GCDAsyncSocketSSLProtocolVersionMax
- _GCDAsyncSocketSSLProtocolVersionMin
- _GCDAsyncSocketSSLSessionOptionFalseStart
- _GCDAsyncSocketSSLSessionOptionSendOneByteRecord
- _GCDAsyncSocketThreadName
- _GCDAsyncSocketUseCFStreamForTLS
- _NSDefaultRunLoopMode
- _OBJC_CLASS_$_DTAssetHTTPRequestHandler
- _OBJC_CLASS_$_NSRunLoop
- _OBJC_CLASS_$_NSTimer
- _OBJC_CLASS_$__DT_GCDAsyncReadPacket
- _OBJC_CLASS_$__DT_GCDAsyncSocket
- _OBJC_CLASS_$__DT_GCDAsyncSocketPreBuffer
- _OBJC_CLASS_$__DT_GCDAsyncSpecialPacket
- _OBJC_CLASS_$__DT_GCDAsyncWritePacket
- _OBJC_METACLASS_$_DTAssetHTTPRequestHandler
- _OBJC_METACLASS_$__DT_GCDAsyncReadPacket
- _OBJC_METACLASS_$__DT_GCDAsyncSocket
- _OBJC_METACLASS_$__DT_GCDAsyncSocketPreBuffer
- _OBJC_METACLASS_$__DT_GCDAsyncSpecialPacket
- _OBJC_METACLASS_$__DT_GCDAsyncWritePacket
- _SSLClose
- _SSLCopyPeerTrust
- _SSLCreateContext
- _SSLGetBufferedReadSize
- _SSLHandshake
- _SSLRead
- _SSLSetCertificate
- _SSLSetConnection
- _SSLSetEnabledCiphers
- _SSLSetIOFuncs
- _SSLSetPeerDomainName
- _SSLSetPeerID
- _SSLSetProtocolVersionMax
- _SSLSetProtocolVersionMin
- _SSLSetSessionOption
- _SSLWrite
- _connect
- _dispatch_get_specific
- _dispatch_queue_set_specific
- _freeaddrinfo
- _freeifaddrs
- _gai_strerror
- _getaddrinfo
- _getifaddrs
- _getpeername
- _in6addr_any
- _inet_ntop
- _kCFBooleanFalse
- _kCFHTTPVersion1_0
- _kCFHTTPVersion1_1
- _kCFRunLoopDefaultMode
- _kCFStreamPropertySSLSettings
- _kCFStreamPropertyShouldCloseNativeSocket
- _kCFStreamSSLAllowsAnyRoot
- _kCFStreamSSLAllowsExpiredCertificates
- _kCFStreamSSLAllowsExpiredRoots
- _kCFStreamSSLCertificates
- _kCFStreamSSLIsServer
- _kCFStreamSSLLevel
- _kCFStreamSSLPeerName
- _kCFStreamSSLValidatesCertificateChain
- _poll
- _strtol
- _write
CStrings:
+ "%02x"
+ "%@:%@"
+ "%{public}s error: %{public}@"
+ "%{public}s sent %{public}ld bytes"
+ "%{public}s unexpected message"
+ "%{public}s write error"
+ "An unknown error occurred"
+ "AssetService: BA server reply has unexpected shape: %@"
+ "AssetService: BA server started on port %lu"
+ "AssetService: BA service %p created with channel %p for path %@"
+ "AssetService: DTAssetProviderService %p messageReceived (backgroundAssetsPath=%@)"
+ "AssetService: DTAssetProviderService %p received connection interrupted"
+ "AssetService: Error starting BA server on device: %@"
+ "BA server reply was not a DTBAServerInfo"
+ "Basic %@"
+ "CA generation failed: "
+ "CA keychain load failed: OSStatus "
+ "Could not build asset request"
+ "Could not build response"
+ "Could not open response stream"
+ "DTAssetService: BA HTTPS server listening on port %lu"
+ "DTAssetService: Clearing stale BA development override URL left over from a prior session"
+ "DTAssetService: Failed to archive BA override URL: %{public}@"
+ "DTAssetService: Failed to generate Basic-auth password"
+ "DTAssetService: Failed to materialize trust: %{public}@"
+ "DTAssetService: Failed to start BA HTTPS server: %{public}@"
+ "DTAssetService: Published BA development override URL https://localhost:%lu (with userinfo)"
+ "DTAssetService: Restored user's pre-existing BA development override URL"
+ "DTAssets"
+ "DTServiceHub Asset Server ("
+ "DTServiceHub Background Assets Development CA"
+ "DVTInstrumentsFoundation.DTBAServerInfo"
+ "DVTInstrumentsFoundation.DTBATrustMaterial"
+ "GET %{public}s identifier=%{public}s"
+ "Generated ephemeral CA identity (expires %{public}s)"
+ "Leaf certificate issuance returned nil"
+ "Listening on port %{public}hu (%{public}s)"
+ "SecIdentityCopyCertificate failed: OSStatus %{public}d"
+ "SecIdentityCreate returned nil"
+ "SecIdentityCreate returned nil for leaf certificate"
+ "SecIdentitySignCertificateWithParameters returned nil for host %{public}s"
+ "SecKeyCopyPublicKey returned nil for ephemeral leaf key"
+ "SecRandomCopyBytes failed: OSStatus %{public}d"
+ "SecTrustStoreCopyAll failed: OSStatus %{public}d"
+ "SecTrustStoreForDomain returned nil for user domain"
+ "SecTrustStoreRemoveCertificate failed: OSStatus %{public}d"
+ "SecTrustStoreSetTrustSettings failed: OSStatus %{public}d"
+ "Trust store install failed: OSStatus "
+ "WWW-Authenticate"
+ "_CFHTTPServerCreateWithAcceptedSocket returned NULL"
+ "accept failed: %{public}s (%d)"
+ "assetpacks"
+ "background assets path is empty"
+ "connection error: %{public}s"
+ "https"
+ "kSecTrustSettingsResult"
+ "key generation failed: "
+ "listen() failed: "
+ "manifest"
+ "objectWithAllowedClasses:"
+ "server error: %{public}s"
+ "socket() failed: "
- "\n"
- "\r"
- "\r\n"
- "%"
- "%hu"
- "%lx\r\n"
- "/assetpacks/"
- "/manifest"
- "0\r\n\r\n"
- "A valid IPv4 or IPv6 address was not given"
- "AssetService: Clearing MBAURLOverride"
- "AssetService: Error starting server on device: %@"
- "AssetService: Failed to clear MBAURLOverride: %@"
- "AssetService: Failed to set MBAURLOverride: %@"
- "AssetService: MBAURLOverride cleared successfully"
- "AssetService: MBAURLOverride set successfully"
- "AssetService: Setting MBAURLOverride to %@"
- "Attempt to connect to host timed out"
- "Attempting to accept while connected or accepting connections. Disconnect first."
- "Attempting to accept without a delegate queue. Set a delegate queue first."
- "Attempting to accept without a delegate. Set a delegate first."
- "Attempting to connect while connected or accepting connections. Disconnect first."
- "Attempting to connect without a delegate queue. Set a delegate queue first."
- "Attempting to connect without a delegate. Set a delegate first."
- "Both IPv4 and IPv6 have been disabled. Must enable at least one protocol first."
- "Cannot flush ssl buffers on non-secure socket"
- "DTAssetHTTPRequestHandler"
- "DTAssetService: Cleared MBAURLOverride"
- "DTAssetService: Failed to access BA defaults suite"
- "DTAssetService: Failed to access BA defaults suite for cleanup"
- "DTAssetService: Failed to archive URL: %@"
- "DTAssetService: Invalid BA URL override: %@"
- "DTAssetService: Set MBAURLOverride to %@"
- "Error code definition can be found in Apple's SecureTransport.h"
- "Error creating CFStreams"
- "Error enabling address reuse (setsockopt)"
- "Error enabling close-on-exec on socket (fcntl)"
- "Error enabling non-blocking IO on socket (fcntl)"
- "Error in CFStreamCreatePairWithSocket"
- "Error in CFStreamOpen"
- "Error in CFStreamScheduleWithRunLoop"
- "Error in CFStreamSetClient"
- "Error in CFStreamSetProperty"
- "Error in SSLCreateContext"
- "Error in SSLSetCertificate"
- "Error in SSLSetConnection"
- "Error in SSLSetEnabledCiphers"
- "Error in SSLSetIOFuncs"
- "Error in SSLSetPeerDomainName"
- "Error in SSLSetPeerID"
- "Error in SSLSetProtocolVersionMax"
- "Error in SSLSetProtocolVersionMin"
- "Error in SSLSetSessionOption"
- "Error in SSLSetSessionOption (kSSLSessionOptionFalseStart)"
- "Error in SSLSetSessionOption (kSSLSessionOptionSendOneByteRecord)"
- "Error in bind() function"
- "Error in connect() function"
- "Error in listen() function"
- "Error in read() function"
- "Error in socket() function"
- "Error in write() function"
- "Error retrieving requested asset: %@"
- "Expected at least one valid address"
- "GCDAsyncSocket.m"
- "GCDAsyncSocketClosedError"
- "GCDAsyncSocketConnectTimeoutError"
- "GCDAsyncSocketErrorDomain"
- "GCDAsyncSocketException"
- "GCDAsyncSocketManuallyEvaluateTrust"
- "GCDAsyncSocketManuallyEvaluateTrust specified in tlsSettings, but delegate doesn't implement socket:shouldTrustPeer:"
- "GCDAsyncSocketReadMaxedOutError"
- "GCDAsyncSocketReadTimeoutError"
- "GCDAsyncSocketSSLCipherSuites"
- "GCDAsyncSocketSSLPeerID"
- "GCDAsyncSocketSSLProtocolVersionMax"
- "GCDAsyncSocketSSLProtocolVersionMin"
- "GCDAsyncSocketSSLSessionOptionFalseStart"
- "GCDAsyncSocketSSLSessionOptionSendOneByteRecord"
- "GCDAsyncSocketUseCFStreamForTLS"
- "GCDAsyncSocketWriteTimeoutError"
- "GET"
- "HEAD"
- "IPv4 has been disabled and DNS lookup found no IPv6 address."
- "IPv4 has been disabled and an IPv4 address was passed."
- "IPv4 has been disabled and specified interface doesn't support IPv6."
- "IPv6 has been disabled and DNS lookup found no IPv4 address."
- "IPv6 has been disabled and an IPv6 address was passed."
- "IPv6 has been disabled and specified interface doesn't support IPv4."
- "Invalid TLS transition. Handshake has already been read from socket."
- "Invalid host parameter (nil or \"\"). Should be a domain name or IP address string."
- "Invalid logic"
- "Invalid parameter: bytesAvailable"
- "Invalid read packet for startTLS"
- "Invalid value for GCDAsyncSocketSSLCipherSuites."
- "Invalid value for GCDAsyncSocketSSLCipherSuites. Value must be of type NSArray."
- "Invalid value for GCDAsyncSocketSSLPeerID."
- "Invalid value for GCDAsyncSocketSSLPeerID. Value must be of type NSData. (You can convert strings to data using a method like [string dataUsingEncoding:NSUTF8StringEncoding])"
- "Invalid value for GCDAsyncSocketSSLProtocolVersionMax."
- "Invalid value for GCDAsyncSocketSSLProtocolVersionMax. Value must be of type NSNumber."
- "Invalid value for GCDAsyncSocketSSLProtocolVersionMin."
- "Invalid value for GCDAsyncSocketSSLProtocolVersionMin. Value must be of type NSNumber."
- "Invalid value for GCDAsyncSocketSSLSessionOptionFalseStart."
- "Invalid value for GCDAsyncSocketSSLSessionOptionFalseStart. Value must be of type NSNumber."
- "Invalid value for GCDAsyncSocketSSLSessionOptionSendOneByteRecord."
- "Invalid value for GCDAsyncSocketSSLSessionOptionSendOneByteRecord. Value must be of type NSNumber."
- "Invalid value for kCFStreamSSLCertificates."
- "Invalid value for kCFStreamSSLCertificates. Value must be of type NSArray."
- "Invalid value for kCFStreamSSLPeerName."
- "Invalid value for kCFStreamSSLPeerName. Value must be of type NSString."
- "Invalid write packet for startTLS"
- "Invoked on wrong thread"
- "Invoked with empty pre buffer!"
- "Logic error"
- "Manual trust validation is not supported for server sockets"
- "Must be dispatched on socketQueue"
- "Not found."
- "ODR: Got a message we're not sure how to handle: %s"
- "ODR: Received GET request %s for asset pack %s. Requesting from Xcode."
- "ODR: Received HEAD request for asset pack. Sending default 200 response."
- "ODR: Request %s sent %llu bytes"
- "ODR: Socket %s disconnected with error: %s"
- "ODR: Socket %s disconnected without error."
- "OSStatus SSLReadFunction(SSLConnectionRef, void *, size_t *)"
- "OSStatus SSLWriteFunction(SSLConnectionRef, const void *, size_t *)"
- "Read operation reached set maximum length"
- "Read operation timed out"
- "Read/Write stream is null"
- "Security option unavailable - kCFStreamSSLAllowsAnyRoot"
- "Security option unavailable - kCFStreamSSLAllowsAnyRoot - You must use manual trust evaluation"
- "Security option unavailable - kCFStreamSSLAllowsExpiredCertificates"
- "Security option unavailable - kCFStreamSSLAllowsExpiredCertificates - You must use manual trust evaluation"
- "Security option unavailable - kCFStreamSSLAllowsExpiredRoots"
- "Security option unavailable - kCFStreamSSLAllowsExpiredRoots - You must use manual trust evaluation"
- "Security option unavailable - kCFStreamSSLLevel"
- "Security option unavailable - kCFStreamSSLLevel - You must use GCDAsyncSocketSSLProtocolVersionMin & GCDAsyncSocketSSLProtocolVersionMax"
- "Security option unavailable - kCFStreamSSLValidatesCertificateChain"
- "Security option unavailable - kCFStreamSSLValidatesCertificateChain - You must use manual trust evaluation"
- "Socket closed by remote peer"
- "The given socketQueue parameter must not be a concurrent queue."
- "This method does not apply to non-term reads"
- "This method does not apply to term reads"
- "This server does not handle %@ requests."
- "Trying to complete current read when there is no current read."
- "Trying to complete current write when there is no current write."
- "Unknown interface. Specify valid interface by name (e.g. \"en1\") or IP address."
- "What the deuce?"
- "Write operation timed out"
- "_DT_GCDAsyncSocket"
- "_DT_GCDAsyncSocket-CFStream"
- "_DT_GCDAsyncSocket-CFStreamThreadSetup"
- "chunked"
- "https://localhost:%lu"
- "i20@?0i8@\"NSData\"12"
- "kCFStreamErrorDomainNetDB"
- "kCFStreamErrorDomainSSL"
- "loopback"
```
