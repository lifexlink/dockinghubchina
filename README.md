# China Dock Space Gateway - Final Launch Version

Local test:

```bash
cd dockspace-final-launch
python3 -m http.server 8000
```

Open: http://localhost:8000

CSV/JSON import currently saves to browser localStorage. For public shared data, connect Supabase/Airtable/Google Sheets or deploy a shared data.json file.

Paste GA4 or Cloudflare Web Analytics snippet in the `<head>` section before launch.
