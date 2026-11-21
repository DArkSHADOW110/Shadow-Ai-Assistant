# Shadow AI Assistant — Windows Downloads

This repository contains **application downloads and usage instructions only**. The application source code is private.

## Download

Open [Releases](https://github.com/DArkSHADOW110/Shadow-Ai-Assistant/releases) and download the **ShadowAssistant-0.3.0-win-x64.exe** portable application. This EXE bundles the required runtime; no Node.js, npm, or separate DLL folders are needed.

## Use the app

1. Quit any older copy from its tray menu, then open the downloaded EXE.
2. Open Gemini or ChatGPT in Settings, sign in directly, select the active provider, and save Settings.
3. Minimize the app to run in the background. Reopen Settings from the tray or Ctrl+Alt+S.

| Shortcut | Action |
| --- | --- |
| Ctrl+Alt+B | Send selected/copied question text with pending files |
| Ctrl+Alt+I | Add selected File Explorer files, copied files, or a clipboard screenshot to the pending queue |
| Ctrl+Alt+V | Paste the completed answer |
| Ctrl+Alt+S | Open Settings |

**Adding files does not send them immediately.** Add files, then enter or select/copy your question and use the send action. Ordinary Ctrl+C/Ctrl+V remain independent of the assistant.

The small mouse-following circle is blue while working, green on success, and red on failure. Add files is visible near the top of Settings. File limits: 10 files, 20 MB each, 100 MB total; the selected provider must support the format.

## Notes

Windows x64 only. This unsigned, experimental client is not affiliated with Google or OpenAI. Embedded-browser login, file uploads, network errors, account limits, and website changes can affect operation. The app does not bypass login checks. Sign in and test with your own account.

Answers are pasted as plain text with their existing line breaks and indentation. Undo behavior depends on the destination editor. The clipboard is used temporarily and previous content is restored where supported. Use Copy answer to clipboard for normal repeated Ctrl+V.

Prompts/files go to the provider selected in Settings under its privacy/storage policies. There is no background clipboard listener. Source files selected from disk are not deleted. Use the tray menu to Quit or Restart.