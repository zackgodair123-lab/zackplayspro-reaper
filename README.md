# ZackPlaysPro AI — Reaper

Static control panel for the Reaper AI co-host (local simulation + voice commands + embedded avatar).

## Free hosting

### GitHub Pages
1. Go to Settings → Pages
2. Source: Deploy from a branch → main / root
3. Save. Site will be at https://zackgodair123-lab.github.io/zackplayspro-reaper/

### Cloudflare Pages (recommended for unlimited static)
1. Create Cloudflare account
2. Workers & Pages → Create → Pages → Upload assets
3. Drag-and-drop this folder (or just index.html)
4. Deploy. You get a free *.pages.dev URL + optional custom domain.

## Twitch linking
This panel is the frontend. Live chat requires:
- Twitch Developer App (client ID)
- OAuth for the bot account (grimmy_ai) with chat:read + chat:edit
- Secure backend for tokens and IRC/EventSub (Cloudflare Workers works on free tier for light use)

Never put client secrets or bot tokens in this frontend file.

Bot account: grimmy_ai
Streamer: zackplayspro
