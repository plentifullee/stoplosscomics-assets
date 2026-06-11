# To resize image

for file in *.png; do
  magick "$file" -quality 80 "${file%.png}.webp"
done