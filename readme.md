This is a C project using the `gtk3` and `cairo` graphics library to build an application

## Project Brief

This project is an upgrade on a1 project. It has additional features of button controls and been able to paint a specific color on an image. It draws a png image on a gtk window and detects the color pixels on the image based on the mouse pointer clicks. It separates the rgb values from the extracted color pixel and prints it out. It is the version w of an upgraded pick color and polish project for a2. It allows the colors extracted to painted on to the image.

The new designs can be saved with the "save new" button as a new image in the photos folder as "new.png"

## Contribution

The application was built by:

```
- Emmanuel Ainoo
- Ayomide Oduba
```

## Requirements

- [`gcc C program compiler`](https://gcc.gnu.org)
- [`gtk3`](https://www.gtk.org)
- [`Cairo Graphics`](https://www.cairographics.org)

## Usage

Compile with gcc & gtk3 flags on terminal:

```shell
gcc `pkg-config --cflags gtk+-3.0` -o a2 a2.c `pkg-config --libs gtk+-3.0`
```

Run File:

```shell
./a1
```

- Click on Pick Color
- Choose any color on loaded image and validate with pixels printed below
- Click on Paint Color
- Drag mouse on image to paint with color selected
