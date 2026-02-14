for f in *.jpg; do cwebp "$f" -o "${f%.jpg}.webp"; done

for f in *.jpeg; do cwebp "$f" -o "${f%.jpeg}.webp"; done

for f in *.png; do cwebp "$f" -o "${f%.png}.webp"; done