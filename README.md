# treasurehunt-insta-media

Public media host for [treasurehunt-insta-bot](https://github.com/dindonero/treasurehunt-insta-bot).

Each day the bot commits that day's post image/video to `posts/`. The files are
served via `raw.githubusercontent.com` so Instagram's Graph API can fetch them
from a public URL at publish time. This repo intentionally contains only
generated post media.
