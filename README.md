# deck-writer

The note type and Anki package writer behind **World in Flashcards**, a collection of geography flashcards: every
country, territory and first-level subdivision, with its map, flag, emblem, capital, native name and pronunciation.

This package takes finished notes (code, GUID, fields, tags) and their media files, and writes an Anki `.apkg` with
stable model, deck and note IDs, so re-importing a newer deck updates your notes in place rather than duplicating them.

It is used by the World in Flashcards website's export and by the generator that builds the decks.

Status: being extracted; not yet usable.

## Licence

The code is MIT-licensed. The flashcard content it packages (maps, flags, emblems, recordings, text) carries its own
terms, credited per note in its `source` field; some of it is for non-commercial use only.
