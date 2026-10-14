## IMDPersistence

> `/System/Library/PrivateFrameworks/IMDPersistence.framework/IMDPersistence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3022e4` | `0x3038ec` | **`+0x1608`** |
| `__TEXT.__cstring` | `0x5eba4` | `0x5ed44` | **`+0x1a0`** |
| `__DATA.__data` | `0x3bb0` | `0x3be0` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x3879` | `0x38a9` | **`+0x30`** |
| `__TEXT.__const` | `0xc3d0` | `0xc3f0` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x36c4` | `0x36d0` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2a10` | `0x2a18` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x9dc4` | `0x9dcc` | **`+0x8`** |

### Other Changes

```diff

-1491.200.95.0.0
+1491.200.101.2.5

-  Functions: 13842
+  Functions: 13847

-  CStrings:  7543
+  CStrings:  7560
CStrings:
+ "\n          FROM "
+ "\n          ORDER BY "
+ "\n        )\n    )"
+ "\n      GROUP BY "
+ "\n      INNER JOIN "
+ " <= span.last_date"
+ " = (\n          SELECT "
+ " = span.conversation\n            AND "
+ " = span.conversation\n        AND "
+ " AS MATERIALIZED (\n      SELECT "
+ " AS conversation, "
+ " AS conversation, MAX("
+ " AS threshold_id\n      FROM "
+ " ASC\n          LIMIT 1 OFFSET "
+ " span\n      INNER JOIN "
+ " threshold\n      WHERE threshold.conversation = "
+ ") AS last_date\n      FROM "
+ "fl_span_conversations"
+ "fl_thresholds"
+ "ranked"
- "\n          ORDER BY threshold_date ASC, threshold_id ASC\n          LIMIT 1 OFFSET  ? \n      ) threshold\n      WHERE ("
- " AS threshold_id\n          FROM "
- "NOT EXISTS (\n      SELECT 1\n      FROM (\n          SELECT "
```
