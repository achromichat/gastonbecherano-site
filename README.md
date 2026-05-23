# gastonbecherano.com

Static site hosted on GitHub Pages. Free.

## Update the GIF

Replace `gaston.gif` in the root of this repo, commit, and push. GitHub Pages auto-deploys in ~30 seconds.

```bash
git add gaston.gif
git commit -m "update gif"
git push
```

## DNS (set once at Namecheap)

For `gastonbecherano.com`, set these **A records** on the apex:

```
A  @  185.199.108.153
A  @  185.199.109.153
A  @  185.199.110.153
A  @  185.199.111.153
```

And a CNAME for www:

```
CNAME  www  achromichat.github.io
```
