# Noita eye message grid

A single-file viewer for the 9 Noita eye messages (trigram values 0–82). Open: https://binaryalgorithm.github.io/noita-eye-grid/

- **"What we know"** (top of the page) lists every result with a confidence grade:
  - certain;
  - strong (passes a calibrated 1-in-1000 null);
  - favoured (odds given);
  - not visible in the ciphertext;
  - excluded / searched with nothing found.
- Hover a value to light up every copy of it. Click a cell to pin it. Drag the message names to reorder the rows.
- Slots, shared openings and shifted passage copies are marked. Links that failed the 1-in-1000 calibration are drawn dashed or labelled TENTATIVE.
- Repeat pattern: a repeat inside a passage that recurs in every copy gets the same colour and letter in each copy. Hover one to see the whole set.
- The **hypothetical shape sample** under the grid shows invented words placed on the real structure (lengths, shared text, copy offsets, number fields). It is an illustration, not a decode.

Status (2026-10-22): unsolved; no plaintext is known.
- Every certified search for a compact key (a nameable rule plus a natural start deck) under the "cut at the read seat" model found nothing.
- A random rearrangement would be determined by the messages in principle, but it provably can't be found by search.
- Open lead: diverged messages share cards at the same position more often than cut-type models allow. A shared-update model ("XGAK", see [FrobtheBuilder's field notes](https://frobthebuilder.github.io/eye-cipher-field-notes/)) reproduces this.

Community research: Noita Discord (silmä-huone), https://noita.wiki.gg/wiki/Eye_Messages, https://github.com/Lymm37/eye-messages/wiki
