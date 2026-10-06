## com.apple.kernel

> `com.apple.kernel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x8e3be4` | `0x8e6ed8` | **`+0x32f4`** |
| `__TEXT.__const` | `0x36af0` | `0x36e70` | **`+0x380`** |
| `__BOOTDATA.__init_entry_set` | `0x13b30` | `0x13d58` | **`+0x228`** |
| `__TEXT.__os_log` | `0x418ba` | `0x41aa8` | **`+0x1ee`** |
| `__DATA_CONST.__const` | `0xb6d78` | `0xb6f60` | **`+0x1e8`** |
| `__TEXT.__cstring` | `0x8d638` | `0x8d789` | **`+0x151`** |
| `__DATA_CONST.__assert` | `0xdfc` | `0xf14` | **`+0x118`** |
| `__BOOTDATA.__init` | `0x17760` | `0x17818` | **`+0xb8`** |
| `__DATA.__data` | `0x181a9` | `0x18229` | **`+0x80`** |
| `__DATA_CONST.__kalloc_type` | `0x15380` | `0x15300` | **`-0x80`** |
| `__DATA.__bss` | `0xa4f80` | `0xa4fe0` | **`+0x60`** |
| `__DATA.__lock_grp` | `0x5d80` | `0x5dd8` | **`+0x58`** |
| `__TEXT.__copyio_vectors` | `0xf0` | `0x140` | **`+0x50`** |
| `__DATA.__common` | `0x68e48` | `0x68e88` | **`+0x40`** |

### Other Changes

