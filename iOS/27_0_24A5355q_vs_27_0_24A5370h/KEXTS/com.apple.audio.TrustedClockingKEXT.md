## com.apple.audio.TrustedClockingKEXT

> `com.apple.audio.TrustedClockingKEXT`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xb960` | `0xc2f4` | **`+0x994`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x500` | **`+0x500`** |
| `__TEXT.__cstring` | `0x2fe9` | `0x31ae` | **`+0x1c5`** |
| `__DATA_CONST.__const` | `0x1728` | `0x18d0` | **`+0x1a8`** |
| `__DATA_CONST.__kalloc_type` | `0xc0` | `0x80` | **`-0x40`** |
| `__DATA.__common` | `0x88` | `0x60` | **`-0x28`** |
| `__DATA_CONST.__auth_got` | `0x298` | `0x280` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x50` | `0x40` | **`-0x10`** |
| `__DATA_CONST.__mod_init_func` | `0x18` | `0x10` | **`-0x8`** |
| `__DATA_CONST.__mod_term_func` | `0x18` | `0x10` | **`-0x8`** |

### Other Changes

```diff

-87.1.31.0.0
-  Functions: 435
+92.30.0.0.0
+  Functions: 446

-  CStrings:  154
+  CStrings:  139
CStrings:
+ "121111121222121211111111112211222112221122211222112221122211222112221122211222112221122211222112221122211211112111121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121121121121111211211211211222222111112111121111122222222222222222222222222222222222222222222222222222222222222222121121211111"
+ "KernelCourierWorker::drain - sendMessage failed: %d for useCaseId %u\n"
+ "KernelCourierWorker::isUseCaseReady - Courier not initialized for useCaseId %u\n"
+ "KernelCourierWorker::isUseCaseReady - No state for useCaseId %u\n"
+ "KernelCourierWorker::sendTransactionToUseCase - ring full for useCaseId %u\n"
+ "TrustedClockingKEXT::start - Failed to start impl\n"
+ "TrustedClockingKEXTImpl::processKernelWorkloop [%u] - Exiting\n"
+ "TrustedClockingKEXTImpl::registerUseCaseState - add failed for useCaseId %u\n"
+ "TrustedClockingKEXTImpl::registerUseCaseState - registered useCaseId %u\n"
+ "TrustedClockingKEXTImpl::start - Failed to initialize courier worker\n"
+ "TrustedClockingKEXTImpl::startKernelWorkloop - No state for useCaseID %u\n"
+ "TrustedClockingKEXTImpl::startKernelWorkloop [%u] - PM notify failed\n"
+ "TrustedClockingKEXTImpl::startKernelWorkloop [%u] - failed to signal start\n"
+ "TrustedClockingKEXTImpl::stopKernelWorkloop - No state for useCaseID %u\n"
+ "TrustedClockingKEXTImpl::stopKernelWorkloop [%u] - PM notify failed\n"
+ "TrustedClockingKEXTImpl::stopKernelWorkloop [%u] - stop failed\n"
+ "TrustedClockingKEXTImpl::triggerWorkloopDataAvailability - No state for useCaseID %u\n"
+ "v16@?0^{TrustedClockingWorkloopContext={TightbeamServicesContainer=^^?{TightbeamModulusService=^^?B{coreaudiomodulus_coreaudiomodulusservice_s=^{tb_connection_s}}}{TightbeamDeviceService=^^?B{coreaudiodevice_coreaudiodevicetransportservice_s=^{tb_connection_s}}}{TightbeamCourierService=^^?B{coreaudiocourier_coreaudiocouriermessageservice_s=^{tb_connection_s}}}}{TrustedClockingKernelUtilities=^^?}{TrustedClockingSemaphore=^^?^{semaphore}B}{TrustedClockingSemaphore=^^?^{semaphore}B}{TrustedClockingSemaphore=^^?^{semaphore}B}{TrustedClockingSemaphore=^^?^{semaphore}B}{TrustedClockingMutex=^^?^{_IOLock}}{WorkloopSetup=QIQQQI}^{KernelSemaphore}^{KernelSemaphore}^{KernelSemaphore}^{KernelSemaphore}^{KernelMutex}ABABAB^{ServicesContainer}^{KernelUtilities}}8"
+ "v16@?0^{WorkloopContext={WorkloopSetup=QIQQQI}^{KernelSemaphore}^{KernelSemaphore}^{KernelSemaphore}^{KernelSemaphore}^{KernelMutex}ABABAB^{ServicesContainer}^{KernelUtilities}}8"
- "121111121222121211111222222222222222222222222222222222222222222222222222222222222222222121121111111111112222222222222222222222222222222222222222222222222"
- "12112112112112112112112111122222211111211"
- "TrustedClockingKEXT: sendTransactionToUseCase - ring full for use case %u\n"
- "TrustedClockingKEXT: sendTransactionToUseCase invalid for use case %u\n"
- "TrustedClockingKEXT::initCourierWorker - Failed to allocate queue lock\n"
- "TrustedClockingKEXT::initCourierWorker - Failed to allocate thread_call\n"
- "TrustedClockingKEXT::processCourierQueue - Courier not initialized for use case %u\n"
- "TrustedClockingKEXT::processCourierQueue - No state for use case %u\n"
- "TrustedClockingKEXT::processCourierQueue - messagearrived failed: %d for use case %u\n"
- "TrustedClockingKEXT::processKernelWorkloop [%u] - Exiting\n"
- "TrustedClockingKEXT::registerUseCaseState - Workloop state already registered for usecase %u\n"
- "TrustedClockingKEXT::registerUseCaseState - unable to create workloop state for use case ID %u\n"
- "TrustedClockingKEXT::setupKernelWorkloop - registered useCaseID %u\n"
- "TrustedClockingKEXT::start - Allocated workloop arrays \n"
- "TrustedClockingKEXT::start - Failed to allocate workloop states array\n"
- "TrustedClockingKEXT::start - Failed to initialize courier worker\n"
- "TrustedClockingKEXT::startKernelWorkloop - No registered state for useCaseID %u\n"
- "TrustedClockingKEXT::startKernelWorkloop [%u] - failed to notify PM state machine start\n"
- "TrustedClockingKEXT::startKernelWorkloop [%u] - failed to signal start\n"
- "TrustedClockingKEXT::startKernelWorkloop [%u] - start signal sent\n"
- "TrustedClockingKEXT::stop - All workloops exited\n"
- "TrustedClockingKEXT::stop - Released workloop states array\n"
- "TrustedClockingKEXT::stop - Signaling workloop %u to exit\n"
- "TrustedClockingKEXT::stop - WARNING: Errors waiting for workloops to exit\n"
- "TrustedClockingKEXT::stopKernelWorkloop - Error stopping workloop! %u\n"
- "TrustedClockingKEXT::stopKernelWorkloop - Signaled workloop to stop for useCaseID %u, waiting for exit...\n"
- "TrustedClockingKEXT::stopKernelWorkloop - State not found while stopping workloop! %u\n"
- "TrustedClockingKEXT::stopKernelWorkloop [%u] - failed to notify PM state machine stop\n"
- "TrustedClockingKEXT::triggerWorkloopDataAvailability - No state found for useCaseID %u\n"
- "WorkloopStateObject"
- "WorkloopStateObject::createWithSetup - failed to initialize workloop context\n"
- "WorkloopStateObject::createWithSetup - unable to initialize WorkloopStateObject\n"
- "WorkloopStateObject::init - unable to initialize OSObject\n"
- "site.WorkloopStateObject"
```
