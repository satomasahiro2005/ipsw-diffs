## WebKitLegacy

> `/System/Library/PrivateFrameworks/WebKitLegacy.framework/WebKitLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3980` | `0x24e0` | **`-0x14a0`** |
| `__DATA_DIRTY.__objc_data` | `0xa50` | `0x1ef0` | **`+0x14a0`** |
| `__AUTH_CONST.__cfstring` | `0xf440` | `0xf540` | **`+0x100`** |
| `__TEXT.__cstring` | `0x1c6f4` | `0x1c683` | **`-0x71`** |
| `__TEXT.__text` | `0x166ed0` | `0x166e60` | **`-0x70`** |
| `__TEXT.__gcc_except_tab` | `0x13398` | `0x133c8` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x46d8` | `0x4700` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x1010` | `0x1020` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x52f8` | `0x5300` | **`+0x8`** |
| `__DATA.__bss` | `0x150` | `0x148` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x330` | `0x338` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x9608` | `0x9610` | **`+0x8`** |

### Other Changes

```diff

-625.1.20.10.3
+625.1.22.10.3

-  Functions: 7313
-  Symbols:   13071
-  CStrings:  2294
+  Functions: 7314
+  Symbols:   13077
+  CStrings:  2300
Symbols:
+ __ZN3WTF6Detail15CallableWrapperIZ27-[WebNotification finalize]E3$_5vJPN7WebCore12NotificationEEE4callES5_
+ __ZN3WTF6Detail15CallableWrapperIZ27-[WebNotification finalize]E3$_5vJPN7WebCore12NotificationEEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ27-[WebNotification finalize]E3$_5vJPN7WebCore12NotificationEEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZ36-[WebNotification dispatchShowEvent]E3$_1vJPN7WebCore12NotificationEEE4callES5_
+ __ZN3WTF6Detail15CallableWrapperIZ36-[WebNotification dispatchShowEvent]E3$_1vJPN7WebCore12NotificationEEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ36-[WebNotification dispatchShowEvent]E3$_1vJPN7WebCore12NotificationEEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchClickEvent]E3$_3vJPN7WebCore12NotificationEEE4callES5_
+ __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchClickEvent]E3$_3vJPN7WebCore12NotificationEEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchClickEvent]E3$_3vJPN7WebCore12NotificationEEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchCloseEvent]E3$_2vJPN7WebCore12NotificationEEE4callES5_
+ __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchCloseEvent]E3$_2vJPN7WebCore12NotificationEEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchCloseEvent]E3$_2vJPN7WebCore12NotificationEEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchErrorEvent]E3$_4vJPN7WebCore12NotificationEEE4callES5_
+ __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchErrorEvent]E3$_4vJPN7WebCore12NotificationEEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchErrorEvent]E3$_4vJPN7WebCore12NotificationEEED1Ev
+ __ZN7WebCore14scrollbarWidthERKNS_12RenderObjectE
+ __ZN7WebCore18WebSocketHandshake32setClientHandshakeRequestHeadersERKNS_13HTTPHeaderMapE
+ __ZN7WebCore39LegacyWebSocketInspectorInstrumentation32didSendWebSocketHandshakeRequestEPNS_8DocumentEN3WTF23ObjectIdentifierGenericINS_16WebSocketChannelENS3_38ObjectIdentifierThreadSafeAccessTraitsIyEEyEERKNS_15ResourceRequestE
+ __ZN7WebCore39LegacyWebSocketInspectorInstrumentation33willSendWebSocketHandshakeRequestEPNS_8DocumentEN3WTF23ObjectIdentifierGenericINS_16WebSocketChannelENS3_38ObjectIdentifierThreadSafeAccessTraitsIyEEyEERNS_15ResourceRequestE
+ __ZN7WebCore5Style11fontCascadeERKNS0_13ComputedStyleE
+ __ZN7WebCore5Style13DocumentScope30didChangeStyleSheetEnvironmentEv
+ __ZNK24WebResourceLoadScheduler14isBlockedErrorERKN7WebCore13ResourceErrorE
+ __ZNK7WebCore19ResourceRequestBase16httpHeaderFieldsEv
+ __ZTVN3WTF6Detail15CallableWrapperIZ27-[WebNotification finalize]E3$_5vJPN7WebCore12NotificationEEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZ36-[WebNotification dispatchShowEvent]E3$_1vJPN7WebCore12NotificationEEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchClickEvent]E3$_3vJPN7WebCore12NotificationEEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchCloseEvent]E3$_2vJPN7WebCore12NotificationEEEE
+ __ZTVN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchErrorEvent]E3$_4vJPN7WebCore12NotificationEEEE
- __ZN3WTF6Detail15CallableWrapperIZ27-[WebNotification finalize]E3$_4vJPN7WebCore12NotificationEEE4callES5_
- __ZN3WTF6Detail15CallableWrapperIZ27-[WebNotification finalize]E3$_4vJPN7WebCore12NotificationEEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZ27-[WebNotification finalize]E3$_4vJPN7WebCore12NotificationEEED1Ev
- __ZN3WTF6Detail15CallableWrapperIZ36-[WebNotification dispatchShowEvent]E3$_0vJPN7WebCore12NotificationEEE4callES5_
- __ZN3WTF6Detail15CallableWrapperIZ36-[WebNotification dispatchShowEvent]E3$_0vJPN7WebCore12NotificationEEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZ36-[WebNotification dispatchShowEvent]E3$_0vJPN7WebCore12NotificationEEED1Ev
- __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchClickEvent]E3$_2vJPN7WebCore12NotificationEEE4callES5_
- __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchClickEvent]E3$_2vJPN7WebCore12NotificationEEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchClickEvent]E3$_2vJPN7WebCore12NotificationEEED1Ev
- __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchCloseEvent]E3$_1vJPN7WebCore12NotificationEEE4callES5_
- __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchCloseEvent]E3$_1vJPN7WebCore12NotificationEEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchCloseEvent]E3$_1vJPN7WebCore12NotificationEEED1Ev
- __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchErrorEvent]E3$_3vJPN7WebCore12NotificationEEE4callES5_
- __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchErrorEvent]E3$_3vJPN7WebCore12NotificationEEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchErrorEvent]E3$_3vJPN7WebCore12NotificationEEED1Ev
- __ZN7WebCore39LegacyWebSocketInspectorInstrumentation33willSendWebSocketHandshakeRequestEPNS_8DocumentEN3WTF23ObjectIdentifierGenericINS_16WebSocketChannelENS3_38ObjectIdentifierThreadSafeAccessTraitsIyEEyEERKNS_15ResourceRequestE
- __ZN7WebCore5Style5Scope30didChangeStyleSheetEnvironmentEv
- __ZTVN3WTF6Detail15CallableWrapperIZ27-[WebNotification finalize]E3$_4vJPN7WebCore12NotificationEEEE
- __ZTVN3WTF6Detail15CallableWrapperIZ36-[WebNotification dispatchShowEvent]E3$_0vJPN7WebCore12NotificationEEEE
- __ZTVN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchClickEvent]E3$_2vJPN7WebCore12NotificationEEEE
- __ZTVN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchCloseEvent]E3$_1vJPN7WebCore12NotificationEEEE
- __ZTVN3WTF6Detail15CallableWrapperIZ37-[WebNotification dispatchErrorEvent]E3$_3vJPN7WebCore12NotificationEEEE
Functions:
~ __ZN28BinaryPropertyListSerializer13writeArrayEndEm : 592 -> 564
~ __ZN28BinaryPropertyListSerializer18writeDictionaryEndEm : 596 -> 568
~ __ZN18InProcessIDBServer25generateIndexKeyForRecordERKN7WebCore21IDBResourceIdentifierERKNS0_12IDBIndexInfoERKNSt3__18optionalIN5mpark7variantIJN3WTF6StringENSB_6VectorISC_Lm0ENSB_15CrashOnOverflowELm16ENSB_10FastMallocEEEEEEEERKNS0_10IDBKeyDataERKNS0_8IDBValueENS8_IxEE : 1388 -> 1412
~ __ZN18InProcessIDBServer33didGetAllDatabaseNamesAndVersionsERKN7WebCore21IDBResourceIdentifierEON3WTF6VectorINS0_25IDBDatabaseNameAndVersionELm0ENS4_15CrashOnOverflowELm16ENS4_10FastMallocEEE : 356 -> 352
~ __ZN6WebKit20StorageNamespaceImpl5closeEv : 360 -> 332
~ __ZN6WebKit20StorageNamespaceImpl4copyERN7WebCore4PageE : 1012 -> 992
~ __ZN6WebKit20StorageNamespaceImpl26clearAllOriginsForDeletionEv : 372 -> 340
~ __ZN6WebKit20StorageNamespaceImpl4syncEv : 276 -> 248
~ __ZN6WebKit20StorageNamespaceImpl30closeIdleLocalStorageDatabasesEv : 272 -> 244
~ __ZN6WebKit20StorageNamespaceImpl22setSessionIDForTestingEN3PAL9SessionIDE : 448 -> 424
~ __ZN3WTF37tryMakeStringImplFromAdaptersInternalIJNS_17StringTypeAdapterINS_6StringEEENS1_INS_12ASCIILiteralEEEEEENS_6RefPtrINS_10StringImplENS_12RawPtrTraitsIS7_EENS_21DefaultRefDerefTraitsIS7_EEEEjbDpT_ : 1736 -> 1732
~ __ZN3WTF6VectorIN7WebCore18SecurityOriginDataELm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEE14expandCapacityILNS_13FailureActionE0EEEbm : 476 -> 440
+ __ZNK24WebResourceLoadScheduler14isBlockedErrorERKN7WebCore13ResourceErrorE
~ __ZN24NetworkStorageSessionMap13ensureSessionEN3PAL9SessionIDERKN3WTF6StringE : 5352 -> 5336
~ __ZN7WebCore22SocketStreamHandleImplD2Ev : 740 -> 724
~ __ZN7WebCore16WebSocketChannel7connectERKN3WTF3URLERKNS1_6StringE : 2076 -> 2072
~ __ZN7WebCore16WebSocketChannel4failEON3WTF6StringE : 3540 -> 3536
~ __ZN7WebCore16WebSocketChannel19didOpenSocketStreamERNS_18SocketStreamHandleE : 904 -> 964
~ __ZN7WebCore15ResourceRequestaSEOS0_ : 784 -> 776
~ __ZN7WebCore13HTTPHeaderMapD2Ev : 288 -> 272
~ __ZN10PingHandle17timeoutTimerFiredEv : 452 -> 440
~ __ZN10PingHandle20willSendRequestAsyncEPN7WebCore14ResourceHandleEONS0_15ResourceRequestEONS0_16ResourceResponseEON3WTF17CompletionHandlerIFvS4_EEE : 952 -> 936
~ __ZN10PingHandle42canAuthenticateAgainstProtectionSpaceAsyncEPN7WebCore14ResourceHandleERKNS0_15ProtectionSpaceEON3WTF17CompletionHandlerIFvbEEE : 528 -> 516
~ __ZN3WTF28stringTypeAdapterAccumulatorIDsNS_17StringTypeAdapterINS_6StringEEEJS3_EEEvNSt3__14spanIT_Lm18446744073709551615EEET0_DpT1_ : 1128 -> 1116
~ __ZN3WTF37tryMakeStringImplFromAdaptersInternalIJNS_17StringTypeAdapterINS_12ASCIILiteralEEENS1_INS_6StringEEENS1_IcEES5_S6_EEENS_6RefPtrINS_10StringImplENS_12RawPtrTraitsIS8_EENS_21DefaultRefDerefTraitsIS8_EEEEjbDpT_ : 864 -> 860
~ __ZN3WTF37tryMakeStringImplFromAdaptersInternalIJNS_17StringTypeAdapterINS_12ASCIILiteralEEENS1_INS_6StringEEEEEENS_6RefPtrINS_10StringImplENS_12RawPtrTraitsIS7_EENS_21DefaultRefDerefTraitsIS7_EEEEjbDpT_ : 1568 -> 1552
+ __ZN3WTF6VectorIhLm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEEC2IKhLm18446744073709551615EEENSt3__14spanIT_XT0_EEE
- __ZN3WTF6VectorIhLm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEEC2IKhLm18446744073709551615EEENSt3__14spanIT_XT0_EEE
~ -[DOMNode(DOMNodeExtensions) lineBoxQuads] : 464 -> 448
~ -[DOMElement(WebPrivate) _font] : 1780 -> 1776
~ -[DOMAttr name] : 2580 -> 2576
~ -[DOMAttr ownerElement] : 124 -> 108
~ -[DOMHTMLImageElement altDisplayString] : 512 -> 504
~ -[DOMHTMLInputElement max] : 460 -> 452
~ -[DOMHTMLInputElement min] : 460 -> 452
~ -[DOMHTMLInputElement pattern] : 460 -> 452
~ -[DOMHTMLInputElement placeholder] : 460 -> 452
~ -[DOMHTMLInputElement step] : 460 -> 452
~ -[DOMHTMLInputElement defaultValue] : 460 -> 452
~ -[DOMHTMLInputElement altDisplayString] : 512 -> 504
~ -[DOMHTMLScriptElement htmlFor] : 460 -> 452
~ -[DOMHTMLScriptElement event] : 460 -> 452
~ -[DOMHTMLScriptElement charset] : 460 -> 452
~ -[DOMHTMLScriptElement type] : 460 -> 452
~ -[DOMHTMLScriptElement nonce] : 460 -> 452
~ __ZN3WTF6VectorIN7WebCore19MarkupExclusionRuleELm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEED1Ev : 296 -> 280
~ -[WebBackForwardList removeItem:] : 276 -> 284
~ -[WebPluginController webPlugInContainerLoadRequest:inFrame:] : 1000 -> 968
~ __ZL29makeFormFieldValuesDictionaryRN7WebCore9FormStateE : 476 -> 460
~ __ZN20WebFrameLoaderClient12createPluginERN7WebCore17HTMLPlugInElementERKN3WTF3URLERKNS3_6VectorINS3_10AtomStringELm0ENS3_15CrashOnOverflowELm16ENS3_10FastMallocEEESD_RKNS3_6StringEb : 2644 -> 2648
~ -[WebDataSource initWithRequest:] : 820 -> 824
~ -[WebFrame loadRequest:] : 912 -> 916
~ -[WebFrame _loadData:MIMEType:textEncodingName:baseURL:unreachableURL:] : 2892 -> 2916
~ -[WebHTMLView(WebInternal) _scrollbarWidthStyle] : 164 -> 128
~ -[WebView(WebPrivate) _cookieEnabled] : 52 -> 48
~ -[WebView(WebPrivate) _setCookieEnabled:] : 52 -> 56
~ -[WebView(WebPrivate) _touchEventRegions] : 688 -> 680
~ -[WebView(WebViewInternal) _getWebCoreDictationAlternatives:fromTextAlternatives:] : 244 -> 236
~ __ZN3WTF6VectorIN7WebCore20DictationAlternativeELm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEE14expandCapacityILNS_13FailureActionE0EEEPS2_mS8_ : 488 -> 472
~ __ZL18createNSCountedSetRKN3WTF14HashCountedSetINS_12ASCIILiteralENS_11DefaultHashIS1_EENS_10HashTraitsIS1_EEEE : 456 -> 416
~ -[WebDatabaseManager origins] : 500 -> 492
~ __ZN3WTF6VectorIN7WebCore18SecurityOriginDataELm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEED2Ev : 204 -> 196
~ -[WebHTMLRepresentation matchLabels:againstElement:] : 564 -> 548
~ __ZN3WTF13StringBuilder18appendFromAdaptersIJNS_17StringTypeAdapterINS_12ASCIILiteralEEES4_NS2_INS_6StringEEES4_EEEvDpRKT_ : 2716 -> 2704
~ __ZN3WTF6VectorIN7WebCore21InspectorOverlayLabelELm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEED1Ev : 412 -> 396
~ __ZN7WebCore25InspectorOverlayHighlightD2Ev : 932 -> 920
~ -[NSData(WebNSDataExtras) _webkit_guessedMIMETypeForXML] : 1112 -> 1100
~ -[NSData(WebNSDataExtras) _webkit_guessedMIMEType] : 1856 -> 1832
~ -[WebMainThreadInvoker forwardInvocation:] : 328 -> 304
~ -[NSInvocation(WebMainThreadInvoker) _webkit_invokeAndHandleException:] : 292 -> 284
~ __ZN3WTF6VectorI6CGRectLm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEE14expandCapacityILNS_13FailureActionE0EEEPS1_mS7_ : 432 -> 412
~ +[WebPreferences initialize] : 13156 -> 13216
~ +[WebPreferences(WebPrivateExperimentalFeatures) _experimentalFeatures] : 24768 -> 25016
~ -[WebStorageManager origins] : 500 -> 492
~ __ZN6WebKit27WebStorageNamespaceProvider35cloneSessionStorageNamespaceForPageERN7WebCore4PageES3_ : 1944 -> 1924
~ __ZN3WTF9HashTableIN7WebCore18SecurityOriginDataENS_12KeyValuePairIS2_NS_6RefPtrINS1_16StorageNamespaceENS_12RawPtrTraitsIS5_EENS_21DefaultRefDerefTraitsIS5_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS2_EENS_7HashMapIS2_SA_SF_NS_10HashTraitsIS2_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESI_SM_EC2ERKSP_ : 1280 -> 1240
~ _WebKitGetLastLineBreakInBuffer : 2068 -> 2140
~ __ZN3WTF20VectorTypeOperationsINS_17TextBreakIteratorEE4moveEPS1_S3_S3_ : 252 -> 244
~ __ZN7WebCore18BreakablePositions8classifyILNS0_14LineBreakRulesE0ELNS0_20NoBreakSpaceBehaviorE0EEENS0_10BreakClassEDs : 820 -> 872
~ __ZN3WTF30CachedLineBreakIteratorFactory3getEv : 3232 -> 3212
~ -[WebView(WebViewInternalPreferencesChangedGenerated) _preferencesChangedGenerated:] : 23952 -> 24056
CStrings:
+ "CSS calc-mix()"
+ "CSS ident() function"
+ "CSS object-view-box property"
+ "CSSCalcMixEnabled"
+ "CSSIdentFunctionEnabled"
+ "CSSObjectViewBoxEnabled"
+ "Enable Close Watcher API including dialog closedby attribute"
+ "Enable support for CSS calc-mix()"
+ "Enable support for CSS object-view-box property"
+ "Enable the CSS Values 5 ident() function"
+ "WebKitCSSCalcMixEnabled"
+ "WebKitCSSIdentFunctionEnabled"
+ "WebKitCSSObjectViewBoxEnabled"
+ "void _WebCreateFragment(WebCore::Document &, NSAttributedString *, WebCore::FragmentAndResources &)"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks/WebCore.framework/PrivateHeaders/StyleScrollbarWidth.h"
- "ClosedbyAttributeEnabled"
- "Enable Close Watcher API"
- "Enable HTML closedby attribute support"
- "HTML closedby attribute"
- "WebCore::ScrollbarWidth WebCore::Style::ToPlatform<WebCore::Style::ScrollbarWidth>::operator()(ScrollbarWidth)"
- "WebKitClosedbyAttributeEnabled"
- "void _WebCreateFragment(Document &, NSAttributedString *, FragmentAndResources &)"
```
