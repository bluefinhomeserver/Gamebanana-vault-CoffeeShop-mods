Gamebanana vault (CoffeeShop mods) (built with CoffeeShop Repo Builder)

How to publish this repo:

1. Go to https://github.com/new and create a new public repository.
2. After creating, click "uploading an existing file" and drag every file
   from this ZIP (repo.json + the games/ folder) into the upload area.
   Click "Commit changes".
3. Open the "Releases" page of your new repo.
   Click "Draft a new release", attach your mod ZIP files as assets,
   set a tag like v1, and publish.
4. Each mod's download URL will be of the form:
   https://github.com/<you>/<repo>/releases/download/<tag>/<file>.zip
   Paste these URLs into the Builder and re-export, then upload the
   updated repo.json and games/.../game.json files to your repo.
5. Share the raw URL of your repo.json with users:
   https://raw.githubusercontent.com/<you>/<repo>/main/repo.json
   They paste it into CoffeeShop's config.json under "repos".

Any HTTPS host works. GitHub is just the easiest free option.