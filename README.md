# ir-anthology.github.io
Notes for Quick-Deploy

```
test -d ir-anthology.github.io || git clone git@github.com:ir-anthology/ir-anthology.github.io.git
tar --extract -f ~/ir-anthology_build/build.tar
cp -r build/* ir-anthology.github.io/
cd ir-anthology.github.io/
git add *
git commit -m "update"
```
