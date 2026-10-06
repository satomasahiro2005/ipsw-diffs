## BatteryAlgorithms

> `/System/Library/PrivateFrameworks/BatteryAlgorithms.framework/BatteryAlgorithms`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80550` | `0x806d0` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0x3240` | `0x3200` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x8770` | `0x8798` | **`+0x28`** |
| `__TEXT.__cstring` | `0x3ef2` | `0x3ed8` | **`-0x1a`** |
| `__TEXT.__const` | `0xa9d0` | `0xa9c0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2920` | `0x2928` | **`+0x8`** |

### Other Changes

```diff

-146.0.0.0.0
+152.2.1.0.0

-  Functions: 2104
-  Symbols:   4108
-  CStrings:  621
+  Functions: 2106
+  Symbols:   4111
+  CStrings:  619
Symbols:
+ GCC_except_table120
+ GCC_except_table135
+ GCC_except_table151
+ GCC_except_table156
+ GCC_except_table60
+ GCC_except_table86
+ __Z24gCafeLVRConfigurationV5xv
+ __Z28gCafeLVRConfigurationDefaultv
- GCC_except_table119
- GCC_except_table132
- GCC_except_table149
- GCC_except_table59
- GCC_except_table65
CStrings:
+ "\n{\n  \"Lifetime\": {\n    \"controller\": {\n      \"Ki\": 8e-10,\n      \"Kp\": 0.0005,\n      \"u_max\": 1,\n      \"u_min\": 0\n    },\n    \"settings\": {\n      \"shape\": {\n        \"a\": 0,\n        \"b\": 5.7519e-05,\n        \"c\": 2.9304e+03\n      }\n    },\n    \"enable\": 1,\n    \"interval\": 86400\n  },\n  \"ProjectedLifetime\": {\n    \"controller\": {\n      \"Ki\": 0,\n      \"Kp\": 2.00e-03,\n      \"u_max\": 1,\n      \"u_min\": 0\n    },\n    \"settings\": {\n      \"epsilon\": 0.000694444,\n      \"lambda\": 0.85\n    },\n    \"enable\": 0,\n    \"interval\": 86400\n  },\n  \"SafeHarbor\": {\n    \"aged_target\": {\n      \"debounce_time\": 8,\n      \"socv\": 3.2\n    },\n    \"swell_target\": {\n      \"debounce_time\": 8,\n      \"socv\": 3.2\n    }\n  },\n  \"Weekly\": {\n    \"controller\": {\n      \"Ki\": 0,\n      \"Kp\": 3.33e-02,\n      \"u_max\": 1,\n      \"u_min\": 0\n    },\n    \"settings\": {\n      \"shape\": {\n        \"a\": 0,\n        \"b\": 0,\n        \"c\": 46.15384615\n      }\n    },\n    \"enable\": 0,\n    \"interval\": 604800\n  },\n  \"control_effort_table\": {\n    \"control_effort\": [0,0.1,0.2,0.3,0.4,0.5,0.6,0.7,0.8,0.9,1],\n    \"debounce_time\": [8,8,8,8,8,8,8,8,8,8,8],\n    \"socv\": [3,3.1,3.12,3.13,3.14,3.15,3.16,3.17,3.18,3.19,3.2]\n  },\n  \"final_budget_target\": 12000,\n  \"final_time\": 157680000,\n  \"max_interval\": 1209600,\n  \"grace_period\": 1209600,\n  \"grace_period_budget_target\": 3000,\n  \"control_effort_slew_rate_up\": 0.02,\n  \"control_effort_slew_rate_down\": 0.1,\n  \"weights\": [[[0,1,1],[0,1,1],[0,1,1]],[[0,1,1],[0,1,1],[0,1,1]],[[0,0,0],[0,0,0],[0,0,0]]],\n  \"config_version\": 1\n}\n"
- "\n{\n  \"Lifetime\": {\n    \"controller\": {\n      \"Ki\": 8e-10,\n      \"Kp\": 0.0005,\n      \"u_max\": 1,\n      \"u_min\": 0\n    },\n    \"settings\": {\n      \"shape\": {\n        \"a\": 0,\n        \"b\": 5.7519e-05,\n        \"c\": 2.9304e+03\n      }\n    },\n    \"enable\": 1,\n    \"interval\": 86400\n  },\n  \"ProjectedLifetime\": {\n    \"controller\": {\n      \"Ki\": 0,\n      \"Kp\": 2.00e-03,\n      \"u_max\": 1,\n      \"u_min\": 0\n    },\n    \"settings\": {\n      \"epsilon\": 0.000694444,\n      \"lambda\": 0.85\n    },\n    \"enable\": 0,\n    \"interval\": 86400\n  },\n  \"SafeHarbor\": {\n    \"aged_target\": {\n      \"debounce_time\": 8,\n      \"socv\": 3.2\n    },\n    \"swell_target\": {\n      \"debounce_time\": 8,\n      \"socv\": 3.2\n    }\n  },\n  \"Weekly\": {\n    \"controller\": {\n      \"Ki\": 0,\n      \"Kp\": 3.33e-02,\n      \"u_max\": 1,\n      \"u_min\": 0\n    },\n    \"settings\": {\n      \"shape\": {\n        \"a\": 0,\n        \"b\": 0,\n        \"c\": 46.15384615\n      }\n    },\n    \"enable\": 0,\n    \"interval\": 604800\n  },\n  \"control_effort_table\": {\n    \"control_effort\": [0,0.1,0.2,0.3,0.4,0.5,0.6,0.7,0.8,0.9,1],\n    \"debounce_time\": [8,8,8,8,8,8,8,8,8,8,8],\n    \"socv\": [3,3.1,3.12,3.13,3.14,3.15,3.16,3.17,3.18,3.19,3.2]\n  },\n  \"final_budget_target\": 12000,\n  \"final_time\": 157680000,\n  \"max_interval\": 1209600,\n  \"grace_period\": 1209600,\n  \"grace_period_budget_target\": 3000,\n  \"control_effort_slew_rate_up\": 0.02,\n  \"control_effort_slew_rate_down\": 0.1,\n  \"weights\": [[[0,1,1],[0,1,1],[0,1,1]],[[0,1,1],[0,1,1],[0,1,1]],[[0,0,0],[0,0,0],[0,0,0]]],\n  \"config_version\": 1,\n}\n"
- "SOCVDebounce"
- "SOCVVoltage"
```
