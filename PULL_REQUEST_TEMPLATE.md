### Summary

This pull request removes the simple event management feature from the codebase due to issues it was causing. The code is now restored to its original state with only activity management endpoints.

### Changes
- Removed all event management endpoints and data structures from `src/app.py`
- Reverted to the original activity management API

### Motivation
- The event management feature was causing issues and is not ready for production use.

---

Closes #14
