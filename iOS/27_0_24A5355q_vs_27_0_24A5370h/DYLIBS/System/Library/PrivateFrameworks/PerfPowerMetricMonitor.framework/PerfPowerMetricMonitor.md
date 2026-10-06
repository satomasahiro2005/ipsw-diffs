## PerfPowerMetricMonitor

> `/System/Library/PrivateFrameworks/PerfPowerMetricMonitor.framework/PerfPowerMetricMonitor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18170` | `0x18680` | **`+0x510`** |
| `__AUTH_CONST.__objc_const` | `0x2278` | `0x2308` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x1440` | `0x14a0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x10fd` | `0x1157` | **`+0x5a`** |
| `__TEXT.__objc_methlist` | `0x155c` | `0x15a4` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x1bae` | `0x1be2` | **`+0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0xeb0` | `0xee0` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x908` | `0x928` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x220` | `0x22c` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x678` | `0x680` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x278` | `0x280` | **`+0x8`** |

### Other Changes

```diff

-3468.0.0.502.1
+3486.0.21.502.1

-  Functions: 603
-  Symbols:   969
-  CStrings:  311
+  Functions: 609
+  Symbols:   978
+  CStrings:  317
Symbols:
+ -[PPSClient setTrackedProcesses:]
+ -[PPSClient trackedProcesses]
+ -[PPSMetricCollection ispPower]
+ -[PPSMetricCollection setIspPower:]
+ -[PPSMetricMonitorService _isProcessAlive:withExpectedName:]
+ -[PPSProcessMetricCollection processActive]
+ -[PPSProcessMetricCollection setProcessActive:]
+ GCC_except_table110
+ GCC_except_table40
+ GCC_except_table64
+ GCC_except_table69
+ GCC_except_table73
+ GCC_except_table77
+ GCC_except_table88
+ _OBJC_IVAR_$_PPSClient._trackedProcesses
+ _OBJC_IVAR_$_PPSMetricCollection._ispPower
+ _OBJC_IVAR_$_PPSProcessMetricCollection._processActive
+ _kPPSProcessActiveKey
- -[PPSMetricMonitorService _isProcessAlive:]
- GCC_except_table108
- GCC_except_table38
- GCC_except_table44
- GCC_except_table62
- GCC_except_table67
- GCC_except_table71
- GCC_except_table75
- GCC_except_table86
CStrings:
+ "Active"
+ "Energy Cost        %8.3f     %@\nEnergy Overhead    %8.3f     %@\nCPU Cost           %8.3f     %@\nCPU Seconds        %8.3f s   %@\nCPU Seconds (without vouchers) %8.3f s   %@\nCPU Seconds (vouchers) %8.3f s   %@\nCPU Energy         %8.3f nJ  %@\nCPU Energy (without vouchers)  %8.3f nJ  %@\nCPU Energy (vouchers)  %8.3f nJ  %@\nGPU Cost           %8.3f     %@\nGPU Energy         %8.3f nJ  %@\nGPU Energy (without vouchers)  %8.3f nJ  %@\nGPU Energy (vouchers)  %8.3f nJ  %@\nDisplay Power      %8.3f     %@\nNetwork Cost       %8d     %@\nWiFi In            %8d B   %@\nWiFi Out           %8d B   %@\nCell In            %8d B   %@\nCell Out           %8d B   %@\nLocation Cost      %8.3f     %@\nOngoing Location   %8s     %@\nLocation Desired Accuracy %8.3f %@\nQOS Utility %8.3f s   %@\nQOS Background %8.3f s   %@\nQOS User Initiated %8.3f s   %@\nQOS User Interactive %8.3f s   %@\nQOS Default %8.3f s   %@\nQOS Maintenance %8.3f s   %@\nQOS Unspecified %8.3f s   %@\nApplication State               %@\nProcess Active                  %s\n%29s"
+ "ISP_Power_W"
+ "Inactive"
+ "PPSMetricMonitorService: PID %d: processActive = %d"
+ "__processActive__"
+ "ispPower"
- "Energy Cost        %8.3f     %@\nEnergy Overhead    %8.3f     %@\nCPU Cost           %8.3f     %@\nCPU Seconds        %8.3f s   %@\nCPU Seconds (without vouchers) %8.3f s   %@\nCPU Seconds (vouchers) %8.3f s   %@\nCPU Energy         %8.3f nJ  %@\nCPU Energy (without vouchers)  %8.3f nJ  %@\nCPU Energy (vouchers)  %8.3f nJ  %@\nGPU Cost           %8.3f     %@\nGPU Energy         %8.3f nJ  %@\nGPU Energy (without vouchers)  %8.3f nJ  %@\nGPU Energy (vouchers)  %8.3f nJ  %@\nDisplay Power      %8.3f     %@\nNetwork Cost       %8d     %@\nWiFi In            %8d B   %@\nWiFi Out           %8d B   %@\nCell In            %8d B   %@\nCell Out           %8d B   %@\nLocation Cost      %8.3f     %@\nOngoing Location   %8s     %@\nLocation Desired Accuracy %8.3f %@\nQOS Utility %8.3f s   %@\nQOS Background %8.3f s   %@\nQOS User Initiated %8.3f s   %@\nQOS User Interactive %8.3f s   %@\nQOS Default %8.3f s   %@\nQOS Maintenance %8.3f s   %@\nQOS Unspecified %8.3f s   %@\nApplication State               %@\n%29s"
```
