# Butterbell Café

A cozy concept website for a small café, with 3D scenes built in [Three.js](https://threejs.org/).

- **Hero diorama**: a low-poly model of the café (striped awning, lit windows, a bell on the roof, a cat on the bench, drifting petals and chimney smoke). Drag to look around.
- **3D menu**: eight items modelled entirely from Three.js primitives (strawberry cream slice, latte with latte art, croissant, iced strawberry matcha, donut, cupcake, macarons, cardamom roll). Drag to turn, pick from the tray, choose a size and add to the bag.
- Tray thumbnails are rendered from the same 3D models at load time.
- Bag drawer and favourites are kept in `localStorage`.

It's a single static file with no build step. Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

Three.js r128 is loaded from cdnjs; fonts come from Google Fonts.
