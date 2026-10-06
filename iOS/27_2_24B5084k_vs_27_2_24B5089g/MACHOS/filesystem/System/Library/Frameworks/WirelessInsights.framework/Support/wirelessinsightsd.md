## wirelessinsightsd

> `/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34e6a0` | `0x350e5c` | **`+0x27bc`** |
| `__TEXT.__oslogstring` | `0x2f242` | `0x2f7b2` | **`+0x570`** |
| `__TEXT.__gcc_except_tab` | `0x2aae8` | `0x2ad88` | **`+0x2a0`** |
| `__DATA_CONST.__const` | `0x17570` | `0x176b0` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x10580` | `0x10640` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x161eb` | `0x1623b` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x75e0` | `0x75c0` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x4ff0` | `0x4fd0` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x2810` | `0x2800` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-368.0.0.0.0
+369.1.0.0.0

-  Functions: 14489
-  Symbols:   2062
-  CStrings:  10458
+  Functions: 14519
+  Symbols:   2060
+  CStrings:  10475
Symbols:
+ _arc4random_uniform
- __ZNSt3__113random_deviceC1ERKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE
- __ZNSt3__113random_deviceD1Ev
- __ZNSt3__113random_deviceclEv
CStrings:
+ "369.1"
+ "369.1~17"
+ "ParseError: "
+ "WISCOA:Already in OOS with a retry sequence in progress; dropping subsequent OOS callback"
+ "WISCOA:Cancel API retry timers due to Registration status changed"
+ "WISCOA:Carrier API already confirmed the outage; not overwriting with crowd-sourced result"
+ "WISCOA:Carrier API check is skipped for this OOS episode; no carrier retry will be scheduled"
+ "WISCOA:Carrier API pre-check bailout; retrying in %d minutes (attempt %d/%d)"
+ "WISCOA:Carrier API reached maximum retry count (%d/%d); bailing out carrier API retry sequence"
+ "WISCOA:Carrier API request failed; backing off %u seconds before attempt %d/%d"
+ "WISCOA:Carrier API result is stale, discarding"
+ "WISCOA:Crowd-sourced API did not yield an outage; retrying in %d minutes (attempt %d/%d)"
+ "WISCOA:Crowd-sourced API reached maximum retry count (%d/%d); bailing out crowd-sourced API retry sequence"
+ "WISCOA:Crowd-sourced API result is stale, discarding"
+ "WISCOA:Device does not appear to be in OOS; Bailing out carrier API retry"
+ "WISCOA:Device does not appear to be in OOS; Bailing out carrier API retry sequence"
+ "WISCOA:Device does not appear to be in OOS; Bailing out crowd-sourced API retry"
+ "WISCOA:Device does not appear to be in OOS; Bailing out crowd-sourced API retry sequence"
+ "WISCOA:Failed to create carrier API retry timer; ending carrier API retry sequence"
+ "WISCOA:Failed to create crowd-sourced API retry timer; ending crowd-sourced API retry sequence"
+ "WISCOA:Failed to parse JWT token response: %s"
+ "WISCOA:Failed to parse outage response: %s"
+ "WISCOA:Making API request"
+ "WISCOA:Outage detected during retry wait, stopping carrier API retry sequence"
+ "WISCOA:Outage detected during retry wait, stopping crowd-sourced API retry sequence"
+ "WISCOA:Outage detected, stopping carrier API retry sequence"
+ "WISCOA:Outage detected, stopping crowd-sourced API retry sequence"
+ "WISCOA:Outage status from API response: %{bool}d"
+ "WISCOA:Retry sequence not finished yet (carrier done: %{bool}d [%d/%d, skipped: %{bool}d], crowd-sourced done: %{bool}d [%d/%d]); deferring final metric"
+ "WISCOA:SigLoc confirmed OOS, dispatching carrier and crowd-sourced outage checks"
+ "WISCOA:Telephony delegate unavailable; skipping crowd-sourced check"
+ "WISCOA:WISCarrierOutageClient unable to get response: %s"
+ "com.apple.wirelessinsightsd.coa.carrierFetch"
+ "com.apple.wirelessinsightsd.coa.crowdSourcedFetch"
- "/dev/urandom"
- "368"
- "368~37"
- "WISCOA:API retry sequence[max: %d] (carrier retries: %d, crowd-sourced retries: %d)"
- "WISCOA:Attempt %d failed - empty response. Waiting %d seconds before retry..."
- "WISCOA:Cancel ApiRetyTimer before retry"
- "WISCOA:Cancel ApiRetyTimer due to Registration status changed"
- "WISCOA:Device does not appear to be in OOS; Bailing out API calls retry"
- "WISCOA:Exhausted API query limits, ending retry sequences!"
- "WISCOA:Failed to create API retry timer"
- "WISCOA:Making API request - attempt %d/%d"
- "WISCOA:No outage detected from APIs but SigLoc confirmed OOS, starting retry sequence"
- "WISCOA:Outage confirmed after retry, ending retry sequence"
- "WISCOA:Outage detected during retry wait, stopping retry sequence"
- "WISCOA:Outage status from API response: %d"
- "WISCOA:WISCarrierOutageClient unable to get response after %d attempts"
- "apiMaxRetryRequests"
```
