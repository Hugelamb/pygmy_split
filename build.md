# Build Command Line Instructions

From inside the zmk folder, start the virtual environment .venv,
then navigate to the app subdirectory within zmk (path/zmk/app).

Then run the following to build the boards found within this repository's config folder:

For the right half:
west build -d C:/Users/Hugh/pygmy_split/build/right -b pygmy_right -- -DZMK_CONFIG="C:\Users\Hugh\pygmy_split\config"

For the left half:
west build -d C:/Users/Hugh/pygmy_split/build/left -b pygmy_left -- -DZMK_CONFIG="C:\Users\Hugh\pygmy_split\config"
