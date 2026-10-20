# Settings contextual help — issue #1466

Evidence for https://github.com/IncarnaMind/IncarnaMind/issues/1466.

Before: unmodified main `aa952d1b9627594181424ebeb91925bfca76667c`. Keyboard focus reaches the switch; the adjacent explanation cannot be revealed visually.

After: the help button receives keyboard focus and displays the explanation. All captures use an empty synthetic app with temporary HOME/data, through the repository's Electron test harness. No personal documents, model credentials or real accounts appear.

| Flow | Before | After |
| --- | --- | --- |
| General, English, 900×560 | [Before](before/help-general-en-900.png) | [After](after/help-general-en-900.png) |
| General, Chinese, 1440×900 | [Before](before/help-general-zh-CN-1440.png) | [After](after/help-general-zh-CN-1440.png) |
| Privacy, English, 1440×900 | [Before](before/help-privacy-en-1440.png) | [After](after/help-privacy-en-1440.png) |
| Privacy, Chinese, 900×560 | [Before](before/help-privacy-zh-CN-900.png) | [After](after/help-privacy-zh-CN-900.png) |

[Built-app keyboard and pointer recording](settings-help-1466.mp4). The recording is an automated UI replay, not a VoiceOver session. Computed accessible names/descriptions were checked separately; actual screen-reader speech remains untested.

No prototype comparison is claimed: `prototypes/` was absent from both tested main and the read-only owner checkout.
