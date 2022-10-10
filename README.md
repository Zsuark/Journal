# Journal
A daily journal - to help keep your notes and day organised

Implemented using Go and microservices.

## Motivation
 * Learn Go
 * Microservices practice
 * Stay organised


## General description
 * A user make entries into the journal
 * Each entry in the journay is indexed by date
 * An entry, could be TODO items or notes which may have drawings or images attached.
 * Previous days TODOs are automatically brought forward
   - after a week, the TODO is reviewed and discarded, merged or set to appear later
 * The user interface includes:
   - make an entry
   - display TODOs
   - display TODOs completed today
   - display notes
   - edit/update today's notes
   - Search notes
