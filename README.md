<div align="center">
   
### Walengine

Walengine is a unique web browser based on Surf, a lightweight GTK and WebKit-powered web browser.

### Features

**Browser Background**: Use your web browser as a background.

### To install on arch

```
mkdir -p walengine && cd walengine && (curl -O https://raw.githubusercontent.com/X3ric/walengine/main/PKGBUILD && makepkg -si) && cd .. && rm -rf walengine
```

### To install on others

   ```bash
   git clone https://github.com/X3ric/walengine.git
   cd walengine
   make
   sudo make install
   ```

   in the repo dir.

<details>
<summary><h3>BlackScreen?</h3></summary>

to fix add  ```alias walengine='WEBKIT_DISABLE_COMPOSITING_MODE=1 walengine'``` to your shell.

this appends in some nvidia gpu.

</details>

</p><a href="https://archlinux.org"><img alt="Arch Linux" src="https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=D9E0EE&color=000000&labelColor=97A4E2"/></a><br>
