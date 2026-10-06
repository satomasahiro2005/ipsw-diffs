## BoardServices

> `/System/Library/PrivateFrameworks/BoardServices.framework/BoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b284` | `0x7eef8` | **`+0x3c74`** |
| `__TEXT.__cstring` | `0x6d0e` | `0x7804` | **`+0xaf6`** |
| `__AUTH_CONST.__cfstring` | `0x56e0` | `0x5ba0` | **`+0x4c0`** |
| `__AUTH_CONST.__objc_const` | `0x6218` | `0x6650` | **`+0x438`** |
| `__TEXT.__gcc_except_tab` | `0xb338` | `0xb764` | **`+0x42c`** |
| `__TEXT.__objc_methlist` | `0x2424` | `0x255c` | **`+0x138`** |
| `__TEXT.__unwind_info` | `0x2940` | `0x2a48` | **`+0x108`** |
| `__AUTH.__objc_data` | `0x2f0` | `0x3e0` | **`+0xf0`** |
| `__AUTH.__data` | `0x350` | `0x410` | **`+0xc0`** |
| `__DATA.__data` | `0x1550` | `0x1610` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0xe30` | `0xec8` | **`+0x98`** |
| `__AUTH_CONST.__const` | `0x1d78` | `0x1df8` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1358` | `0x13d8` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x1398` | `0x13e8` | **`+0x50`** |
| `__DATA_DIRTY.__bss` | `0x110` | `0x148` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x598` | `0x5c8` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x49c` | `0x4c4` | **`+0x28`** |
| `__TEXT.__const` | `0x19b8` | `0x19d8` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x1b8` | `0x1d0` | **`+0x18`** |
| `__AUTH_CONST.__weak_auth_got` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x1e0` | `0x1f0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x140` | `0x150` | **`+0x10`** |
| `__DATA_DIRTY.__objc_ivar` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x1c10` | `0x1c08` | **`-0x8`** |

### Other Changes

