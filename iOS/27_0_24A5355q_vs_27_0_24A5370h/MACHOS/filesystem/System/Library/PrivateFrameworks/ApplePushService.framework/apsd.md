## apsd

> `/System/Library/PrivateFrameworks/ApplePushService.framework/apsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x116fa8` | `0x1175bc` | **`+0x614`** |
| `__TEXT.__oslogstring` | `0x13db5` | `0x13fd5` | **`+0x220`** |
| `__DATA_CONST.__cfstring` | `0x8380` | `0x8480` | **`+0x100`** |
| `__DATA.__objc_const` | `0x1c5c0` | `0x1c530` | **`-0x90`** |
| `__TEXT.__cstring` | `0xfb84` | `0xfc14` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x34f0` | `0x34a0` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x9988` | `0x9948` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x1b905` | `0x1b8d5` | **`-0x30`** |
| `__DATA_CONST.__auth_got` | `0x1a90` | `0x1a68` | **`-0x28`** |
| `__DATA.__bss` | `0x1380` | `0x1360` | **`-0x20`** |
| `__TEXT.__const` | `0xd953` | `0xd973` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x2670` | `0x2650` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0xb828` | `0xb808` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x5678` | `0x5660` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x41f0` | `0x4208` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x878` | `0x880` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1157.100.1.0.0
+1161.100.1.0.0

