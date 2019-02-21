## Replace master with orig
#change

```bash
git checkout orig

git merge -s ours master

git checkout master

git merge orig

git push
```
