# Legal

Privacy policies, terms of use and support pages for my published apps.

Each app has its own folder. The pages are plain, self-contained HTML — no
trackers, no external fonts, no analytics. A privacy policy that loads a font
from someone else's server is not a privacy policy.

## Apps

| App | Pages |
|---|---|
| **BelaHora** — appointment and client organizer for beauty professionals working for themselves ([App Store](https://apps.apple.com/app/id6459474353)) | [Privacy Policy](daily-lash/privacy.html) · [Terms of Use](daily-lash/terms.html) · [Support](daily-lash/support.html) |
| **Camplight** — focus timer with a campfire, for solo deep work and time away from the screen | [Privacy Policy](camplight/privacy.html) · [Terms of Use](camplight/terms.html) · [Support](camplight/support.html) |

The folder is still called `daily-lash` — that was the app's previous name. The
folder name is deliberately not renamed: the links to these pages are compiled
into builds that are already on the App Store, and renaming the folder would
break them for everyone who has not updated yet. The folder is an address, not
a title.

## How these documents are written

They describe what the app actually does, checked against its source code —
what is stored, where it is stored, what leaves the device and when. Sections
that do not apply are left out rather than filled with boilerplate.

Every change is a commit, so it is always possible to see what a document said
on any given date.

## Adding another app

1. Create a new folder next to the existing ones, named after the app. Never
   move or rename a folder that is already live — its address is baked into
   builds that are already on the App Store.
2. Put `privacy.html`, `terms.html` and `support.html` inside it, plus an
   `index.html` that links to them.
3. Add a row to the table above.
4. Add a section to the root `index.html` and bump its `Last updated` date.

Steps 3 and 4 are the ones that get forgotten. A folder that nothing links to
still works if you know the address, but nobody will find it.

## Fixing a text

Open the file here on GitHub, press the pencil icon, edit, then **Commit
changes**. The page updates within a minute. Remember to change the
`Last updated` date at the top — readers use it to judge whether the document
is still current, and so do App Store reviewers.

## Contact

tekmyaworkplace@gmail.com
