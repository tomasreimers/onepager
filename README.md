# Deploy

```
gulp
git checkout gh-pages
cp -r dist/* ./
rm -rf dist/
git add --all
git commit -m "New release with <features>"
git push
```
