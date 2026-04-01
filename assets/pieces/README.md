# Custom chess pieces

To use your own chess pieces in the app:

1. Open board settings and choose **Custom (из assets)** in the "Фигурки" selector.
2. Put your PNG files into `assets/pieces/custom/`.
3. Use these exact file names (case-sensitive):

- `wP.png`, `wR.png`, `wN.png`, `wB.png`, `wQ.png`, `wK.png`
- `bP.png`, `bR.png`, `bN.png`, `bB.png`, `bQ.png`, `bK.png`

The board will load pieces from the template:

`assets/pieces/custom/{piece}.png`

where `{piece}` is one of the names above.
