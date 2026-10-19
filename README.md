# lab.usersfirst.games redirect

The controller lab moved to **https://lab.housetandem.com** (repo [UsersFirst/tandemonium-controller-lab](https://github.com/UsersFirst/tandemonium-controller-lab)). GitHub Pages allows one custom domain per repo, so this tiny Pages site holds the old `lab.usersfirst.games` domain. It sends every path to the same path on the new domain (`404.html` handles deep links like `/overlay/` and `/pr-preview/...`).

DNS for usersfirst.games is on name.com: `lab` CNAME → `usersfirst.github.io` (unchanged).
