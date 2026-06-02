MIAWSLOT RTP AMP Dynamic Hourly

ISI PAKET
- index.html
- functions/api/rtp.js
- data/providers.js

DOMAIN TARGET
- Root / canonical AMP: https://miawslot-rtp.com/
- Subdomain AMP final: https://amp.miawslot-rtp.com/

CARA DEPLOY VIA GITHUB + CLOUDFLARE PAGES
1. Buat repo GitHub baru, misalnya: miawslot-rtp
2. Upload semua isi folder ini ke root repo.
3. Cloudflare Workers & Pages -> Create application -> Pages -> Connect to Git.
4. Pilih repo miawslot-rtp.
5. Build setting:
   Framework preset: None
   Build command: kosongkan
   Build output directory: /
6. Deploy.
7. Tambahkan custom domain: amp.miawslot-rtp.com
8. Test endpoint:
   /api/rtp?provider=pragmatic
   /api/rtp?provider=jili
   /api/rtp?provider=pgsoft&q=mahjong

CATATAN
- Warna sudah diubah ke merah maroon.
- Icon/logo memakai: https://res.cloudinary.com/dingtuqen/image/upload/v1764150758/favicon_pohwx4.png
- Banner memakai: https://res.cloudinary.com/dingtuqen/image/upload/v1780395525/miawslot_rtp_live_1024x512_kj8vl0.webp
- AMP validity: selected attribute dan !important sudah dihapus.
