# Plan - MojoHub Improvements

1.  **Carousel Stability:** Prevent rapid clicking from breaking the slide transitions.
    - [x] Add `isTransitioning` state.
    - [x] Lock navigation during transitions.
    - [x] Clean up old slides more robustly.

2.  **Terminology Update:** "Contexts" -> "Topic(s)".
    - [x] Update UI label "All Contexts" -> "All Topics".
    - [x] Update logic for dynamic count text.

3.  **Layout Adjustment:** Move Actions.
    - [x] Move "Active Topic" count and "Add Book" button out of the global actions tile.
    - [x] Place them between the Search tile and the Filter/Library tile.
    - [x] Use a "Book with +" icon for the add button.

4.  **Accordion Functionality:**
    - [x] Convert tiles to `<details open>`.
    - [x] Add chevron to header (summary).
    - [x] Ensure tiles are expanded by default.
    - [x] Allow collapsing/expanding via header click.
    - [x] Preserve "Activate Topic" functionality via specific click target (topic name).

5.  **Visual Polish:**
    - [x] Make "Saved" heart icon solid white when active.
