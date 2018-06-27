# Public Interest Tech Blog
## Andrew Lovett-Barron

To install, fork on github and modify the `/_data/bio.yml` and the `_config.yml` file.
Use the files in `_posts` to get started in filling in your own content, and 


Demo: [https://pit.andrewlb.com](https://pit.andrewlb.com)

## Installation
* Fork the repository
* Update with the pit config by running `git submodule update --recursive --remote`
* Go to settings and set Github Pages source as master.
* (Optional) Set up your custom domain and make sure to force HTTPS (may take a few days)
* Your new site should be ready soon, but will take time to propogate.

## Troubleshooting
If the "other fellows" collection isn't being called, open your `.gitmodules` file and verify that this line is present. Github pages requires the https url ref for using submodules, vs. the standard remote git path.
```
[submodule "_data/_config"]
	path = _data/_config
	url = https://github.com/NewAmericaPIT/_config.git
```


### About
Built by Andrew Lovett-Barron
Heavily modified with from Vyaasa as a starting point theme.