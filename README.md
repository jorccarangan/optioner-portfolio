# OPTIONER.DESIGN Portfolio
Live: https://jorccarangan.github.io/optioner-portfolio/Index.html

## GitHub Pages Setup
1. Upload all files to repo: jorccarangan/optioner-portfolio
2. Settings > Pages > Source: main branch / root
3. URL will be https://jorccarangan.github.io/optioner-portfolio/Index.html (capital I supported, lowercase also works)

## Drive Structure Fix - AI Branding
The 2 files were in root folder:
- Milo-Flow-Character-Reference-Optimized.html (1ynrZf_9WTrnJQvysgwV7eVdD9JEF0kaO)
- Kip-360-Character-Sheet-Optimized.html (1Cs_YtCjvY-Oxrdg-y0gJGVb2srGmCFK4)

MANUAL STEP (Drive API write not available in this session):
1. Go to https://drive.google.com/drive/folders/0B4XiMaSxk5Uca1FnX1B6LVNhRUk
2. Create folder named 0_AI_Branding
3. Move the 2 files above into that folder
4. Copy its new folder ID and paste into js/drive-config.js:
   "AI Branding": "NEW_FOLDER_ID"
5. Commit to GitHub - auto-sync will then work

Folder IDs currently:
- eBlast: 1qulzzVkFPxs2o3hOjezP3jWUEwJEmbwo
- Packaging: 1jgSGkRhB6nffs1ICKA57cS51lZzmZ45D
- Video and Animation: 1jneSO_P7JRl7yXS30bNNRm17ZzyONrJc
- Social Media Posting: 1VM6PP5qaM9BR1-wjYmnG82QbspNaV8Ml
- UI/UX: 1B49rUqO1XJ73M9b5wL988GHwMC-Ex4q_
- AI Branding: (create new)

## Features
- 8 tabs: eBlast, Packaging, Video and Animation, Social Media Posting, Amazon Pages, UI/UX, AI Branding, Logos and Others
- 300x300 thumbnails
- Carousel with dots
- Purple theme #6A1E5E matching logo
- Transparent logo + favicons + OG image
