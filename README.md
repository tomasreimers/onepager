# OnePager.io
> A community of students who love to build

## Deploy

```build dist
checkout gh-pages
cp -r dist/* ./
rm -rf dist/
git add --all
git commit -m "Rebuild"
git push```