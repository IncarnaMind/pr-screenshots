# Public record-cite evaluation (#1709)

Run 2026-10-28T01:00:24.654Z at 5862dad34, 107 s, with anthropic/claude-sonnet-5-5. the app's public core checkClaim, with record-cite resolution and judgement.

Set: 2 public court Documents, 8 claims, 10 expected cite results. Matched 10 of 10.

Model: 26 requests, 198219 input and 2735 output tokens, 51.7 s of requests, $0.1946 at the core's count.

## Cases

| Id | Interface | Overall | Cite outcomes | Misses |
| --- | --- | --- | --- | --- |
| en-page-supported | en | supported | ECF No. 41 at 3: supported | 0 |
| zh-page-supported | zh-CN | supported | ECF No. 41 at 3: supported | 0 |
| en-page-partly | en | contradicted | ECF No. 41 at 3: partly | 0 |
| en-wrong-page-nearby | en | supported | Dkt. 41 at 2: not-found | 0 |
| en-id-wrong-page | en | supported | ECF No. 41 at 3: supported; Id. at 2: not-found | 0 |
| en-supra-supported | en | supported | ECF No. 41 at 3: supported; supra: supported | 0 |
| en-ambiguous-source | en | supported | ECF No. 41 at 3: choose | 0 |
| en-docket-not-found | en | supported | ECF No. 42 at 3: not-found | 0 |

## Every miss

None.
