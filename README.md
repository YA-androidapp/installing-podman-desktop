# installing-podman-desktop

---

# for Windows

## Links

- [Podman Desktop](https://podman-desktop.io)
  - [exe](https://github.com/containers/podman-desktop/releases/download/v1.0.1/podman-desktop-1.0.1-setup.exe)
  - `winget install -e --id RedHat.Podman-Desktop`

- Podman compose
  - `py -m pip install podman-compose`

# for Mac

- [Podman Desktop](https://podman-desktop.io)
  - [dmg](https://github.com/containers/podman-desktop/releases/download/v1.0.1/podman-desktop-1.0.1-universal.dmg)
  - `brew install podman-desktop`

- Podman compose
  - `pip3 install podman-compose`

# Test

```bash
podman run -d -p 8080:80 --name web nginx

podman run -d -p 8787:8787 rockerjp/tidyverse

cd src/flask/
podman-compose up -d
```

---

Copyright (c) 2023 YA-androidapp(https://github.com/YA-androidapp) All rights reserved.
