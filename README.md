# HELLO

I'm not 100% on how to pull at will with lfs, but [this](https://github.com/git-lfs/git-lfs/issues/1511) seems like a good resource

Pulling the repo does not include the gold images by default. These are stored in git-lfs, which you can install [here](). 

You should pull images a la carte. To pull an image, run: 

```
git lfs pull -I cat.bin -X ""
```

