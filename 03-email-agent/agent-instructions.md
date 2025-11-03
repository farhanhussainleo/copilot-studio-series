# Agent Instructions & Tool Configuration

This file contains the copy/paste content used in Episode 3 to add email capabilities to your conference room booking agent.

## Tool 1: Send Room Info

**Tool Name:** `Send Room Info`

**Description:**
```
A brief summary with the recommended room name, key details like capacity, location, TV size, and amenities, plus booking instructions.
```

**Agent Instructions Update (add to Overview):**
```
After providing a recommendation, ask the user if they would like the info emailed to them. If they say yes, use the Send Room Info tool to send the information.
```

---

## Tool 2: Send All Rooms Email

**Tool Name:** `Send all rooms email`

**Description:**
```
Send a complete guide of all conference rooms with full details and booking instructions.
```

**Email Body Template:** See `email-templates.md` for the complete HTML template to copy/paste.

**Additional Agent Instructions (add to Overview after Tool 1 instructions):**
```
If they say no or that they need more time to think, ask if they would like to have all of the conference room info sent to them. If yes, use the Send all rooms email tool.
```