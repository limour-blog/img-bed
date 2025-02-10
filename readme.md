```bash
rclone copy --ignore-existing --progress --ignore-errors img:limour-img ~/img-bed
git add .
git commit -m 'backup'
git push
```
