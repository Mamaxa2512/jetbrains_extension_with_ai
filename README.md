# MindSaver AI Context Restorer
A JetBrains IDE plugin that generates a "Resume Brief" using AI so you instantly remember what you were working on after a meeting, weekend, or context switch.
## Why is it unique?
Most AI plugins are code generators or chat bots. **MindSaver** acts as your proactive context manager. Instead of you asking "how do I fix this code?", MindSaver tells you "You were fixing an NPE in UserService, you added validation but haven't covered it with tests yet." 
## Features
- **Instant Resume Brief:** Generates a summary of your uncommitted changes, open files, and recent edits.
- **Privacy-First:** Designed to work with Local LLMs via Ollama to keep your proprietary source code safe.
## To test the MVP
1. Make sure you have Gradle and JDK 17 installed.
2. Run `./gradlew runIde` inside the project root.
3. Once the Sandbox IDE opens, open a sample project and open a few files.
4. Go to **Tools -> Generate Resume Brief** (or use `Ctrl+Alt+Shift+R`).
5. A popup will emulate the AI generating your context restore brief.
