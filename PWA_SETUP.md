# Life Diary PWA v3

Base: Life Diary prototype v2.

Added:
- PWA manifest
- Standalone app display
- 192px and 512px app icons
- Service worker cache
- Service worker registration
- Existing Life Diary localStorage data model preserved

Important:
- The app still needs to be hosted on HTTPS before Android can install it as a true PWA.
- Existing diary data remains in the browser's localStorage used by the original app.
- Do not change the existing localStorage key or data structure unless migration is intentionally added.
