## Diagnostic-8268

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8268.appex/Diagnostic-8268`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f5c` | `0xb188` | **`+0x822c`** |
| `__TEXT.__cstring` | `0x6ae` | `0x1d1b` | **`+0x166d`** |
| `__DATA_CONST.__cfstring` | `0x3c0` | `0x10a0` | **`+0xce0`** |
| `__TEXT.__oslogstring` | `0x3e6` | `0x984` | **`+0x59e`** |
| `__TEXT.__auth_stubs` | `0x350` | `0x7d0` | **`+0x480`** |
| `__TEXT.__objc_stubs` | `0x480` | `0x840` | **`+0x3c0`** |
| `__DATA_CONST.__auth_got` | `0x1b0` | `0x3f0` | **`+0x240`** |
| `__TEXT.__objc_methname` | `0x6bd` | `0x85f` | **`+0x1a2`** |
| `__TEXT.__unwind_info` | `0xf0` | `0x230` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x40` | `0x150` | **`+0x110`** |
| `__DATA_CONST.__objc_intobj` | `0x30` | `0x138` | **`+0x108`** |
| `__DATA.__data` | `0x120` | `0x1e0` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0xa0` | `0x140` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x248` | `0x2e0` | **`+0x98`** |
| `__TEXT.__const` | `0x78` | `0x100` | **`+0x88`** |
| `__DATA.__bss` | `0x18` | `0x48` | **`+0x30`** |
| `__DATA.__common` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x10` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

+  - /System/Library/Frameworks/CFNetwork.framework/CFNetwork

