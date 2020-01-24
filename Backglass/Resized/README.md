Resize Centered Images
```bash
magick mogrify -path Center -resize 1280x1024^ -gravity Center -extent 1280x1024 ../Preformatted/*
magick mogrify -path East -resize 1280x1024^ -gravity East -extent 1280x1024 ../Preformatted/*
magick mogrify -path West -resize 1280x1024^ -gravity West -extent 1280x1024 ../Preformatted/*
```
