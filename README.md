# Wedding Invitation Website

This repository is prepared for GitHub Pages.

## Files and folders
- `index.html` — website home page (must stay in the repository root)
- `assets/invitation-video.mp4` — opening invitation video
- `assets/wedding-song.mp3` — background music
- `assets/couple-photo.jpg` — couple photo
- `.nojekyll` — tells GitHub Pages to publish all static assets

## Upload to GitHub
1. Create a new **Public** GitHub repository.
2. Extract this ZIP on your computer.
3. Open the extracted `GitHub_Wedding_Invitation` folder.
4. Upload **all files and the `assets` folder inside it** to the repository's main/root level.
   - Do not upload the ZIP file itself.
   - Do not put `index.html` inside another extra folder.
   - Make sure the `assets` folder is alongside `index.html`.
5. In the repository, open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch **main** and folder **/(root)**, then click **Save**.
8. Wait for GitHub Pages to publish, then open the URL shown in Settings → Pages.

## Important: keep this structure
```
repository-root/
├── index.html
├── .nojekyll
├── README.md
├── README.txt
└── assets/
    ├── invitation-video.mp4
    ├── wedding-song.mp3
    └── couple-photo.jpg
```

The website uses relative asset paths such as `assets/wedding-song.mp3`, so keep the `assets` folder and filenames unchanged.

## Mobile and autoplay note
The opening video attempts to autoplay with sound. Some mobile browsers block sound until the visitor interacts with the page; this is a browser restriction. After **OPEN INVITATION**, the supplied MP3 starts and loops for the rest of the invitation.