-  Functions: 6776
-  Symbols:   1197
-  CStrings:  8596
+  Functions: 6775
+  Symbols:   1193
+  CStrings:  8601
Symbols:
+ _APSGetXPCDictionaryFromDictionary
+ _APSPriorityBoostEntitlement
- _IOAllowPowerChange
- _IODeregisterForSystemPower
- _IONotificationPortDestroy
- _IONotificationPortSetDispatchQueue
- _IORegisterForSystemPower
- _IOServiceClose
CStrings:
+ "%@ handleSentOutgoingMessage: %@ onInterface %@ identifier %lu {topic: %@}"
+ "%@ informed of reconnect, retry late critical message %@ sent on another interface {topic: %@}"
+ "%@: Ack'ed outgoing message %lu was already cancelled or timed out {topic: %@}"
+ "%@: Acknowledgment for critical outgoing message %lu is late {topic: %@}"
+ "%@: An acknowledgement for critical outgoing message %lu is late and we are in the middle of a connection attempt - leaving it open. {topic: %@}"
+ "%@: Cancelled outgoing message %lu was already cancelled or timed out {topic: %@}"
+ "%@: Cancelled outgoing message %lu was already sent {topic: %@}"
+ "%@: Clearing sent flag for outgoing message %lu that had been sent on %@ {topic: %@}"
+ "%@: Critical message has timed out. Timeout = %lu. Alerting the delegate. {topic: %@}"
+ "%@: Delivering result for outgoing message %lu with idenitifer %lu: %ld '%@' {topic: %@}"
+ "%@: Dropping outgoing message %lu because queue is full {topic: %@}"
+ "%@: Message %lu may have already been sent, not removing message... {topic: %@}"
+ "%@: Outgoing message %lu timed out {topic: %@}"
+ "%@: Received cancellation for outgoing message %lu {connection: %@}"
+ "%@: Received message for enabled topic '%@' onInterface: %@ with payload '%@' with priority %@ for device token: %@ isProxyMessage: %@, apsd current QOS: %{public}@"
+ "%@: Received message for ignored topic '%@', apsd current QOS: %@"
+ "%@: Received message for recently removed topic '%@', apsd current QOS: %@"
+ "%@: Received message for topic '%@' — resolved boost: %{public}s (source: %{public}s), apsd current QOS: %{public}@"
+ "%@: Received message for unknown topic hash '%@', apsd current QOS: %@"
+ "%@: Reconnecting because ack for critical outgoing message %lu is late. It was sent over %@. {topic: %@}"
+ "%@: Removing cancelled or timed out outgoing message %lu from queue {topic: %@}"
+ "%@: Removing cancelled outgoing message %lu from queue {topic: %@}"
+ "%@: Removing unsent timed out message %lu from queue {topic: %@}"
+ "%@: Tried to send outgoing message %lu but it's not connected yet, {Originator:%@, topic: %@}"
+ "%@: [ExplicitKA] Sending keep alive message with delayed response interval %d via conn: %@ onInterface: %@. reason: %@. Connected on %lu interfaces. Current link quality: %@"
+ "%@: [ImplicitKA] Reset timer on %@ due to %@, next KA in %dsec"
+ "%@: connection set priority boost topics from %@ to %@"
+ "BACKGROUND"
+ "DEFAULT"
+ "Dispatching xpc to client [highPriority, boost=%{public}s] on %@ — dispatch-thread QOS: %{public}@"
+ "Dispatching xpc to client [lowPriority, boost=%{public}s] on %@ — dispatch-thread QOS: %{public}@"
+ "Peer [pid=%d] attempts to set priority boost topics without priority boost entitlement"
+ "T@\"NSDictionary\",C,N,V_priorityBoostTopics"
+ "UNKNOWN(%u)"
+ "UNSPECIFIED"
+ "USER_INITIATED"
+ "USER_INTERACTIVE"
+ "UTILITY"
+ "UserInitiated"
+ "_evaluateAndProcessPendingChange"
+ "_priorityBoostTopics"
+ "cancelOutgoingMessageWithID:fromOriginator:"
+ "client-spi"
+ "priorityBoost"
+ "priorityBoostTopics"
+ "setPriorityBoostTopics:"
- "%@ handleSentOutgoingMessage: %@ onInterface %@ identifier %lu"
- "%@ informed of reconnect, retry late critical message %@ sent on another interface"
- "%@: Ack'ed outgoing message %lu was already cancelled or timed out"
- "%@: Acknowledgment for critical outgoing message %lu is late"
- "%@: An acknowledgement for critical outgoing message %lu is late and we are in the middle of a connection attempt - leaving it open."
- "%@: Cancelled outgoing message %lu was already cancelled or timed out"
- "%@: Cancelled outgoing message %lu was already sent"
- "%@: Clearing sent flag for outgoing message %lu that had been sent on %@"
- "%@: Critical message has timed out. Timeout = %lu. Alerting the delegate."
- "%@: Delivering result for outgoing message %lu with idenitifer %lu: %ld '%@'"
- "%@: Dropping outgoing message %lu because queue is full"
- "%@: Message %lu may have already been sent, not removing message..."
- "%@: Outgoing message %lu timed out"
- "%@: Received cancellation for outgoing message %lu"
- "%@: Received message for enabled topic '%@' onInterface: %@ with payload '%@' with priority %@ for device token: %@ isProxyMessage: %@"
- "%@: Received message for ignored topic '%@'"
- "%@: Received message for recently removed topic '%@'"
- "%@: Received message for unknown topic hash '%@'"
- "%@: Reconnecting because ack for critical outgoing message %lu is late. It was sent over %@."
- "%@: Removing cancelled or timed out outgoing message %lu from queue"
- "%@: Removing cancelled outgoing message %lu from queue"
- "%@: Removing unsent timed out message %lu from queue"
- "%@: Tried to send outgoing message %lu but it's not connected yet, {Originator:%@}"
- "%@: [ExplicitKA] Sending keep alive message with interval %d via conn: %@ onInterface: %@. reason: %@. Connected on %lu interfaces. Current link quality: %@"
- "%@: [ImplicitKA] Reset timer on %@ due to %@, next KA in %dmin"
- "Dispatching high priority message on server: %@"
- "Dispatching low priority message on server: %@"
- "Exception raised during sleep callback: %@"
- "IOAllowPowerChange failed!  Error: %d"
- "IORegisterForSystemPower failed"
- "SLEEP -- going to sleep now"
- "TB,N,V_usesPowerNotifications"
- "WAKE -- just woke up!"
- "_systemDidWake"
- "_systemWillSleep"
- "_usesPowerNotifications"
- "cancelOutgoingMessageWithID:"
- "setUsesPowerNotifications:"
- "systemDidWake"
- "systemWillSleep"
- "usesPowerNotifications"
```
