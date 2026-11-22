# Tower Siege

Knock down two towers of blocks with a hexagonal stone fired from a slingshot.

## How to play
- **Drag** the stone back with the mouse and **release** to launch it.
- Blocks that are hit hard enough disappear.

## Run it locally
Browsers block games that load images and scripts straight from disk, so serve the folder with any small web server:

```bash
git clone https://github.com/Aakash12321/Tower-Siege-I.git
cd Tower-Siege-I
python -m http.server 8000
```

Then open <http://localhost:8000> in your browser. (The VS Code **Live Server** extension works too.)

## Built with
- p5.js
- Matter.js
