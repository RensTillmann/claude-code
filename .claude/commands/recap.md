<command name="recap">
  <description>Summarize conversation for context preservation</description>
  <prompt>Our conversation is approaching the context limit. Please create a comprehensive technical summary that I can paste at the start of a new Claude Code session to seamlessly continue our work.

Write this as if you're briefing a new instance of yourself who has no prior knowledge of our conversation. Include:

1. **Project Overview**: Core purpose, goals, and architecture
2. **Current Implementation State**: 
   - All files we've created/modified with their roles
   - Key functions, classes, and their relationships
   - Dependencies, packages, and environment setup
   - Directory structure if relevant
3. **Recent Work Session**: 
   - What we accomplished in this conversation
   - Code changes we made and why
   - Any decisions or trade-offs we discussed
4. **Active Issues**: 
   - Current bugs or errors we're debugging
   - Unresolved problems and what we've tried
   - Any warnings or edge cases to watch for
5. **Working Code**: 
   - Latest version of code we're actively modifying
   - Any code snippets that aren't saved to files yet
6. **Immediate Next Steps**: 
   - What we were about to implement when we stopped
   - Specific tasks or features queued up
   - Any context needed to resume mid-task

Make this summary self-contained and detailed enough that you could resume exactly where we left off.</prompt>
</command>
