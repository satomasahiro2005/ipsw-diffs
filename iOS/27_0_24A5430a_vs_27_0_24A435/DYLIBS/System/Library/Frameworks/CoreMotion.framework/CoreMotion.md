## CoreMotion

> `/System/Library/Frameworks/CoreMotion.framework/CoreMotion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b6ba0` | `0x3ce334` | **`+0x17794`** |
| `__TEXT.__oslogstring` | `0x2d273` | `0x2f686` | **`+0x2413`** |
| `__TEXT.__cstring` | `0x459ba` | `0x47503` | **`+0x1b49`** |
| `__AUTH_CONST.__objc_const` | `0x1caa8` | `0x1db18` | **`+0x1070`** |
| `__TEXT.__gcc_except_tab` | `0xc9e4` | `0xd458` | **`+0xa74`** |
| `__AUTH_CONST.__const` | `0x14f60` | `0x15810` | **`+0x8b0`** |
| `__TEXT.__objc_methlist` | `0xd0e4` | `0xd854` | **`+0x770`** |
| `__TEXT.__const` | `0xc690` | `0xcc90` | **`+0x600`** |
| `__TEXT.__unwind_info` | `0xb658` | `0xbc50` | **`+0x5f8`** |
| `__AUTH_CONST.__cfstring` | `0x136e0` | `0x13c00` | **`+0x520`** |
| `__AUTH.__objc_data` | `0x3f20` | `0x4290` | **`+0x370`** |
| `__DATA_CONST.__const` | `0x3a08` | `0x3d60` | **`+0x358`** |
| `__DATA_CONST.__objc_selrefs` | `0x5480` | `0x56a0` | **`+0x220`** |
| `__DATA.__objc_ivar` | `0x16e8` | `0x1798` | **`+0xb0`** |
| `__DATA_CONST.__objc_classlist` | `0x880` | `0x8d8` | **`+0x58`** |
| `__DATA_CONST.__objc_superrefs` | `0x770` | `0x7c0` | **`+0x50`** |
| `__DATA_DIRTY.__bss` | `0x10a0` | `0x10e0` | **`+0x40`** |
| `__DATA_DIRTY.__objc_ivar` | `0x180` | `0x1c0` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1490` | `0x14c0` | **`+0x30`** |
| `__DATA.__common` | `0xf8` | `0x128` | **`+0x30`** |
| `__DATA.__data` | `0xde8` | `0xe18` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x7e8` | `0x818` | **`+0x30`** |
| `__AUTH_CONST.__objc_intobj` | `0x270` | `0x288` | **`+0x18`** |

### Other Changes

