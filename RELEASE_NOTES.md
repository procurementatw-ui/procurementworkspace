# ATW Source v106 — ATLAS conversation repair

The browser icon is restored to the approved ATLAS head at the user's request. One favicon set is retained, with no inherited footer icon overriding it. The previous ATW page colors, compact bars and all 84 modules remain.

## Questions and language

Selecting C enables a free-question conversation. Send clicks, Enter and form submission use one early dispatcher before the legacy guided listeners. The Send click no longer depends on a later native form submission event, which can be cancelled by another handler or unrelated required controls. Shift+Enter and IME composition do not submit. A/B guided actions remain available. Answers use the existing ATW Source guides and permitted transaction data; unknown questions receive a clarification. This is a deterministic assistant, not a general language model.

The visible language selector updates the shared language immediately. Existing managed free answers are regenerated in that language from their original question and permitted context. Their user-authored question text is preserved. The C prompt, guided answers, navigation and following replies also change. Main-content translation no longer skips the whole page because the navigation shell has a custom-render marker. Markers inside a module and user-entered values are preserved. No outside translation service is used; arbitrary source-document prose is subject to the document reader's existing translation limits.

## Audio

The previous audio path chose a generic recorded cue ahead of the answer. It now speaks the actual composed answer with a matching device-local voice. Recorded guidance is used for a recognized FAQ topic when it matches that topic, and for explicit conversational prompts. The 87 bundled MP3 assets remain unchanged. Recordings cannot speak arbitrary transaction amounts or newly typed prose.

If the selected language has no permitted device-local voice, a dynamic answer remains in text rather than playing an unrelated recording, another language or an online voice. The availability note and Replay control expose that state. Matching voices that appear later can resume only the current pending answer. Sending a new answer, changing language or changing identity cancels earlier playback; mute remains respected. Replay follows the newly translated answer. Real voice availability and perceived voice quality still depend on the browser/device. No live external speech or AI provider is enabled.

## Validation and operational boundary

VALIDATION.json records the final checks. New cases exercise actual language-selector change events, Send interception, native validation interference, transcript translation, IME/Shift+Enter, local speech correspondence, missing-voice behavior, delayed voice availability, overlap and mute. These run application code in a DOM harness with selected browser APIs simulated. Browser reproduction could not be completed: file URLs were blocked by Browser Use policy, and the localhost preview connection timed out. Actual audio listening, full native-browser interaction and a physical phone were not verified.

The original source records, current-PIC calculations, approvals, templates and business workflows are preserved. No publication or push was performed. The archive is a static frontend; shared official operation still requires ATW Source server authentication, server-side access checks, shared persistence, document storage and verified notification/integration services.
