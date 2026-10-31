# Changelog

## 1.5 (2026-10-31)

- **Story time:** real dates, plain days ("Day 3") or a calendar of your own, with months, weekdays, eras and leap years, plus time labels like "The Long Winter". A chapter's Calendar switch picks its time from the story's calendar, with an optional end. Scenes can have their own time (a clock on the scene-break label), and the Story timeline shows them indented, marks flashbacks and flags anything outside the story's span. Times can go into the Word document, e-book and web page.
- **Undo for everything in the text:** Ctrl+Z and Ctrl+Shift+Z / Ctrl+Y now cover Quire's own changes too (speaker marks, passage tags, comments, alignment, Fix quotes, scene labels, Clear formatting), in order with your typing, in every browser. Messages after those actions have an Undo button for phones.
- **Who says this, faster:** the panel stays open while you mark line after line, Next unmarked line jumps ahead, and with a keyboard 1–9 pick a speaker and N moves on. Marks show as a dotted bar in the right margin instead of underlining the text (Options → Text → Speaker marks). Select text and remove every mark inside it at once.
- **Links:** the [[ ]] button makes the selected name a link, or starts an empty one with suggestions; typing [[ does the same. Links also find entries by their "also known as" names.
- **Your own fields** on characters, places, notes, chapters and story arcs: one line, longer text, a choice list, a number or a date, for one story or all of them.
- **Milestones** (Story ▾ → Milestones): name the current version of every chapter at once, compare a chapter with it, or bring a chapter back.
- **Several chapters at once:** Select, tick (Shift-click for a range), then set status, type, tags or time, move them to the trash, or drag them as a block.
- **Title image** on the story overview, usable as the e-book cover (or behind the title) and at the start of the Word document and web page.
- **Senses in Voices** count whole words with a much larger word list, so "human" no longer counts as a sound and smells are no longer crowded out. Shown per 1,000 words, with the words counted, and you can add your own sense words.
- **Clear formatting** keeps the font and comments and removes everything else, including speaker marks and passage tags.
- **Menus:** the viewpoint and cast menus list protagonists (and deuteragonists) first, then antagonists, then the chapter's cast, A–Z within each.
- **Relationship tags:** a switch on a tag's page decides whether it counts as a relationship, for tags like Hurt/Comfort.
- **Sidebar:** the New button, status strip and order switch stay in place while the chapter list scrolls.
- **The download** no longer contains any of the code the hosted copy in Claude uses, and carries a security rule that blocks every connection except Google Fonts. Help and the README explain what the file can contact.
- Printing a story shows video and music embeds as links instead of loading the players.
- Fixed: the Point of view field overlapped itself when a chapter had two or more viewpoints.
- Fixed: on phones under 400 px, the Reference and Watch words buttons above the text were empty.
- Help explains saving over your file in Firefox, and the difference between speaker marks and scene labels.

## 1.4.2 (2026-10-29)

- Fixed: changing the font of text that already had one (from Quire's font menu, or pasted from Google Docs or Word, which bring Arial or Times New Roman along) looked right but didn't save, so the old font came back on reopening. "Default font" now removes a pasted font for good, too.
- Quire now uses American English throughout: color, center, favorite and so on. The Bin is now called Trash. Saved files and backups are unchanged.
- Punctuation stats call ( ) parentheses.

## 1.4.1 (2026-10-28)

- **Watch words above the text:** a Watch words button sits above every text, and watch words can now be set for one chapter (or note or sheet) only, for things that matter there for a while.
- **Buttons above the text:** Focus mode and full screen sit together again. Options → Display → Buttons above the text… changes the order of the buttons and which ones show.
- **Toolbar:** alignment and indent now sit right after the headings.
- **Highlighting** now covers arc beat chips too, which were hard to read on dark themes.
- The French quote style's label shows the narrow spaces Quire types inside « ».
- Fixed: Help gave Quire's size as 770 KB.

## 1.4 (2026-10-28)

- **Reference panel:** the Reference button above a text keeps a character, place, note, story arc or another chapter in view while you write, with the chapter's own cast and places listed first. Short fields can be edited in the panel. On wide screens it sits beside the text and stays open from chapter to chapter; on smaller ones it slides over the text.
- **Go to (Ctrl+K):** type a few letters to jump to any entry, tag or story, or to run a command such as New chapter, an export or a theme. Shift+Enter shows the chosen entry in the reference panel.
- **Cast check:** under a chapter's characters and places, Quire lists those named in its text but missing from the lists, with how often they appear, and adds them with one click. It matches names exactly, plus the names under Also known as, which places now have too.
- Fixed: Help said Quire was about 650 KB.

## 1.3 (2026-10-28)

- **Trash:** deleting a chapter, sheet, note, story arc or whole story moves it to the trash (Story ▾ → Trash) for 30 days, with Undo right after. Restoring brings it back with its links, viewpoints, cast lists, arc beats and speaker marks. The trash stays in the saved file but out of backups, exports and search.
- **Import from Word:** Import chapters reads .docx files. Chapters start at headings (in any language of Word) or at lines like "Chapter 3"; italics, bold, centered lines, lists, links, images and scene breaks come along, Word comments become Quire comments, tracked changes count as accepted and footnotes go at the end of their chapter.
- **E-book export:** an EPUB for e-readers and reading apps, with a table of contents, scene breaks, images, a title page and an optional cover with the title and byline. Checked against EPUBCheck, the official validator.
- **Deadline:** add a date beside the story's target length to see the words a day it takes, today's progress toward that share, and where your recent pace would land.
- **Chapter cards** show each chapter's viewpoint, places and arc beats, and can show the whole synopsis.
- Fixed: low contrast on "(optional)" in the Word document settings.

## 1.2 (2026-10-27)

- **Your own themes:** pick four colors (paper, text, background and accent) or start from a preset; Quire works out the other shades, previews them live and checks the text stays readable. Save as many named themes as you like.
- **Word document:** a second Word export that looks like your story, with your typeface, size and spacing, real Word headings, book-style or spaced paragraphs, scene breaks, images, an optional title page and page numbers. Word manuscript is unchanged.
- **Watch words:** list words and phrases to notice, for every story or just one, with an optional note. Typing one shows a small note beside the line that fades by itself; the Prose checker marks them all.
- **Voices** (Stats): how each viewpoint character narrates, compared side by side, with distinctive words, favorite phrases, sentence rhythm, senses and chapter-by-chapter drift.
- **Who says this:** mark a line of dialogue with its speaker from the toolbar. Once a line is marked, Voices compares how your characters speak, from the lines you've marked only. Quire never guesses a speaker.
- **Also known as** on character sheets, for other names a character goes by.

## 1.1 (2026-10-26)

- **Encryption:** optional password protection for backups and for the saved file, with AES-256-GCM and a key derived by PBKDF2-SHA-256 (600,000 rounds), all done by the browser. Encrypted files open behind a lock screen.
- **Password meter:** rates a new password as you type, estimates how long guessing it would take, and warns about common passwords, years and names from your own story.
- **Scene viewpoints:** with two or more viewpoint characters, a label at the start of a chapter and at each scene break says whose scene it is. The chapter shows how its words divide between them, and Stats uses the same split.
- **Status colors** (Options → Display): chapters colored by status, with a strip of the whole manuscript, each block as wide as its chapter.
- **Tag suggestions:** the tag box suggests existing tags and entries as you type; picked entries become linked chips, listed under "Tagged in" on the entry.
- **Search in Help:** a search field at the top of Help shows only the passages that match, marks the words, and steps through them with Enter or the arrow buttons.
- **Fixes from stress testing:** text typed in the last instant before closing or reloading the page is no longer lost; damaged or hostile backups can't break the page; files that only pretend to be images are refused; very long words no longer push exported web pages and the Tags page sideways; story arc menus fit 320-pixel phones; a save error on one entry is no longer hidden when another saves fine.

## 1.0 (2026-10-24)

First public release.

- **Writing:** rich-text editor with book-style indents, smart quotes in three styles, focus mode in two stages with full screen, typewriter scrolling, six themes, and picking up where you left off.
- **Sprints and targets:** timed sprints with word goals, word targets per chapter and story, a progress bar at the bottom of the screen, and a word count for any selection.
- **Drafts and history:** drafts with change-by-change merging that can be undone, and version history with replay and named versions.
- **Planning:** sheets for the story, chapters, characters, places and notes; story arcs on a tension curve; `[[links]]` with backlinks; tags for entries, images and passages, with passage threads in story order.
- **Revising:** a Prose checker (readability, adverbs, passive voice, wordy phrases, word echoes, dialogue), comments, and stats from basic to in-depth.
- **Saving and sharing:** everything saved inside the HTML file; exports to Word manuscript format, web page, Markdown, plain text, print and PDF; optional AO3 sharing; backups and chapter import.
- **Example story:** two chapters of Conan Doyle's "The Red-Headed League" with every feature filled in.