```diff

-  Functions: 12333
-  Symbols:   1776
-  CStrings:  11105
+  Functions: 12679
+  Symbols:   1811
+  CStrings:  11394
Symbols:
+ _CMDeviceStateEventPropertyA0Key
+ _CMDeviceStateEventPropertyA1Key
+ _CMDeviceStateEventPropertyAKey
+ _CMDeviceStateEventPropertyBKey
+ _CMDeviceStateEventPropertyCKey
+ _CMDeviceStateEventPropertyDKey
+ _CMDeviceStateEventSendNotification
+ _CMFlipEventReasonKey
+ _CMFlipEventSendNotification
+ _CMFlipEventStateKey
+ _CMFlipManagerClientID
+ _CMFlipManagerClientType
+ _CMFlipServiceEnable
+ _IOHIDEventCreateHingeAngleEvent
+ _IOHIDEventCreateVendorDefinedEvent
+ _IOHIDEventGetDoubleValue
+ _IOHIDEventGetEvent
+ _IOHIDEventGetPhase
+ _IOHIDEventGetTimeStampOfType
+ _OBJC_CLASS_$_CMAngle
+ _OBJC_CLASS_$_CMAngleManager
+ _OBJC_CLASS_$_CMDeviceStateEvent
+ _OBJC_CLASS_$_CMDeviceStateManager
+ _OBJC_CLASS_$_CMFactoryAngle
+ _OBJC_CLASS_$_CMFactoryAngleManager
+ _OBJC_CLASS_$_CMFlipEvent
+ _OBJC_CLASS_$_CMFlipManager
+ _OBJC_METACLASS_$_CMAngle
+ _OBJC_METACLASS_$_CMAngleManager
+ _OBJC_METACLASS_$_CMDeviceStateEvent
+ _OBJC_METACLASS_$_CMDeviceStateManager
+ _OBJC_METACLASS_$_CMFactoryAngle
+ _OBJC_METACLASS_$_CMFactoryAngleManager
+ _OBJC_METACLASS_$_CMFlipEvent
+ _OBJC_METACLASS_$_CMFlipManager
CStrings:
+ "%@ flipState:%@ flipReason:%@ timestamp: %.6f timestampContinuous: %.6f"
+ "%@ propertyA:%@ propertyA0:%@ propertyA1:%@ propertyB:%@ propertyC:%@ propertyD:%@ timestamp:%f timestampContinuous:%f"
+ "%@:%@"
+ "%{public}s calling setAngleHandler:%{public}p interval:%{public}f"
+ "%{public}s calling setFactoryAngleHandler:%{public}p"
+ "%{signpost.description:begin_time}llu"
+ "%{signpost.description:begin_time}llu %{signpost.description:end_time}llu"
+ "%{signpost.description:end_time}llu"
+ "+[CMDeviceStateEvent propertyAForConfigType:propertyA:propertyB:propertyC:]"
+ "+[CMDeviceStateManager computeDeviceStateEventForPropertyA:propertyA0:propertyA1:angle:propertyC:timestamp:continuousTimestamp:]"
+ "+[CMFactoryAngleManager isAvailable]"
+ "-[CMAngleManager setAngleHandler:interval:]"
+ "-[CMAngleManagerInternal cancelPendingAngleUpdate]"
+ "-[CMAngleManagerInternal isAngleActive]"
+ "-[CMAngleManagerInternal notifyAngleChange:]"
+ "-[CMAngleManagerInternal onAngleChange:]"
+ "-[CMAngleManagerInternal scheduleAngleUpdate]_block_invoke"
+ "-[CMAngleManagerInternal setAngleUpdateIntervalPrivate:]"
+ "-[CMAngleManagerInternal startAngleUpdatesPrivateToQueue:handler:]"
+ "-[CMAngleManagerInternal stopAngleUpdatesPrivate]"
+ "-[CMDeviceStateManager feedDeviceStateEvent:propertyA0Type:propertyA1Type:propertyBType:propertyCType:propertyDType:timestamp:continuousTimestamp:timestampAPArrivalSecs:]_block_invoke"
+ "-[CMDeviceStateManager initWithName:]"
+ "-[CMDeviceStateManager onDeviceStateData:]"
+ "-[CMDeviceStateManager onNotification:]_block_invoke"
+ "-[CMDeviceStateManager queryDeviceStateBlocking]"
+ "-[CMDeviceStateManager queryDeviceStateWithHandler:]"
+ "-[CMDeviceStateManager sendEventToClientPrivate]"
+ "-[CMDeviceStateManager startUpdatesPrivateToQueue:withHandler:]"
+ "-[CMDeviceStateManager startUpdatesToQueue:withHandler:]_block_invoke"
+ "-[CMDeviceStateManager stopUpdatesPrivate]"
+ "-[CMFactoryAngleManager setFactoryAngleHandler:]"
+ "-[CMFlipManager connect]_block_invoke"
+ "-[CMFlipManager feedFlipEvent:reason:timestamp:continuousTimestamp:]"
+ "-[CMFlipManager initWithName:]"
+ "-[CMFlipManager onDistributedNotification:]_block_invoke"
+ "-[CMFlipManager onFlipStateData:]"
+ "-[CMFlipManager sendEventToClientPrivate]"
+ "-[CMFlipManager simulateFlipState:reason:]_block_invoke"
+ "-[CMFlipManager startUpdatesPrivateToQueue:withHandler:]"
+ "-[CMFlipManager stopUpdatesPrivate]"
+ "-[CMSuppressionManager feedDeviceStateEvent:facedown:timestamp:force:]_block_invoke"
+ "-[CMSuppressionManager handleDeviceStateEvent:]"
+ "-[CMSuppressionManager handleDeviceStateEvent:]_block_invoke"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Shared/Motion/DeviceState/CLSPUDeviceStateInterface.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Shared/Motion/Notifiers/Angle/CLAngleNotifier.mm"
+ "21:09:51"
+ "A"
+ "Active"
+ "Angle"
+ "Angle=%{signpost.description:attribute}f State=%{signpost.description:attribute}s %{signpost.description:begin_time}llu %{signpost.description:end_time}llu"
+ "Began"
+ "CLAngleNotifier"
+ "CLAngleNotifier.mm"
+ "CLAngleNotifier::isAvailable()"
+ "CLDeviceStateNotifier"
+ "CLDeviceStateNotifier::CLDeviceStateNotifier()"
+ "CLDeviceStateNotifier::fLastEventFromVirtualDevice defaulted to: %s"
+ "CLDeviceStateNotifier::onIoHidEventPhysical fLastEventFromVirtualDevice set to false."
+ "CLDeviceStateNotifier::onIoHidEventVirtual fLastEventFromVirtualDevice set to true."
+ "CLFactoryAngleService.mm"
+ "CLFactoryAngleService::CLFactoryAngleService(std::function<void (const Sample &)> &&)"
+ "CLFactoryAngleService::isAvailable()"
+ "CLFlipNotifier"
+ "CMAngle.m"
+ "CMAngleAPArrivalToNotified"
+ "CMAngleEventPhaseFromCLMotionTypeAngleEventPhase"
+ "CMAngleGestureBeganToWakeEvent"
+ "CMAngleManager.mm"
+ "CMAngleStateChangeAPArrivalToNotified"
+ "CMAngleStateChangeEventSentToAPArrival"
+ "CMAngleStateChangeEventToEventSent"
+ "CMAngleStateChangeGestureBeganToEvent"
+ "CMAngleStateFromCLMotionTypeAngleState"
+ "CMAngleWakeEventSentToAPArrival"
+ "CMAngleWakeEventToWakeEventSent"
+ "CMDeviceStateArrivalToNotified"
+ "CMDeviceStateDetectedToArrival"
+ "CMDeviceStateEventPropertyA0Key"
+ "CMDeviceStateEventPropertyA1Key"
+ "CMDeviceStateEventPropertyAKey"
+ "CMDeviceStateEventPropertyBKey"
+ "CMDeviceStateEventPropertyCKey"
+ "CMDeviceStateEventPropertyDKey"
+ "CMDeviceStateEventSendNotification"
+ "CMDeviceStateManager error: %{public}@"
+ "CMDeviceStateReport::visit() type %{public}d failed."
+ "CMFactoryAngleManager.mm"
+ "CMFlipDetectedToNotified"
+ "CMFlipEventReasonKey"
+ "CMFlipEventSendNotification"
+ "CMFlipEventStateKey"
+ "CMFlipManagerClientID"
+ "CMFlipManagerClientType"
+ "CMFlipReport::visit() type %{public}d failed."
+ "CMFlipReportArrival"
+ "CMFlipServiceEnable"
+ "CMPocketStateManager_%@"
+ "CMSuppressionManager_%@"
+ "Canceled pending angle update for %{public}p"
+ "Cancelled"
+ "Changed"
+ "DeltaSecs=%{signpost.telemetry:number1,public}f enableTelemetry=YES "
+ "DeviceState"
+ "DeviceState CLDeviceStateNotifier::currentDeviceState()"
+ "Event created successfully. PropertyA: %{public}@ PropertyA0: %{public}@ PropertyA1: %{public}@ PropertyB: %{public}@ PropertyC: %{public}@ timestamp: %{public}f, continuousTimestamp: %{public}f"
+ "Flip"
+ "FlipGesture"
+ "FlipGesture1"
+ "Gesture ended for %{public}p with phase %{public}u"
+ "Getting latest AP angle for %{public}p"
+ "IOHIDEventGetType(event) == kIOHIDEventTypeHingeAngle"
+ "Inactive"
+ "Incoming device state event, PropertyA,%{public}@,PropertyB,%{public}@,PropertyC,%{public}@"
+ "Invalid configType: %{public}ld"
+ "Invalid deviceStatePropertyAType, propertyBType, propertyCType combination."
+ "Invalid payload size"
+ "Invalid propertyA input."
+ "Invalid state"
+ "Invalid usage"
+ "Invalid usagePage"
+ "MayBegin"
+ "OverridesAngleAxisX"
+ "OverridesAngleAxisY"
+ "OverridesAngleAxisZ"
+ "ParameterA"
+ "ParameterB"
+ "ParameterC"
+ "ParameterD"
+ "ParameterE"
+ "ParameterF"
+ "ParameterG"
+ "ParameterH"
+ "ParameterI"
+ "ParameterJ"
+ "PropertyA ambiguous for PropertyB Ambiguous, ParameterD & ParameterE."
+ "PropertyA=%{public}ld PropertyA0=%{public}ld PropertyA1=%{public}ld PropertyB=%{public}ld PropertyC=%{public}ld TimestampDeltaArrivalToNotified=%{public}f"
+ "PropertyA=%{public}u PropertyA0=%{public}u PropertyA1=%{public}u PropertyB=%{public}u PropertyC=%{public}u PropertyD=%{public}u TimestampDeltaDetectedToArrival=%{public}f"
+ "Report,FlipState,state,%{public}u,reason,%{public}u,wake,%{public}u,isSimulated,%{public}u,timestamp,%{public}lf,now,%{public}lf"
+ "Report,Type,%{public}u,PropertyAType,%{public}u,PropertyA0Type,%{public}u,PropertyA1Type,%{public}u,PropertyBType,%{public}u,PropertyCType,%{public}u,PropertyDType,%{public}u,isSimulated,%{public}d,timestamp,%{public}lf,timestampContinuous,%{public}lf,now,%{public}lf"
+ "Requesting latest device state."
+ "Scheduling angle update for %{public}p to handler %{public}p on queue %{public}p with CMAngle = { %@ }"
+ "Starting angle updates for %p with handler %{public}p, queue %{public}p"
+ "State=%{public}u,Reason=%{public}u,DeltaAPArrival=%{signpost.telemetry:number1,public}f enableTelemetry=YES "
+ "StaticEntry"
+ "StaticExit"
+ "Stopping angle updates for %p with handler %{public}p, queue %{public}p"
+ "Unexpected event type"
+ "[%{public}@] %@ is not supported on this platform!"
+ "[%{public}@] CLFlipNotifier instance is NULL"
+ "[%{public}@] CMFlipManager is not supported on this platform!"
+ "[%{public}@] Clamping out-of-range flip reason,%{public}ld,to Ambiguous"
+ "[%{public}@] Connection interrupted; resending service request."
+ "[%{public}@] Distributed notification missing flip reason"
+ "[%{public}@] Incoming DeviceState Notification PropertyA: %{public}ld  PropertyA0: %{public}ld PropertyA1: %{public}ld PropertyB: %{public}f PropertyC: %{public}d PropertyD: %{public}ld"
+ "[%{public}@] Incoming deviceState event, propertyAType,%{public}u, propertyA0Type,%{public}u, propertyA1Type,%{public}u, propertyBType,%{public}u, propertyCType,%{public}u, propertyDType,%{public}u, isSimulated,%{public}u, timestampAbsoluteSecs,%{public}f, timestampContinuousSecs,%{public}f"
+ "[%{public}@] Invalid data parameter!"
+ "[%{public}@] Invalid distributed notification payload"
+ "[%{public}@] Invalid flip state value: %{public}ld"
+ "[%{public}@] Invalid notification payload!"
+ "[%{public}@] Invalid propertyA value!"
+ "[%{public}@] Invalid propertyA0 value!"
+ "[%{public}@] Invalid propertyA1 value!"
+ "[%{public}@] Invalid propertyB value!"
+ "[%{public}@] Invalid propertyD value!"
+ "[%{public}@] Invalid service response."
+ "[%{public}@] New event is identical to previous event, skipping!"
+ "[%{public}@] Not entitled to manage the AOP service."
+ "[%{public}@] Registered dispatcher with CLFlipNotifier"
+ "[%{public}@] Registered for distributed notifications"
+ "[%{public}@] Registering for notifications."
+ "[%{public}@] Sending DeviceState event to client: %{public}@,now,%{public}f"
+ "[%{public}@] Sending Flip event to client: %{public}@,now,%{public}f"
+ "[%{public}@] Service is not available!"
+ "[%{public}@] Service rejected request: invalid parameters."
+ "[%{public}@] Service request failed! error,%{public}ld"
+ "[%{public}@] Starting DeviceState updates without progress."
+ "[%{public}@] Starting Flip updates"
+ "[%{public}@] Stopping DeviceState updates"
+ "[%{public}@] Stopping Flip updates"
+ "[%{public}@] Unable to communicate with AOP service!"
+ "[%{public}@] Unregistered dispatcher from CLFlipNotifier"
+ "[%{public}@] Unregistered from distributed notifications"
+ "[%{public}@] Unregistering for notifications."
+ "[%{public}@] onDistributedNotification,state,%{public}ld,reason,%{public}ld"
+ "[%{public}@] onFlipState,state,%{public}ld,reason,%{public}u,isSimulated,%{public}u,timestamp,%{public}lf,continuousTimestamp,%{public}lf"
+ "[%{public}@] simulateFlipState,state,%{public}ld,reason,%{public}ld"
+ "[%{public}ld] Incoming device state event, PropertyA,%{public}@,PropertyB,%{public}@,PropertyC,%{public}@"
+ "[%{public}ld] fAllowSuppressionForConfigTypeDefault: %{public}s"
+ "[%{public}ld][%{public}@][%{public}ld] -> Feeding device state event: %{public}@ @ %{public}f"
+ "[%{public}ld][%{public}@][%{public}ld] -> Not feeding device state event: %{public}@ @ %{public}f"
+ "[%{public}ld][%{public}@][%{public}ld] Stopping suppression updates. Final states: DS: %{public}@ @ %{public}f, SPN: %{public}@ @ %{public}f, DP: %{public}@ @ %{public}f"
+ "[CLAngleNotifier] %{public}s : phase=%{public}s, state=%{public}s, angle=%{public}f, mechanicalAngle=%{public}f, velocity=%{public}f, timestamp=%{public}lf (%{public}llu), continuousTimestamp=%{public}lf (%{public}llu), gestureBeganContinuousTimestamp=%{public}f (%{public}llu), messageSentContinuousTimestamp=%{public}f (%{public}llu), isWakeEvent=%{public}d"
+ "[CLAngleNotifier] Event ref invalid"
+ "[CLAngleNotifier] Skipping open for physical HID device on VM/Simulator"
+ "[CLAngleNotifier] Unrecognized update interval notification %{public}d"
+ "[CLAngleNotifier] copied event is invalid"
+ "[CLAngleNotifier] copyEvent returned invalid event ref"
+ "[CLAngleNotifier] copyEvent: no HID device available"
+ "[CLDeviceStateNotifier] Skipping open for physical HID device on VM/Simulator"
+ "[CLDeviceStateNotifier] copied event isn't DeviceState report,type,%{public}d,size,%{public}lu"
+ "[CLDeviceStateNotifier] copyEvent returned invalid event ref"
+ "[CLDeviceStateNotifier] currentDeviceState failed, openHidDevice failed"
+ "[CLDeviceStateNotifier] currentDeviceState: no HID device available"
+ "[CLFactoryAngleService] Overriding axis with x=%f, y=%f, z=%f"
+ "[CLFlipInterface] Dispatching cached flip state via copyEvent"
+ "[CLFlipInterface] copyEvent returned no cached flip state"
+ "[CLFlipInterface] copyEvent returned no valid flip state"
+ "[CLFlipInterface] dispatchCachedEvent called with no HID device"
+ "[CLFlipNotifier] No cached state, sending default Ambiguous"
+ "[CLIoHidInterface] setMatchingEventForCopyEvent should be called from motion thread"
+ "[CLSPUDeviceStateInterface] Service required"
+ "[CLSPUDeviceStateInterface] Simulate failed"
+ "[CLSPUDeviceStateInterface] Simulate,propertyA,%{public}u,propertyA0,%{public}u,propertyA1,%{public}u,propertyB,%{public}u,propertyC,%{public}u,propertyD,%{public}u,%{public}f"
+ "[CLSPUDeviceStateInterface] sendCommand skipped, no physical HID driver (VM/Simulator)"
+ "[static_cast<id>(info) isKindOfClass:CMAngleManagerInternal.class]"
+ "angle %f, isValid: %d @ %f"
+ "angle: %f, mechanicalAngleDegrees: %f, progress: %f, isAngleValid: %d, velocityDegreesPerSeconds: %f, isVelocityValid: %d, state: %ld, eventPhase: %ld @ absoluteTime: %f, continuousTime: %f"
+ "angleDataFromAngleHIDEvent"
+ "angleEventPhase"
+ "angleState"
+ "bool CLSPUDeviceStateInterface::sendCommand(const void *, size_t)"
+ "bool CLSPUFlipInterface::dispatchCachedEvent()"
+ "bool CLSPUFlipInterface::openHidDevice()"
+ "com.apple.CoreMotion.CMFlipManager"
+ "defaultInit_%@"
+ "deviceState"
+ "kCLConnectionMessageFlipServiceRequest"
+ "kCLConnectionMessageSuppressionType2ClientChange"
+ "kCLConnectionMessageSuppressionType2StateChange"
+ "kCMDeviceStateEventCodingKeyPropertyA"
+ "kCMDeviceStateEventCodingKeyPropertyA0"
+ "kCMDeviceStateEventCodingKeyPropertyA1"
+ "kCMDeviceStateEventCodingKeyPropertyB"
+ "kCMDeviceStateEventCodingKeyPropertyC"
+ "kCMDeviceStateEventCodingKeyPropertyD"
+ "kCMFlipEventCodingKeyFlipReason"
+ "kCMFlipEventCodingKeyFlipState"
+ "onAccelerometer1Change"
+ "onAccelerometerChange"
+ "onAngleChange"
+ "onGyro1Change"
+ "onGyroChange"
+ "onIoHidEvent"
+ "onIoHidEventBounce"
+ "onIoHidEventBounceVirtual"
+ "payload && payloadSize == sizeof(CMAnglePrivateData)"
+ "physical"
+ "queryDeviceStateBlocking is unsupported and should not be used."
+ "queryDeviceStateWithHandler is unsupported and should not be used."
+ "reConfigure"
+ "report"
+ "setMatchingEventForCopyEvent"
+ "sharedManager_%@"
+ "static void CLDeviceStateNotifier::onIoHidEventPhysical(void *, void *, void *, IOHIDEventRef)"
+ "static void CLDeviceStateNotifier::onIoHidEventVirtual(void *, void *, void *, IOHIDEventRef)"
+ "std::optional<AngleData> CLAngleNotifier::copyEvent(CLIoHidInterface::Device::NeedsEventUpdate)"
+ "std::optional<AngleData> CLAngleNotifier::copyEvent(CLIoHidInterface::Device::NeedsEventUpdate)_block_invoke"
+ "suppress"
+ "target"
+ "toCLMotionType"
+ "toString"
+ "unsuppress"
+ "updateAngleDataWithPrivateDataFromAngleHIDEvent"
+ "usage == kHIDUsage_AppleVendorMotion_CranePrivateData"
+ "usagePage == kHIDPage_AppleVendorMotion"
+ "v24@?0@\"CMDeviceStateEvent\"8@\"NSError\"16"
+ "velocityDegreesPerSeconds"
+ "virtual"
+ "virtual CFTimeInterval CLAngleNotifier::minimumUpdateIntervalChanged(int, const CFTimeInterval &)"
+ "virtual bool CLDeviceStateNotifier::openHidDevice()"
+ "virtual void CLDeviceStateNotifier::numberOfSpectatorsChanged(int, size_t)"
+ "virtual void CLDeviceStateNotifier::visitDeviceState(const CMDeviceStateReport::DeviceState *)"
+ "virtual void CLFlipNotifier::numberOfSpectatorsChanged(int, size_t)"
+ "virtual void CLFlipNotifier::visitFlipState(const CMFlipReport::FlipState *)"
+ "virtual void CLFlipNotifier::visitPong(const CMFlipReport::Pong *)"
+ "virtual void CLSPUDeviceStateInterface::visitPong(const CMDeviceStateReport::Pong *)"
+ "void CLAngleNotifier::onIoHidEvent(IOHIDEventRef, bool)"
+ "void CLAngleNotifier::openHIDDriverInterfaceIfNeeded()"
+ "void CLPocketStateService::enableDetection()_block_invoke"
+ "void CLSPUDeviceStateInterface::onIoHidEvent(IOHIDEventRef)"
+ "void CLSPUDeviceStateInterface::simulateDeviceStateEvent(uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, CFTimeInterval)_block_invoke"
+ "void CLSPUDeviceStateInterface::visitIoHidEvent(const uint8_t *, size_t, const CFTimeInterval, const CFTimeInterval)"
+ "void CLSPUFlipInterface::onIoHidEvent(IOHIDEventRef)"
+ "void CLSPUFlipInterface::visitIoHidEvent(const uint8_t *, size_t, const CFTimeInterval, const CFTimeInterval)"
+ "{\"msg%{public}.0s\":\"Invalid payload size\", \"payloadSize\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid state\", \"hidState\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid usage\", \"usage\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid usagePage\", \"usagePage\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Unexpected event type\", \"eventType\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"[CLIoHidInterface] setMatchingEventForCopyEvent should be called from motion thread\", \"usagePage\":%{public}d, \"usage\":%{public}d, \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"[CLSPUDeviceStateInterface] Service required\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
- "22:07:34"
- "kData4"
```
