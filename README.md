# React Three Fiber universal examples

A fork of https://github.com/birkir/react-three-fiber-examples with the aim to make examples work on native and web.

Examples which work:

- [x] Hello World
- [x] Physics
- [x] Stars (except for a small hitbox alignment issue https://github.com/jmatsushita/react-three-fiber-examples/issues/4)
- [x] Reparenting
- [ ] Multi Render (web only shows on second render)
- [x] Montage
- [ ] Font (OrbitControls don't work on the web https://github.com/jmatsushita/react-three-fiber-examples/issues/7)
- [ ] Lines (same problem with OrbitControls https://github.com/jmatsushita/react-three-fiber-examples/issues/7)
- [x] MeshLines
- [ ] ARKit - doesn't work on mobile web https://github.com/jmatsushita/react-three-fiber-examples/issues/8

Misc:

- [ ] Layout in the browser doesn't stretch to the container size https://github.com/jmatsushita/react-three-fiber-examples/issues/5.
- [ ] Update from expo sdk 34 to 36.
- [ ] Update from react-three-fiber `3.0.17` to `4.0.12`
- [ ] Update from three.js `0.105.0` to `0.113.2`

## Usage

- Install: `yarn` (`npm i` [doesn't work](https://github.com/jmatsushita/react-three-fiber-examples/issues/1))
- Start `npm start`
- Browser: Type `w` in the terminal to start the web build and open the browser.
- Native: Use the iOS camera to scan the QR code which will open the expo client.
