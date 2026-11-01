# ZineROM-Project

Public static website for the ZineROM Project device roadmap. This repository is a fork of the existing ZineROM landing source and keeps its static HTML/CSS/JavaScript architecture.

## Pages

- `index.html` — project-wide Galaxy device selection and roadmap.
- `device.html?device=a11` — Galaxy A11-specific details, status, base, checksum, and test download.
- `device.html?device=a52s` — Galaxy A52s-specific details.

Device data is centralized in `app.js`. Devices without an approved public build show **SOON / no download** and a **Request Support** link instead of a fake download button.

## Local preview

```sh
python3 -m http.server 4173
```

The site is independent and is not affiliated with Samsung.
