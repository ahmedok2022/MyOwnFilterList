# Filter Lists

Comprehensive ad, tracker, malware, phishing & annoyance filter list — auto-compiled from 70+ trusted sources into a single file.

## Subscribe

Add this **one URL** to your browser:

```
https://raw.githubusercontent.com/ahmedok2022/MyOwnFilterList/refs/heads/main/filters.txt
```

### uBlock Origin (Desktop)
1. Dashboard → Filter lists → Import → paste the URL above
2. Click "Apply changes"

**One-time fix to prevent YouTube anti-adblock detection:**

uBlock Origin silently disables `trusted-*` scriptlets (the YouTube ad bypass mechanism) from external subscriptions by default. Fix it once:

1. Dashboard → **Settings** → check **"I am an advanced user"** → click the **⚙ gear icon**
2. Find `trustedListPrefixes` (default value: `ublock-`)
3. Change it to:
   ```
   ublock- https://raw.githubusercontent.com/ahmedok2022/
   ```
4. Save
