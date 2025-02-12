# Online Portfolio

When adding new images, one should use the command `convert` to:
- Reduce the size, with the argument, `-resize`
- Remove the EXIF data, with the argument `-strip`

Example:

```sh
convert ~/Images/mypicture.jpg -resize 1280x1280 -strip ./Images/myimage.jpg
```