# body-pix Demos

## Contents

The demo shows how to estimate segmentation in real-time from a webcam video stream.

## Setup

cd into the demos folder:

```sh
cd body-pix/demos
```

Install dependencies and prepare the build directory:

```sh
yarn
```

To watch files for changes, and launch a dev server:

```sh
yarn watch
```

## If you are developing body-pix locally, and want to test the changes in the demos

Install yalc:
```sh
npm i -g yalc
```

cd into the body-pix folder:
```sh
cd body-pix
```

Install dependencies:
```sh
yarn
```

Publish body-pix locally:
```sh
yalc push
```

Cd into the demos and install dependencies:

```sh
cd demos
yarn
```

Link the local body-pix to the demos:
```sh
yalc link @tensorflow-models/body-pix
```

Start the dev demo server:
```sh
yarn watch
```

To get future updates from the body-pix source code:
```
# cd up into the body-pix directory
cd ../
yarn build && yalc push
```
