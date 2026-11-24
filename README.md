# Hearth Orbital — world content

This repository is published by the **Hearth Orbital Control Room**. Please don't edit it by hand:
the next publish overwrites `test/` and `live/`.

- `vrchat-test/` — one text file and two pictures to check that VRChat can load from here.
- `test/` — read by the test world.
- `live/` — read by the public world ("Go live" copies test → live).

Each channel has a `manifest.json` (version + what exists) and one file per module.
Pictures use fixed numbered slots with two files each (`01a.jpg` / `01b.jpg`); the manifest says which is current.
