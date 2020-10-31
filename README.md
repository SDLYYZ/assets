# Assets

This repository is used to store assets used by LYOI Online Judge.

Please upload the assets used by a problem in the `problems` directory, and create a directory named by the problem id to categorize them.

If your assets are used by the website, please upload them in the `web` directory.

Otherwise, you should upload them in the `misc` directory.

## How to use

When you have uploaded your asset, you can get the CDN link provided by jsDelivr.

The format is shown below:

```url
https://cdn.jsdelivr.net/gh/SDLYYZ/assets/[$LOCAL_PATH_IN_THE_GIT_REPOSITORY]
```

For example, if you uploaded an asset called `glztxdy.png` for problem with id `1145141919810`, it's supposed to be located in `/problems/1145141919810/glztxdy.png`. Then you can get it with this link:   
```url
https://cdn.jsdelivr.net/gh/SDLYYZ/assets/problems/1145141919810/glztxdy.png
```

You can ask our administrators for commiting permission of this repository, or fork it and create a PR.

It's OK to store assets on wherever you like and link it on the OJ. But it's recommended to store it there.