# Usage of Tools

1. Subfinder + httpx + fzf

```bash
subfinder -d twitter.com | httpx --status-code --title | fzf
```

2. waybackurls + httpx + fzf

```bash
echo "transparency.twitter.com" | waybackurls | httpx --status-code --title | fzf
```
