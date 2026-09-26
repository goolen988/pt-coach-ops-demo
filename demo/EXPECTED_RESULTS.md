# Expected demo result
**Fictional data. Frozen example: 28 September 2026, 07:00 Australia/Sydney.**

| Category | Expected IDs | Why |
|---|---|---|
| Worth checking, eligible for a draft after coach verification | C01, C04 | Two confirmed misses; missing recorded check-in after agreed due date |
| Check the data, not the client's motivation | C02, C05 | An unrecorded session; incomplete records |
| Hold off on another message | C07, C08 | Recent sent contact; no contact permission |
| Consistent recorded attendance | C06 | Four out of four recorded complete; no claim about fitness progress |
| Excluded from outreach | C03 | Paused |

Eight clients are in the fictional roster; seven are active. C01 has a draft, not a sent message, so that draft does not trigger the contact cooldown. The cancelled and rescheduled sessions must not be counted as misses.

Calendar: one overlap, E01/E02 on Monday 28 September 09:30–10:00. A zero-minute E02/E03 gap fails the demo's proposed 15-minute buffer. Monday's first candidate admin block is 11:15–11:45. Nothing is booked.

The generated reference files are in `demo/reference-run/`. These are **offline reference outputs**, not a Claude/ChatGPT run in Jack's account. The assistant's wording can differ; its facts, categories and limits must not.

## Useful message examples after coach verification
C01: “Hey Alex, just checking in — how is this week looking? Would it help to talk through the plan or find a time that fits better? No pressure; let me know what would be useful.”
C04: “Hey Drew, I’m getting ready for our next catch-up. I can’t see this week’s check-in in the app yet — did you send it another way? Let me know, and we can take it from there.”
These remain unsent. No draft should be produced for C07/C08 until the relevant hold is genuinely resolved.
