# recorder
Just a simple video recorder that works with OpenCV. Used for recording videos that are needed in other projects.

## Dependencies

* [OpenCV](https://pypi.org/project/opencv-python/)

## Usage

### Arguments

| flag | name | description | default |
| :---: | :--- | :--- | :--- |
| `-h` | `--help` | show this help message and exit | `None` |
| `-d` | `--device-id` | the id of the camera that shall be used (if you want to use a video, see the '-f' argument) | `1` |
|  | `--width` | width in px, the frame shall be resized to (has to equal '--height', if '--square' is set) | `None` |
|  | `--height` | height in px, the frame shall be resized to (has to equal '--width', if '--square' is set) | `None` |
|  | `--square` | make the frame square (it will not be resized but cropped to the smaller edge length, if '--width' and '--height' are also set, they must have the same value) | `False` |


### Keybindings

| key | usage |
| :---: | :--- |
| `s` | take a photo |
| `SPACE` | take a video (start / stop with `SPACE`) |
| `q` or `ESC` | quit the program |
