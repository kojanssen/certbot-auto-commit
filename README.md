# certbot-auto-commit
commit changes in certificates as posthook in the certbotscript.

The changes in the filesystem under /etc are to be committed in the post-hook of the script. But only these; if there are other changes then a warning will be sent.
