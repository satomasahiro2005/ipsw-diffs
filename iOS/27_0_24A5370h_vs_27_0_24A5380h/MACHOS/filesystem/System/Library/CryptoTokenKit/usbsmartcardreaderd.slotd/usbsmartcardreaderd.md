## usbsmartcardreaderd

> `/System/Library/CryptoTokenKit/usbsmartcardreaderd.slotd/usbsmartcardreaderd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15ae8` | `0x16c74` | **`+0x118c`** |
| `__TEXT.__oslogstring` | `0x159b` | `0x1a90` | **`+0x4f5`** |
| `__TEXT.__objc_stubs` | `0x3000` | `0x3100` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x22c9` | `0x236e` | **`+0xa5`** |
| `__DATA.__data` | `0x190` | `0x1f0` | **`+0x60`** |
| `__DATA.__objc_const` | `0x26a8` | `0x2700` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x16f4` | `0x1734` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x120` | `0x150` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0xdc0` | `0xde8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x7e0` | `0x808` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x608` | `0x630` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x2120` | `0x2140` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x1e7` | `0x1fc` | **`+0x15`** |
| `__DATA_CONST.__objc_doubleobj` | `0x20` | `0x30` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__const` | `0x2a0` | `0x2a8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x15d5` | `0x15db` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-878.0.3.0.0
+878.0.8.0.0

-  Functions: 658
+  Functions: 680

-  CStrings:  1129
+  CStrings:  1155
CStrings:
+ "<nil>"
+ "APDU Mapping: unparseable APDU (%lu bytes); rejecting"
+ "ChainableTransmitter"
+ "Inbound chain: assembled payload would exceed cap %lu at frame %lu"
+ "Inbound chain: continuation reply has unexpected messageType (frame %lu)"
+ "Inbound chain: frame count exceeded cap %lu; aborting"
+ "Inbound chain: initial payload %lu bytes exceeds cap %lu"
+ "Inbound chain: state violation at frame %lu bChainParameter=0x%02x"
+ "Inbound chain: unexpected initial bChainParameter=0x%02x"
+ "Message is nil or unexpected type"
+ "Outbound chain frame %lu/%lu (wLevelParameter=0x%04x) failed: %{public}@"
+ "RDR_to_PC_HardwareError: short frame (%lu bytes)"
+ "RDR_to_PC_HardwareError: slot=%u bSeq=%u bHardwareErrorCode=0x%02x"
+ "T1 TPDU Mapping transmit"
+ "Unhandled interrupt-IN message type 0x%02x"
+ "abortChainOnSequence:"
+ "abortSequence: drain deadline (%.1fs) expired without matching SlotStatus terminator (seq=%u)"
+ "abortSequence: drain receive returned 0 bytes (timeout); checking deadline"
+ "abortSequence: drain saw frame for slot %u while aborting slot %u; bailing"
+ "abortSequence: drain saw short/partial reply (%lu bytes, below CCID header); discarding and continuing"
+ "abortSequence: drained matching SlotStatus terminator (seq=%u)"
+ "abortSequence: step 1 control transfer failed (continuing to step 2): %{public}@"
+ "abortSequence: step 2 bulk-OUT short send (%lu of %lu bytes; continuing to step 3)"
+ "dateWithTimeIntervalSinceNow:"
+ "maxOutboundCCIDMessageLength"
+ "sendOutboundChain:maxPayload:outTimeout:inTimeout:transmitted:"
+ "timeIntervalSinceNow"
- "T1 APDU Mapping transmit"
```
