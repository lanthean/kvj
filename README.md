# kvj
Lodni denik template + rename/resize script to manage photos

## Usage
```sh
Usage $script_name -i /path/to/
					[--rename_jpeg (only rename *.jpeg files to *.$ext)]
					[--mov (only convert MOV files)]
					[-m (--max_pixels) [1024] ${max_pixels}]
					[-e (--img_extension) [JPG] ${ext}]
```
- note that /path/to/rs is relative to /path/to/org (not configurable)  

Example of usage:
```
./resize -i /kvj/2020_PT_Vltava/den_01/
# input: /kvj/2020__PT_Vltava/den_01/org/*.JPG
# resized output: /kvj/2020__PT_Vltava/den_01/rs/
```

### input
/path/to/\[org\]
path to original photos

### rename_jpeg
only rename \*.jpeg files to \*.$ext

### mov
only convert \*.MOV files to \*.mp4

### max_pixels
maximum height/width of resized photo

### img_extension
input/original photo files extension (e.g. 'JPG')


## Author
https://github.com/lanthean/kvj