```diff

-13432.0.50.502.2
-  Functions: 21870
+13432.0.94.502.2
+  Functions: 21880

-  CStrings:  21072
+  CStrings:  21092
CStrings:
+ "%s: %s %s DHCP dp_flags 0x%x -> 0x%x"
+ "%s: %s: dir %s action %s reqid 0x%x sa_handle 0x%llx handle 0x%llx\n"
+ "%s: %s: spi 0x%x reqid 0x%x handle 0x%llx dir %s src %s[%u] dst %s[%u] proto %u\n"
+ "%s: refusing cross-protocol ifa change on route with llinfo"
+ "(%u): HMAC verification failed: %d\n"
+ "111122211111222211112111121222122"
+ "12120000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000122222222222222222221221211111111221122000000000"
+ "122112211222111"
+ "ALLOW"
+ "B16@?0^{proc=(?={?=^{proc}^^{proc}}{smr_node=^{smr_node}^?})^{proc}^{proc_ro}iiIIIIIIiIQ{?=[2Q]}iCccc{?=^{proc}^^{proc}}{?=^{proc}^^{proc}}{?=^{proc}}{?=^{uthread}^^{uthread}}{smrq_slink={?=^{smrq_slink}}}^{persona}{?=^{proc}^^{proc}}{?=[2Q]}{filedesc={?=[2Q]}CCSiiiii^^{fileproc}*^{klist}^{kqworkq}^{vnode}^{vnode}{?=[2Q]}{?=[2Q]}Q^{kqwllist}{?=[2Q]}Q^{klist}}^{pstats}{?=^{plimit}}{?=^{pgrp}}{sigacts=[32Q][32Q][32I]IIIIIAIi}{?=[2Q]}iIIIIAIAIiiiIi{itimerval={timeval=qi}{timeval=qi}}{timeval=qi}{itimerval={timeval=qi}{timeval=qi}}{itimerval={timeval=qi}{timeval=qi}}{timeval=qi}ii^v^viIII^vii(?={?=IiQ^{vnode}qIIIICCcC[17c][33c]CiI[16C]Q[16C]ii}{proc_forkcopy_data=IiQ^{vnode}qIIIICCcC[17c][33c]CiI[16C]Q[16C]ii}){?=^{aio_workq_entry}^^{aio_workq_entry}}{?=^{aio_workq_entry}^^{aio_workq_entry}}{klist=^{knote}}^{rusage_superset}^{thread}^{thread}^{thread}iSSQQiIQA^{workqueue}A^{workq_aio_s}{timeval=qi}^v^vQQ*QQQQQQQ{timeval=qi}SCBBCIiiiI{?=^{proc}^^{proc}}QQQQiiiiIIII[3AS]IQII^{os_reason}^{virtual_env}}8"
+ "DISCARD"
+ "Disabled MTE soft mode because process was ptraced\n"
+ "FWD"
+ "bridge_mac_nat_dhcp_adjust_flags"
+ "com.apple.private.kernel.cpu-counters-info"
+ "com.apple.private.shared-region.config"
+ "flow_registration_count"
+ "ipsec_nonoffload_policy_count > 0"
+ "key_build_offload_policy: unsupported policy action %u for offload\n"
+ "key_build_offload_sa: authentication key too long %u\n"
+ "key_build_offload_sa: encryption key too long %u\n"
+ "key_parse: invalid address extension.\n"
+ "key_setsaval: ESN flag requires an offload interface (offload_if); software ESN is not supported\n"
+ "key_setsaval: offload SA must specify exactly one direction (IN or OUT)\n"
+ "necp_client.c"
+ "necp_flow_registration_count underflow @%s:%d"
+ "offload_fastpath_in"
+ "offload_fastpath_out"
+ "pf_socket_lookup -1 returns due to ipi_lock contention"
+ "rBBR best-effort receive-side throttling enabled"
+ "rt_setif"
+ "socket_lookup_contended"
+ "stale RACK segment [%u, %u) flags 0x%x below snd_una %u"
+ "tcp_rack_output"
+ "throttle_be"
- "%s: %s %s DHCP dp_flags 0x%x"
- "%s: %s: reqid 0x%x sa_handle 0x%llx handle 0x%llx\n"
- "%s: %s: spi 0x%x, reqid 0x%x handle 0x%llx\n"
- "(%u): HMAC verfication failed: %d\n"
- "11112221111122221111211112122212"
- "12120000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000112000000000000011200000000000001120000000000000122222222222222222221221211111111221220000000000"
- "12211211222111"
- "B16@?0^{proc=(?={?=^{proc}^^{proc}}{smr_node=^{smr_node}^?})^{proc}^{proc_ro}iiIIIIIIiIQ{?=[2Q]}iCccc{?=^{proc}^^{proc}}{?=^{proc}^^{proc}}{?=^{proc}}{?=^{uthread}^^{uthread}}{smrq_slink={?=^{smrq_slink}}}^{persona}{?=^{proc}^^{proc}}{?=[2Q]}{filedesc={?=[2Q]}CCSiiiii^^{fileproc}*^{klist}^{kqworkq}^{vnode}^{vnode}{?=[2Q]}{?=[2Q]}Q^{kqwllist}{?=[2Q]}Q^{klist}}^{pstats}{?=^{plimit}}{?=^{pgrp}}{sigacts=[32Q][32Q][32I]IIIIIAIi}{?=[2Q]}iIIIIAIAIiiiIi{itimerval={timeval=qi}{timeval=qi}}{timeval=qi}{itimerval={timeval=qi}{timeval=qi}}{itimerval={timeval=qi}{timeval=qi}}{timeval=qi}ii^v^viIII^vii(?={?=IiQ^{vnode}qIIIICCcC[17c][33c]CiI[16C]Q[16C]ii}{proc_forkcopy_data=IiQ^{vnode}qIIIICCcC[17c][33c]CiI[16C]Q[16C]ii}){?=^{aio_workq_entry}^^{aio_workq_entry}}{?=^{aio_workq_entry}^^{aio_workq_entry}}{klist=^{knote}}^{rusage_superset}^{thread}^{thread}^{thread}iSSQQiIQA^{workqueue}A^{workq_aio_s}{timeval=qi}^v^vQQ*QQQQQQ{timeval=qi}SCBBCIiiiI{?=^{proc}^^{proc}}QQQQiiiiIIII[3AS]IQII^{os_reason}^{virtual_env}}8"
- "ERROR - the creation of new shared region namespaces is restricted by entitlement"
- "Soft mode disabled because process was ptraced\n"
- "Unexpected debugger trap while SP1 selected"
- "bridge_mac_nat_dhcp_flags"
- "internal-isa-vm-allowed"
- "tcp_rack.c"
- "tcp_rack_output: stale segment %p [%u, %u) flags 0x%x below snd_una %u @%s:%d"
```
