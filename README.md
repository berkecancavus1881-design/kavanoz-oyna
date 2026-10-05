# Kavanoz — play in the browser

Godot **4.7.2** web export (single-threaded, no SharedArrayBuffer / COOP-COEP required).

## Play

- **GitHub Pages (intended):** https://berkecancavus1881-design.github.io/kavanoz-oyna/
- **User Pages mirror:** https://berkecancavus1881-design.github.io/
- If Pages is still building/failing, open the files from this repo via any static host, or use a local server (`python3 -m http.server`) in this folder.

Built from private source `berkecancavus1881-design/kavanoz` commit **3de7bb5**.

## Notes

- Desktop + mobile landscape. Touch maps to mouse (`emulate_mouse_from_touch`).
- First load downloads ~40 MB (`index.wasm`).
- Empty browser storage → fresh jar; progress saves in Godot `user://` (IndexedDB).
- iOS Safari: allow storage; add to Home Screen optional; very old iOS may lack WebGL2.