```diff

-821.0.0.0.0
+825.0.0.0.0

+  - /usr/lib/libc++.1.dylib

-  Functions: 1876
-  Symbols:   2736
-  CStrings:  952
+  Functions: 1923
+  Symbols:   2858
+  CStrings:  1007
Symbols:
+ +[BSServiceConnectionCalloutType typeForBSXPCServiceCalloutType:]
+ +[BSXPCServiceConnectionProxy proxyForConnection:handshake:withProtocol:activationGeneration:activeXPCConnection:xpcConnectionTargetQueue:replyQueue:replyCalloutContext:replyCalloutContextSetupBlock:replyCalloutContextTeardownBlock:target:attributes:assertionProvider:]
+ -[BSServiceConnectionCalloutContextualizer .cxx_destruct]
+ -[BSServiceConnectionCalloutContextualizer setSetupBlock:]
+ -[BSServiceConnectionCalloutContextualizer setTeardownBlock:]
+ -[BSServiceConnectionCalloutContextualizer setupBlock]
+ -[BSServiceConnectionCalloutContextualizer teardownBlock]
+ -[BSServiceConnectionCalloutType description]
+ -[BSServiceConnectionCalloutType isForLifecycle]
+ -[BSServiceConnectionCalloutType isForMessagingReply]
+ -[BSServiceConnectionCalloutType isForMessaging]
+ -[_BSServiceConnectionConfiguration setCalloutContextualizer:]
+ -[_BSServiceMainThreadBlockDispatcherQueue .cxx_destruct]
+ -[_BSServiceMainThreadBlockDispatcherQueue _initWithDispatcher:]
+ -[_BSServiceMainThreadBlockDispatcherQueue _performAsync:withHandoff:]
+ -[_BSServiceMainThreadBlockDispatcherQueue assertBarrierOnQueue]
+ -[_BSServiceMainThreadBlockDispatcherQueue dealloc]
+ -[_BSServiceMainThreadBlockDispatcherQueue description]
+ -[_BSServiceMainThreadBlockDispatcherQueue isEqual:]
+ -[_BSServiceMainThreadBlockDispatcherQueue performAfter:withBlock:]
+ -[_BSServiceMainThreadBlockDispatcherQueue performAsync:]
+ GCC_except_table72
+ GCC_except_table84
+ GCC_except_table85
+ GCC_except_table87
+ GCC_except_table91
+ GCC_except_table92
+ GCC_except_table93
+ _BSServiceBlockDispatcherEnqueueBlock
+ _BSServiceBlockDispatcherGetTypeID
+ _BSServiceMachHoistCreateBlockDispatcher
+ _BSServiceMachHoistDequeueBlocks
+ _BSServiceMachHoistDrainBlocks
+ _BSServiceMachHoistGetNotifyPort
+ _BSServiceMachHoistGetTypeID
+ _BSServiceMachHoistInvalidate
+ _BSServiceMainThreadMachHoistCreate
+ _BSServiceQueueForMachHoist
+ _CFGetTypeID
+ _CFRetain
+ _OBJC_CLASS_$_BSServiceConnectionCalloutContextualizer
+ _OBJC_CLASS_$_BSServiceConnectionCalloutType
+ _OBJC_CLASS_$__BSServiceMainThreadBlockDispatcherQueue
+ _OBJC_IVAR_$_BSServiceConnectionCalloutContextualizer._setupBlock
+ _OBJC_IVAR_$_BSServiceConnectionCalloutContextualizer._teardownBlock
+ _OBJC_IVAR_$_BSServiceConnectionCalloutType._underlying
+ _OBJC_IVAR_$_BSXPCServiceConnectionEventHandler._calloutContextSetupBlock
+ _OBJC_IVAR_$_BSXPCServiceConnectionEventHandler._calloutContextTeardownBlock
+ _OBJC_IVAR_$_BSXPCServiceConnectionEventHandler._customCalloutContext
+ _OBJC_IVAR_$_BSXPCServiceConnectionProxy._replyCalloutContext
+ _OBJC_IVAR_$_BSXPCServiceConnectionProxy._replyCalloutContextSetupBlock
+ _OBJC_IVAR_$_BSXPCServiceConnectionProxy._replyCalloutContextTeardownBlock
+ _OBJC_IVAR_$__BSServiceConnectionConfiguration._calloutContextSetupBlock
+ _OBJC_IVAR_$__BSServiceConnectionConfiguration._calloutContextTeardownBlock
+ _OBJC_METACLASS_$_BSServiceConnectionCalloutContextualizer
+ _OBJC_METACLASS_$_BSServiceConnectionCalloutType
+ _OBJC_METACLASS_$__BSServiceMainThreadBlockDispatcherQueue
+ __CFRuntimeCreateInstance
+ __CFRuntimeRegisterClass
+ __OBJC_$_INSTANCE_METHODS_BSServiceConnectionCalloutContextualizer
+ __OBJC_$_INSTANCE_METHODS_BSServiceConnectionCalloutType
+ __OBJC_$_INSTANCE_METHODS__BSServiceMainThreadBlockDispatcherQueue
+ __OBJC_$_INSTANCE_VARIABLES_BSServiceConnectionCalloutContextualizer
+ __OBJC_$_INSTANCE_VARIABLES_BSServiceConnectionCalloutType
+ __OBJC_$_INSTANCE_VARIABLES__BSServiceMainThreadBlockDispatcherQueue
+ __OBJC_$_PROP_LIST_BSServiceConnectionCalloutContextualizer
+ __OBJC_$_PROP_LIST_BSServiceConnectionCalloutType
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BSServiceConnectionCalloutType
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BSServiceConnectionConfiguring_CalloutContextualizing
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BSServiceConnectionCalloutType
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BSServiceConnectionConfiguring_CalloutContextualizing
+ __OBJC_$_PROTOCOL_REFS_BSServiceConnectionConfiguring_CalloutContextualizing
+ __OBJC_CLASS_PROTOCOLS_$_BSServiceConnectionCalloutType
+ __OBJC_CLASS_RO_$_BSServiceConnectionCalloutContextualizer
+ __OBJC_CLASS_RO_$_BSServiceConnectionCalloutType
+ __OBJC_CLASS_RO_$__BSServiceMainThreadBlockDispatcherQueue
+ __OBJC_LABEL_PROTOCOL_$_BSServiceConnectionCalloutType
+ __OBJC_LABEL_PROTOCOL_$_BSServiceConnectionConfiguring_CalloutContextualizing
+ __OBJC_METACLASS_RO_$_BSServiceConnectionCalloutContextualizer
+ __OBJC_METACLASS_RO_$_BSServiceConnectionCalloutType
+ __OBJC_METACLASS_RO_$__BSServiceMainThreadBlockDispatcherQueue
+ __OBJC_PROTOCOL_$_BSServiceConnectionCalloutType
+ __OBJC_PROTOCOL_$_BSServiceConnectionConfiguring_CalloutContextualizing
+ __ZL11_hoist_pingP20__BSServiceMachHoist
+ __ZL13invoke_blocksP20__BSServiceMachHoistb
+ __ZL25__BSServiceMachHoistClass
+ __ZL27_BSServiceMachHoistFinalizePKv
+ __ZL28_hoist_deregister_dispatcherP20__BSServiceMachHoist
+ __ZL31__BSServiceBlockDispatcherClass
+ __ZL33_BSServiceBlockDispatcherFinalizePKv
+ __ZNSt20bad_array_new_lengthC1Ev
+ __ZNSt20bad_array_new_lengthD1Ev
+ __ZNSt3__114__split_bufferIPU13block_pointerFvvENS_9allocatorIS3_EEE12emplace_backIJRS3_EEEvDpOT_
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIPU13block_pointerFvvEEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
+ __ZNSt3__15dequeIU13block_pointerFvvENS_9allocatorIS2_EEE19__add_back_capacityEv
+ __ZNSt3__15dequeIU13block_pointerFvvENS_9allocatorIS2_EEED2B9fqe220106Ev
+ __ZNSt3__15mutex4lockEv
+ __ZNSt3__15mutex6unlockEv
+ __ZNSt3__15mutexD1Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZTISt20bad_array_new_length
+ __ZdlPv
+ __ZnwmSt19__type_descriptor_t
+ ___269+[BSXPCServiceConnectionProxy proxyForConnection:handshake:withProtocol:activationGeneration:activeXPCConnection:xpcConnectionTargetQueue:replyQueue:replyCalloutContext:replyCalloutContextSetupBlock:replyCalloutContextTeardownBlock:target:attributes:assertionProvider:]_block_invoke
+ ___57-[_BSServiceMainThreadBlockDispatcherQueue performAsync:]_block_invoke
+ ___62-[_BSServiceConnectionConfiguration setCalloutContextualizer:]_block_invoke
+ ___62-[_BSServiceConnectionConfiguration setCalloutContextualizer:]_block_invoke_2
+ ___65+[BSServiceConnectionCalloutType typeForBSXPCServiceCalloutType:]_block_invoke
+ ___67-[_BSServiceMainThreadBlockDispatcherQueue performAfter:withBlock:]_block_invoke
+ ___BSServiceBlockDispatcherGetTypeID_block_invoke
+ ___BSServiceMachHoistGetTypeID_block_invoke
+ ____ZL28_hoist_deregister_dispatcherP20__BSServiceMachHoist_block_invoke
+ ___block_descriptor_40_ea8_32bs_e11_v20?0i812ls32l8
+ ___block_descriptor_40_ea8_32bs_e8_12?0i8ls32l8
+ ___block_descriptor_89_e8_32o40o48o56o64b72b80b_e51_v24?0"BSXPCServiceConnectionMessage"8"NSError"16ls32l8s64l8s40l8s48l8s56l8s72l8s80l8
+ ___cxa_allocate_exception
+ ___cxa_throw
+ ___gxx_personality_v0
+ __os_assert_log
+ __os_crash
+ _mach_msg
+ _mach_port_construct
+ _mach_port_deallocate
+ _mach_port_destruct
+ _mach_task_self_
+ _pthread_main_np
+ _typeForBSXPCServiceCalloutType:.onceToken
+ _voucher_mach_msg_clear
+ _voucher_mach_msg_set
- +[BSXPCServiceConnectionProxy proxyForConnection:handshake:withProtocol:activationGeneration:activeXPCConnection:xpcConnectionTargetQueue:replyQueue:target:attributes:assertionProvider:]
- -[BSXPCServiceConnection _eventHandler]
- GCC_except_table94
- _OBJC_IVAR_$_BSXPCServiceConnectionEventHandler._calloutContext
- ___186+[BSXPCServiceConnectionProxy proxyForConnection:handshake:withProtocol:activationGeneration:activeXPCConnection:xpcConnectionTargetQueue:replyQueue:target:attributes:assertionProvider:]_block_invoke
- ___block_descriptor_65_e8_32o40o48o56b_e51_v24?0"BSXPCServiceConnectionMessage"8"NSError"16ls32l8s56l8s40l8s48l8
- _objc_exception_throw
CStrings:
+ "%@ <%@:%p> Encoding of %@ in <%@> failed: %@ -> (\n%@\n)"
+ "(unknown: %i)"
+ "+[BSXPCServiceConnectionProxy proxyForConnection:handshake:withProtocol:activationGeneration:activeXPCConnection:xpcConnectionTargetQueue:replyQueue:replyCalloutContext:replyCalloutContextSetupBlock:replyCalloutContextTeardownBlock:target:attributes:assertionProvider:]"
+ "@12@?0i8"
+ "BSServiceBlockDispatcher"
+ "BSServiceBlockDispatcherRef  _Nonnull BSServiceMachHoistCreateBlockDispatcher(CFAllocatorRef _Nullable, BSServiceMachHoistRef _Nonnull)"
+ "BSServiceMachHoist"
+ "BSServiceMachHoist.mm"
+ "BSServiceQueue * _Nonnull BSServiceQueueForMachHoist(BSServiceMachHoistRef _Nonnull)"
+ "Error encoding reply block for %@: %@ -> (\n%@\n)"
+ "Error encoding return error from %@: %@ -> (\n%@\n)"
+ "Error encoding return value from %@: %@ -> (\n%@\n)"
+ "Exception thrown while invoking -[%@ %@]: %@ -> (\n%@\n)"
+ "Exception thrown while invoking environment setup block for %@ with %@ -> (\n%@\n)"
+ "Exception thrown while invoking environment teardown block for %@ with %@ -> (\n%@\n)"
+ "_BSServiceMainThreadBlockDispatcherQueue"
+ "_hoist_ping"
+ "attempt to invoke blocks after invalidation"
+ "bool _hoist_register_dispatcher(BSServiceMachHoistRef)"
+ "bool invoke_blocks(BSServiceMachHoistRef, bool)"
+ "calloutContextSetupBlock for %@ stashed info with no teardownBlock to clean it up : stashed=%@"
+ "calloutContextualizer"
+ "cannot deregister a dispatcher after invalidation"
+ "cannot deregister because there are no extant registrations"
+ "cannot register a dispatcher after invalidation"
+ "cf != nullptr"
+ "dispatcher"
+ "dispatcher != ((void*)0)"
+ "dispatcher != nullptr"
+ "dispatcher (%@) is of an unknown class"
+ "err == KERN_SUCCESS"
+ "failure to find context to execute call out : param=%@ connection=%@ (%@)"
+ "hoist != nullptr"
+ "hoist is not quescent: there are still enqueued blocks"
+ "hoist is not quescent: there are still valid dispatchers"
+ "hoist is not quescent: there is still an outstanding ping to the notifyPort"
+ "lifecycle"
+ "message"
+ "must be called on the main thread"
+ "not invalidated before dealloc"
+ "reply"
+ "scheduling"
+ "setCalloutContextualizer: called outside of configurator"
+ "somehow still scheduled after invalidation"
+ "somehow we have blocks without being scheduled"
+ "there are blocks still waiting to be dequeued"
+ "there are no dispatchers capable of enqueuing blocks"
+ "there are still valid dispatchers"
+ "there are too many dispatchers capable of enqueuing blocks"
+ "there should not be any dispatchers capable of enqueuing blocks after invalidation"
+ "threading violation: not on the main thread"
+ "too many calls to BSServiceMachHoistDequeueBlocks"
+ "unknown callout type: %i"
+ "v20@?0i8@12"
+ "void BSServiceBlockDispatcherEnqueueBlock(BSServiceBlockDispatcherRef _Nonnull, void (^ _Nonnull)())"
+ "void BSServiceMachHoistInvalidate(BSServiceMachHoistRef _Nonnull)"
+ "void BSXPCServiceConnectionExecuteCallOut(BSXPCServiceConnection *const __strong _Nonnull, __strong id _Nonnull, enum BSXPCServiceCalloutType, BSXPCServiceCalloutContextSetupBlock  _Nullable const __strong, BSXPCServiceCalloutContextTeardownBlock  _Nullable const __strong, const __strong dispatch_block_t _Nonnull)"
+ "void _BSServiceBlockDispatcherFinalize(CFTypeRef)"
+ "void _BSServiceMachHoistFinalize(CFTypeRef)"
+ "void _hoist_deregister_dispatcher(BSServiceMachHoistRef)"
+ "void _hoist_enqueue(BSServiceMachHoistRef, bool, void (^)())"
- "%@ <%@:%p> Encoding of %@ in <%@> failed: %@ -> %@"
- "Error encoding reply block for %@: %@ -> %@"
- "Error encoding return error from %@: %@ -> %@"
- "Error encoding return value from %@: %@ -> %@"
- "failure to find context to execute call out : param=%@ connection=%@ eventHandler=%@ (%@)"
- "void BSXPCServiceConnectionExecuteCallOut(BSXPCServiceConnection *const __strong _Nonnull, __strong id _Nullable, const __strong dispatch_block_t _Nonnull)"
```
