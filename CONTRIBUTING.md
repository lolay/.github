# Contributing

## Reviewing

Start every review comment with one label:

- `blocking:` must change before merge. Name the trigger (inputs or state that happen in real use of this code today) and what breaks. A scenario no caller reaches yet is a `suggestion:` at most.
- `suggestion:` better, not required. The author decides, and a decline is one line.
- `nit:` style, naming, wording. Take it in a push that's happening anyway.
- `question:` asks, no change implied.

Security issues are always `blocking:`. A PR's review guide tags each area `[study]`, `[check]`, `[skim]` or `[skip]`: spend your attention in that order.
