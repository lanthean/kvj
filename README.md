# kvj
Lodni denik template + rename/resize script to manage photos


## Usage
```sh
Usage $script_name -i /path/to/ (org)
					[--rename_jpeg (only rename *.jpeg files to *.$ext)]
					[--mov (only convert MOV files)]
					[-m (--max_pixels) [1024] ${max_pixels}]
					[-e (--img_extension) [JPG] ${ext}]
```
- note that /path/to/rs is relative to /path/to/org (not configurable)
e.g.
```
 ./resize -i /kvj/2020_PT_Vltava/den_01/
```

### input
/path/to/org
Path to original photos.

### rename_jpeg
Only rename \*.jpeg files to \*.$ext

### mov
Only convert \*.MOV files to \*.mp4

### max_pixels
Maximum height/width of resized photo.

### img_extension
Photo files extension (e.g. 'JPG')


## Author
https://github.com/lanthean/kvj

