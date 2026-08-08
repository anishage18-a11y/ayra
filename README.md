Aira Legal Pages
================

Files:
- index.html
- terms.html
- privacy.html

IMPORTANT BEFORE PUBLISHING
1. Replace Anish.
2. Replace Anish bot.
3. Replace Bangladesh in Terms of Service.
4. Review the documents with a qualified lawyer if you will operate Aira commercially or serve users in regulated jurisdictions.
5. Keep the privacy policy publicly accessible and linked in your Discord Developer Portal.

The pages were tailored to the supplied Aira codebase, including:
- Discord User/Guild IDs
- chatbot history
- 24-hour conversation memory cleanup
- personal personality storage
- server chatbot settings
- Groq API inference
- deletion commands and deletion-request workflow

Important implementation note:
The current code has a separate `chatbot_history` table that is NOT removed by `/ai conversation-clear`. The privacy policy therefore describes that separately and provides a deletion-request route.
