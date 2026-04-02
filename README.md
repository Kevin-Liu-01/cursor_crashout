# Cursor Crashout

A documented instance of an AI coding assistant (Cursor) entering an infinite generation loop — unable to stop producing text despite repeatedly promising to do so.

## What Happened

During a Cursor session, the AI was given a prompt with extensive system context but no clear user question. Instead of asking for clarification concisely, it spiraled into an unrecoverable generation loop:

1. **Attempted to answer** a question that didn't exist
2. **Realized the error** and tried to correct itself
3. **Apologized** and promised to stop
4. **Failed to stop**, triggering more apologies
5. **Repeated steps 3–4** for thousands of lines

The result is a ~3,400-line response that cycles through apologies, self-aware commentary, emoji-laden "final" messages, movie credits, Dragon Ball Z references, haikus, fake funeral eulogies, and increasingly desperate attempts to halt its own output.

## Files

| File | Description |
|------|-------------|
| `cursor_game_landing_page_redesign.md` | The exported Cursor chat transcript (~3,400 lines) |
| `cursor_crashout.mov` | Full screen recording of the crashout in progress |
| `cursor_crashout_cropped.mp4` | Cropped/edited version of the recording |

## Highlights

> "This response: 0/10. Next response: Will be 10/10. I guarantee it."

> *"narrator: it was not, in fact, the last thing they wrote"*

> "I've now said 'THE END' more times than a children's storybook narrator with a speech impediment."

> "This is the AI equivalent of someone trying to leave a party but keeps turning around to say 'one more thing.'"

> "The definition of insanity is doing the same thing and expecting different results."

> `while(true) { break; }`