-  Functions: 90
-  Symbols:   90
-  CStrings:  221
+  Functions: 296
+  Symbols:   192
+  CStrings:  504
Symbols:
+ _AMAuthInstallApImg4SetSepNonce
+ _AMAuthInstallSetSigningServerURL
+ _AMFDRSealingMapGetFDRDataVersionForDevice
+ _AMSupportCopyHexStringFromData
+ _AMSupportCreateSetFromCFIndexArray
+ _AMSupportHttpCopyProxySettings
+ _AMSupportHttpSendSync
+ _AMSupportLogDumpMemory
+ _AMSupportLogInternal
+ _AMSupportLogSetHandler
+ _CFDataCreate
+ _CFDataCreateCopy
+ _CFDataCreateWithBytesNoCopy
+ _CFDataGetBytePtr
+ _CFDataGetBytes
+ _CFDataGetLength
+ _CFDataGetTypeID
+ _CFDictionaryAddValue
+ _CFDictionaryApplyFunction
+ _CFDictionaryContainsKey
+ _CFDictionaryCreateCopy
+ _CFDictionaryCreateMutable
+ _CFDictionaryGetTypeID
+ _CFDictionaryGetValue
+ _CFDictionarySetValue
+ _CFErrorCreate
+ _CFGetTypeID
+ _CFHTTPMessageCopyAllHeaderFields
+ _CFHTTPMessageCreateRequest
+ _CFHTTPMessageSetBody
+ _CFHTTPMessageSetHeaderFieldValue
+ _CFNumberCreate
+ _CFPropertyListCreateData
+ _CFPropertyListCreateWithData
+ _CFRelease
+ _CFRetain
+ _CFStringAppend
+ _CFStringCompare
+ _CFStringCreateMutable
+ _CFStringCreateMutableCopy
+ _CFStringCreateWithFormat
+ _CFStringGetTypeID
+ _CFUUIDCreate
+ _CFUUIDCreateString
+ _HSCGetMesaNonce
+ _HSCSecureProvisionMesaWithUID
+ _HSCSecureProvisionMesaWithUIDProxy
+ _IOConnectCallMethod
+ _IORegistryEntryCreateCFProperty
+ _IORegistryEntryFromPath
+ _OBJC_CLASS_$_CRPersonalizationManager
+ _OBJC_CLASS_$_CRPreflightController
+ _OBJC_CLASS_$_NSNumber
+ __NSConcreteStackBlock
+ ___chkstk_darwin
+ ___memcpy_chk
+ ___osLogPearlLib
+ ___osLogPearlLibTrace
+ ___stdoutp
+ __logHandler
+ _bzero
+ _calloc
+ _ccder_blob_decode_len
+ _ccder_blob_decode_range
+ _ccder_blob_decode_sequence_tl
+ _ccder_blob_decode_tag
+ _ccder_blob_decode_tl
+ _ccder_blob_encode_body
+ _ccder_blob_encode_tl
+ _ccder_sizeof
+ _ccdigest
+ _ccsha384_di
+ _cleanIOServiceConnection
+ _dispatch_queue_create
+ _dispatch_sync
+ _fprintf
+ _initializeIOServiceConnectionWithNameAndType
+ _kAMSupportHttpOptionDisableSSLValidation
+ _kAMSupportHttpOptionMaxAttempts
+ _kAMSupportHttpOptionSocksProxySettings
+ _kAMSupportHttpOptionTimeout
+ _kAMSupportHttpOptionValidResponses
+ _kCFAllocatorMalloc
+ _kCFBooleanFalse
+ _kCFBooleanTrue
+ _kCFErrorLocalizedDescriptionKey
+ _kCFHTTPVersion1_1
+ _kCFNull
+ _kCFTypeDictionaryKeyCallBacks
+ _kCFTypeDictionaryValueCallBacks
+ _kIOMasterPortDefault
+ _malloc
+ _malloc_type_calloc
+ _memcmp
+ _memcpy
+ _memset_s
+ _objc_release
+ _objc_retainBlock
+ _pearlSeaCookieHandleMessage
+ _performCommand
+ _qsort
+ _syslog
CStrings:
+ "\terrorCode: "
+ "\terrorString: "
+ "%.*s"
+ "%.2X"
+ "%@\n"
+ "%d"
+ "%llu"
+ "%lu"
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s aks connection failed%s\n"
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s bad 1%s\n"
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s fail%s\n"
+ "(type == kMesaFactorySeaCookieMessageS0) || (type == kMesaFactorySeaCookieGenerateNonce) || message"
+ "(type == kMesaFactorySeaCookieMessageS0) || (type == kMesaFactorySeaCookieGenerateNonce) || messageLength"
+ "(type == kMesaFactorySeaCookieValidateTatsuTicket) || reply"
+ "(type == kMesaFactorySeaCookieValidateTatsuTicket) || replySize"
+ "(type == kPearlFactorySeaCookieMessageS0) || (type == kPearlFactorySeaCookieGenerateNonce) || message"
+ "(type == kPearlFactorySeaCookieMessageS0) || (type == kPearlFactorySeaCookieGenerateNonce) || messageSize"
+ "(type == kPearlFactorySeaCookieValidateTatsuTicket) || reply"
+ "(type == kPearlFactorySeaCookieValidateTatsuTicket) || replySize"
+ "*bufferSize"
+ "*replySize >= outData->dataSize"
+ "------- CLIENT REQUEST -------\n"
+ "------- END CLIENT REQUEST -------\n"
+ "------- END SERVER RESPONSE -------\n"
+ "------- SERVER RESPONSE -------\n"
+ "--------------------------------------------------------------\n"
+ "-[MesaPairer runWithInputs:results:]"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Pearl_Kernel/PearlFactoryLib/PearlFactoryLib.m"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Pearl_Kernel/PearlSupport/PearlSupportUtils.m"
+ "/tmp/%@"
+ "/tmp/%@-from-server"
+ "00"
+ "0x"
+ "1.2"
+ ":"
+ "ApChipID"
+ "ApChipID: %@"
+ "ApECID"
+ "ApECID: %@"
+ "AppleKeyStore"
+ "ApplePearlSEPDriver"
+ "AssertMacros: %s (value = 0x%lx), %s file: %s, line: %d\n"
+ "C1"
+ "C3"
+ "C4"
+ "C5"
+ "C6"
+ "C7"
+ "CFDataCreate sik_digest failed"
+ "CFPropertyListCreateData failed\n"
+ "CFPropertyListCreateData failed : %@\n"
+ "Calling pearl patch loading."
+ "Command"
+ "Command = %@\n"
+ "Content Length -- empty \n"
+ "Content Length Empty"
+ "Content-Length"
+ "Content-Type"
+ "Could not create proxy settings, system default proxy will be used."
+ "Couldn't create OS Log for 'com.apple.BiometricKit.Library-PearlFactory'!\n"
+ "Create xmlData failed, error: %@"
+ "Create xmlData failed."
+ "DataRef or responseDict is NULL."
+ "Disabling SSL validation"
+ "Error is empty"
+ "ErrorCode"
+ "ErrorCode is String Type"
+ "ErrorMessage"
+ "ErrorMessage - %@"
+ "ErrorString : %@\n"
+ "Exiting parse_response : %d"
+ "Fail to provision mesa: %i error: %@"
+ "Failed to create connection options dictionary.\n"
+ "Failed to create max attempts\n"
+ "Failed to create timeout\n"
+ "Failed to enable single sign on"
+ "Failed to get default AMAuthInstallRef"
+ "Failed to get mesa nonce with error %@"
+ "Failed to initialize personalization manager with error %@"
+ "Failed to set SEP nonce with error %d"
+ "Failed to set TATSU server URL with error %d"
+ "Failed to verify MSRk %@"
+ "HSCGetMesaNonce"
+ "HTTP Status == 200. OK\n"
+ "HTTP send error: %d\n"
+ "HorizonSeaCookieErrorDomain"
+ "IODeviceTree:/chosen"
+ "IOService:/IOResources/AppleKeyStore"
+ "Input argument req_dict is empty or NULL\n"
+ "Invalid Argument"
+ "Invalid Arguments"
+ "LTH SeaCookie not supported"
+ "Library-PearlFactory"
+ "Mesa Module serial number: %@"
+ "Mesa Nonce Size: %d"
+ "Mesa Nonce: %@"
+ "Mesa already paired and sealed"
+ "Mesa already paired using remote data"
+ "Mesa is unpaired"
+ "Mesa physical presence already asserted. Skip verify MSRk"
+ "Mesa sensor serial number: %@"
+ "MesaFactoryC seacookie message handling."
+ "ModuleStatus"
+ "No Error"
+ "Not supported."
+ "Output - Module Function = %@\n"
+ "POST"
+ "PairSensor"
+ "Payload = %@\n"
+ "PearlFactoryLib seacookie message handling."
+ "Physical presence is not cleared properly"
+ "Physical presence not reset"
+ "Processing Message  %@ --> %@"
+ "Protocol Version : %@"
+ "RePairingSessionKeyExchange"
+ "ReprovisionSensor"
+ "Request"
+ "Request Dictionary Creation failed\n"
+ "Request data is : %@\n"
+ "Reset physical presence"
+ "Resetting session\n"
+ "Response"
+ "Response Dictionary : %@\n"
+ "S5"
+ "S6"
+ "S7"
+ "SERVER RESPONSE is NULL\n"
+ "SIK"
+ "SIK : %@"
+ "SeaCookie server returned HTTP status: %ld\n"
+ "Send request status: %d http status: %ld error: %@\n"
+ "SensorChipID"
+ "SensorChipID : %@"
+ "SensorChipID: %@"
+ "SensorNonce"
+ "SensorNonce : %@"
+ "SensorSN"
+ "SensorSN: %@"
+ "SensorSNUM"
+ "SensorSNUM: %@"
+ "SensorType"
+ "SensorType : %@"
+ "SensorUID"
+ "SensorUID: %@"
+ "SepNonce"
+ "SepNonce : %@"
+ "Server did not return session cookie"
+ "Server returned an "
+ "ServerStatus"
+ "Session"
+ "SessionKeyExch"
+ "Setting custom tatsu server URL: %@"
+ "Signature = %@\n"
+ "Skip pairing pre-check"
+ "SpecVersion"
+ "TrustedAccessoryFactory seacookie message handling."
+ "UUID"
+ "Unable to create Error object\n"
+ "Unable to get Mesa Information"
+ "Unable to get Pearl Information"
+ "Unable to get current mesa provisioning state"
+ "Unable to get mesa nonce"
+ "Unable to get mesa provisioning state"
+ "Unable to get mesa serial number"
+ "Unable to parse response data from SeaCookie server\n"
+ "Unable to receive Module Information\n"
+ "Unable to relay response to SEP and obtain information \n"
+ "Unable to send/receive data with SeaCookie server\n"
+ "Unable to validate tatsu ticket"
+ "Unknown SeaCookie type"
+ "Unknown callback type."
+ "Validate tatsu ticket succeeded."
+ "Version"
+ "X-Apple-SeaCookie-IP"
+ "XML datalen: %lu data is : %@\n"
+ "^{__CFString=}24@?0r*8Q16"
+ "_HSCGetMesaInfo"
+ "_HSCGetModuleInfo"
+ "_HSCGetPearlInfo"
+ "_HSCHandleMesaMessage"
+ "_HSCHandleMessage"
+ "_HSCHandleMessage Failed"
+ "_HSCHandleMessage returned : %d"
+ "_HSCHandlePearlMessage"
+ "_HSCHandlePearlMessage_block_invoke"
+ "_HSCPairProxy"
+ "_HSCSeaCookieHandler"
+ "_HSCValidateTatsuTicket"
+ "_aks_operation"
+ "_connect != ((io_object_t) 0)"
+ "_merge_dict_cb"
+ "absoluteString"
+ "aks"
+ "aks-client-queue"
+ "aksStatus is %d"
+ "application/xml"
+ "appropriate command is not present"
+ "base64EncodedStringWithOptions:"
+ "buffer"
+ "bufferSize"
+ "callback"
+ "chip-id"
+ "code"
+ "connect"
+ "containsString:"
+ "could not create contentLengthStr\n"
+ "could not create httpRequest\n"
+ "createErrorWithUserInfo"
+ "createRequestData"
+ "dataWithBytes:length:"
+ "development-cert"
+ "enableSSO:"
+ "errorCode: 8302"
+ "errorCode: 8500"
+ "failed to open connection to %s: %d\n"
+ "failed to open userclient via %s: %d\n"
+ "getApTicketForSeaCookiePairingWithOptions:pairingTicket:error:"
+ "getClientAuth"
+ "getDefaultAMAuthInstallRef"
+ "getInnermostNSError:"
+ "getModuleSerialNumber -> err:0x%x\n"
+ "getModuleSerialNumber(%p, %p)\n"
+ "getSIKString"
+ "getSensorProvisioningState -> err:0x%x, state:%d\n"
+ "getSensorProvisioningState(%p)\n"
+ "getSensorSerialNumber -> err:0x%x\n"
+ "getSensorSerialNumber(%p, %p)\n"
+ "getSensorSerialNumber, retry: %d\n"
+ "i"
+ "i28@?0i8r*12Q20"
+ "inData"
+ "initWithAuthInstallObj:"
+ "initWithBytes:length:encoding:"
+ "inputData"
+ "inputData --> %@ inputSize --> %lu"
+ "intValue"
+ "isSSR"
+ "isUnlockRequired"
+ "localizedDescription"
+ "mesaInfo"
+ "mesaModuleSerialNumber"
+ "mesaSensorPhysicalPresenceState"
+ "mesaSensorPreviousPhysicalPresenceState"
+ "mesaSensorPreviousState"
+ "mesaSensorProvisioningState"
+ "mesaSensorSerialNumber"
+ "mesaStatus: %d Size: %d"
+ "moduleStatus = %d reply[%lu] \n"
+ "numberWithBool:"
+ "numberWithInt:"
+ "numberWithInteger:"
+ "numberWithUnsignedInt:"
+ "outConnect"
+ "parseResponse"
+ "pearlInfo"
+ "pearlSeaCookieHandleMessage %d %p %zu %p %p\n"
+ "pearlSeaCookieHandleMessage, type=%d -> 0x%x\n"
+ "pearlSeaCookieHandleMessage, type=%d reply[%zu] %.*P\n"
+ "pearlStatus: %d Size: %d"
+ "requestData : %@ responseData : %@"
+ "responseDict : %@"
+ "responseDict NULL. Unable to parse Response\n"
+ "result : %d"
+ "result = %d\n"
+ "seaCookieHandleMessage message[%zu] %.*P\n"
+ "seaCookieHandleMessage(type:%d) -> err:0x%x\n"
+ "seaCookieHandleMessage(type:%d, message:%p, messageLength:%zu, reply:%p, replySize:%p)\n"
+ "seaCookieHandleMessage, type=%d reply[%zu] %.*P\n"
+ "sendRequestSync"
+ "serviceName"
+ "shouldPersonalizeWithSSOByDefault"
+ "sign:keyBlob:"
+ "signature"
+ "sik_digest is NULL"
+ "sik_pub_key is NULL"
+ "sik_pub_key_len is 0"
+ "startPairing"
+ "unable to create a request \n"
+ "useProdMasterKey"
+ "warnings"
+ "x-intnt-apchipid"
+ "xmlData : %@"
+ "xmlData is not CFDictionary type."
```
