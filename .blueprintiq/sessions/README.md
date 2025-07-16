# Session Management

This directory manages BluePrintIQ conversation sessions and their state.

## Structure

- `active-session.json` - Current active session with context
- `history/` - Historical session data and conversation archives

## Session Lifecycle

1. **Session Start**: New session created with project context
2. **Conversation Turns**: Each interaction recorded with metadata
3. **Session Checkpoint**: Periodic state saves for restoration
4. **Session End**: Final state archived to history

## Session Restoration

BluePrintIQ can restore conversation context from any session, enabling:
- Seamless project resumption across devices
- Team collaboration with shared context
- Complete architectural decision history

*Managed by BluePrintIQ Session Manager*
