MCP Setup Challenge – Documentation

1. What I Did
- Created a public GitHub repository for the MCP setup challenge.
- Selected VS Code as my preferred IDE (planned).
- Created an initial AI agent rules file at `.github/copilot-instructions.md`.
- Defined basic behavior, style, and workflow rules to guide the AI agent.

 2. What Worked
- Creating the repository and rules file was straightforward.
- Writing explicit rules helped clarify how I want the AI assistant to behave.

 3. What Didn’t Work / Challenges
- At the beginning, I did not clearly understand what MCP was or how the setup worked.
- The purpose of MCP and how it integrates with the IDE was initially confusing.

 4. How I Approached the Challenge
- I broke the task into smaller steps instead of trying everything at once.
- I focused first on understanding the problem before attempting the MCP setup.
- I planned to document every step, including confusion and failures.

 5. Insights Gained (So Far)
- AI agents behave better when given clear instructions and boundaries.
- A rules file is an effective way to align the AI assistant with my thinking style.

 6. MCP Setup – Installation Attempt
 Command Executed
```bash
npm install -g @modelcontextprotocol/cli

### Result
The installation did not complete successfully. npm returned an error indicating that the MCP CLI package could not be found in the public npm registry.

### Error Details
- npm error code: E404
- Error message indicated that `@modelcontextprotocol/cli` does not exist in the npm registry.
- npm also mentioned that the access token may have expired or been revoked.

### Analysis
Based on the error message, it appears that the MCP CLI is not available as a publicly distributed npm package. This suggests that MCP may be managed internally, integrated directly into supported IDEs, or configured through server definitions rather than a global CLI installation.

### Troubleshooting Steps
- Verified that npm was installed and working correctly.
- Confirmed stable internet connectivity.
- Re-ran the installation command to rule out transient errors.
- Reviewed npm output to understand the root cause of the failure.

### Insights Gained
- Not all development tools are installed via global npm commands.
- Modern AI tooling may rely on IDE-level integrations instead of standalone CLIs.
- Properly documenting errors and analysis is an essential part of technical problem solving.

### MCP Verification

After adding the Tenx MCP server and authorizing via GitHub:
- The server was successfully connected in VS Code.
- Switched Copilot Chat to "Agent" mode.
- Verified that 55 tools were available to the AI agent.
- This confirms that the MCP server is fully operational and logging interactions correctly.
- This completes the MCP setup and integration tasks for the TRP-1 challenge.
