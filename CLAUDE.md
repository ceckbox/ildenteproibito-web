# CLAUDE.md

# IL DENTE PROIBITO — PROFILE IMAGE & MUSIC UPDATE SPECIFICATION

## PRIMARY OBJECTIVE

Modify the existing **IL DENTE PROIBITO** website in this repository according to the exact instructions in this document.

Repository:

https://github.com/ildenteproibito/ildenteproibito-web

Official website:

https://ildenteproibito.pages.dev/

This task has ONLY two functional objectives:

1. Replace the current profile picture/avatar displayed by the website with the exact image supplied by the project owner.
2. Replace the current music list with the exact requested music list while preserving **BIA - WE ON GO**.

Nothing else should be changed.

---

# ABSOLUTE RULE — DO NOT TAKE UNREQUESTED INITIATIVE

This is a strictly controlled modification task.

Do NOT redesign the website.

Do NOT refactor the website.

Do NOT improve unrelated code.

Do NOT change the UI.

Do NOT change animations.

Do NOT change colors.

Do NOT change typography.

Do NOT change spacing.

Do NOT change responsive behavior.

Do NOT change navigation.

Do NOT change sections.

Do NOT change buttons.

Do NOT change links unrelated to the requested music.

Do NOT change text unrelated to the requested modifications.

Do NOT update dependencies.

Do NOT change configuration.

Do NOT change build settings.

Do NOT change deployment settings.

Do NOT change the project's structure unless absolutely required to replace the image asset.

Do NOT remove files unless a file becomes genuinely unused as a direct consequence of replacing the profile image and removing old music entries.

Do NOT add features.

Do NOT remove features.

Do NOT "clean up" unrelated code.

Do NOT make aesthetic decisions on your own.

If something is not explicitly requested in this document, leave it unchanged.

---

# REQUIRED WORKFLOW

Follow this exact sequence:

1. Inspect the repository.
2. Inspect the current website implementation.
3. Identify exactly where the current profile image is stored/referenced.
4. Identify exactly how the current music list is stored/rendered.
5. Identify the existing **BIA - WE ON GO** entry and preserve it.
6. Replace ONLY the profile image.
7. Remove every music entry except **BIA - WE ON GO**.
8. Add the three requested songs immediately after BIA - WE ON GO, in the exact order specified below.
9. Verify the website still builds and renders correctly.
10. Check that no unrelated files were modified.
11. Perform the final audit described at the end of this document.

Do not skip the inspection phase.

---

# PROFILE IMAGE — EXACT REQUIREMENT

The project owner supplied a specific image for the new profile picture.

Use the supplied image **exactly as provided**.

Do NOT:

- generate a different image;
- redraw it;
- replace it with a similar image;
- use an online image instead;
- crop it unnecessarily;
- add effects;
- change colors;
- add text;
- remove elements;
- alter the artwork;
- upscale/downscale unnecessarily;
- convert it to another format unless technically required by the existing website implementation.

The supplied image is the authoritative source for the new profile picture.

## IMPORTANT

The goal is to replace the CURRENT profile image with the supplied image while preserving the existing website's behavior.

First determine how the current profile image is implemented.

If the current image is referenced by an existing asset path, prefer replacing the asset while preserving the existing path/filename when technically possible.

This is strongly preferred because it minimizes source-code changes and reduces the risk of breaking the website.

If the image must instead be referenced from a new asset path, make the smallest possible change required.

Do not alter the surrounding profile component.

---

# IMAGE DISPLAY REQUIREMENTS

Preserve the existing:

- image dimensions;
- aspect-ratio behavior;
- border radius;
- clipping;
- positioning;
- responsive behavior;
- animations;
- hover behavior;
- surrounding layout.

Only the image content itself should change.

If the existing website uses CSS/object-fit or another presentation method, leave it unchanged.

Do not redesign the avatar.

---

# MUSIC — REQUIRED FINAL STATE

The current website contains a music list/player.

The final music list must contain ONLY these four songs, in this exact order:

## 1. BIA - WE ON GO

This is the existing song that must be preserved.

IMPORTANT:

- Find the existing **BIA - WE ON GO** entry in the current website/repository.
- Preserve its existing YouTube URL exactly.
- Preserve its existing metadata/artwork/settings where applicable.
- Do not replace its URL with a guessed URL.
- Do not modify its title unless the current implementation requires exact formatting and the title is already equivalent.

## 2. MILITARY

YouTube:

https://youtu.be/MW0XjrVJ2_E

## 3. MONTAGEM CAMERA LENTA

YouTube:

https://youtu.be/S0m32JT64OM

## 4. Im Sorry Mom

YouTube:

https://youtu.be/xUc7LISGQl8

---

# MUSIC REMOVAL RULE

Remove ALL currently configured songs except:

**BIA - WE ON GO**

Do not leave old songs hidden, commented out, duplicated, or inactive.

The final active music data must contain exactly four entries.

Final order:

```text
BIA - WE ON GO
MILITARY
MONTAGEM CAMERA LENTA
Im Sorry Mom
```

No other songs may remain active.

---

# MUSIC IMPLEMENTATION

First inspect how the website implements its music system.

It may use:

- an array;
- JSON;
- TypeScript data;
- JavaScript data;
- component props;
- local assets;
- YouTube URLs;
- embedded player configuration;
- another existing structure.

Modify the existing implementation rather than replacing the music system.

Do NOT create a new music player.

Do NOT redesign the music player.

Do NOT change playback behavior.

Do NOT change controls.

Do NOT change autoplay behavior.

Do NOT change volume behavior.

Do NOT change the player UI.

Do NOT change animations.

Only update the underlying music entries required by this task.

---

# YOUTUBE URL RULES

Use the exact URLs supplied by the project owner:

MILITARY:
https://youtu.be/MW0XjrVJ2_E

MONTAGEM CAMERA LENTA:
https://youtu.be/S0m32JT64OM

Im Sorry Mom:
https://youtu.be/xUc7LISGQl8

Do not substitute different uploads.

Do not search for alternative versions.

Do not modify the video IDs.

For **BIA - WE ON GO**, preserve the exact existing URL found in the repository.

---

# SONG TITLE RULE

Use these exact displayed titles:

```text
BIA - WE ON GO
MILITARY
MONTAGEM CAMERA LENTA
Im Sorry Mom
```

Do not add artists, descriptions, emojis, release years, genres, or other metadata unless the existing music system requires metadata fields and the information is already available.

Do not invent missing metadata.

---

# MUSIC ARTWORK / THUMBNAILS

If the existing music system automatically obtains YouTube thumbnails from the video URL, preserve that behavior.

Do not manually replace artwork unless required by the existing implementation.

Do not invent cover art.

Do not download unrelated artwork.

---

# PRESERVE EVERYTHING ELSE

The following must remain unchanged unless directly required by the requested modifications:

- layout;
- profile section;
- navigation;
- hero;
- text;
- biography;
- social links;
- buttons;
- animations;
- effects;
- background;
- fonts;
- colors;
- responsive design;
- page structure;
- components unrelated to the avatar/music;
- dependencies;
- build system;
- deployment configuration.

---

# FILE MODIFICATION SCOPE

Only modify files that are strictly necessary to:

1. replace the profile image;
2. update the music data/configuration.

Do not modify unrelated files.

If the existing profile image can be replaced without changing source code, prefer that approach.

If an image asset is replaced, do not modify unrelated assets.

---

# DO NOT DELETE THE OLD IMAGE PREMATURELY

Before replacing the profile image:

1. Identify the exact current asset.
2. Identify every reference to it.
3. Confirm that it is the profile image displayed by the website.
4. Replace it safely.

Do not delete an image that is used elsewhere.

If the existing asset is shared by another part of the website, do not overwrite it unless you have confirmed that doing so will not alter unrelated parts of the website.

In that situation, use a new asset path and change only the profile-image reference.

---

# VALIDATION

After making the modifications:

1. Run the project's existing validation/build process if available.
2. Do not invent commands.
3. Inspect `package.json` and use only existing scripts.
4. Confirm there are no syntax errors.
5. Confirm the website still builds.
6. Confirm the music data contains exactly four entries.
7. Confirm their order.
8. Confirm the three supplied YouTube URLs exactly match the requested URLs.
9. Confirm BIA - WE ON GO still uses its original URL.
10. Confirm the profile image points to the supplied image.
11. Confirm no unrelated functionality was changed.

---

# GIT STATUS AUDIT

At the end, run:

```bash
git status
```

Review every changed file.

Only files directly necessary for this task may be changed.

If unrelated modifications already existed before your work:

- do not revert them;
- do not delete them;
- do not modify them.

Clearly distinguish pre-existing changes from your own changes.

---

# FINAL CHECKLIST

Before considering the task complete, verify every item:

## Profile image

- [ ] The current website profile image was identified.
- [ ] The supplied image is now used.
- [ ] The supplied image was not replaced by another image.
- [ ] No unnecessary image processing was performed.
- [ ] Existing avatar styling was preserved.
- [ ] Existing dimensions/behavior were preserved.
- [ ] No unrelated image references were broken.

## Music

- [ ] BIA - WE ON GO remains.
- [ ] BIA - WE ON GO remains first.
- [ ] Its original YouTube URL is preserved.
- [ ] MILITARY is second.
- [ ] MILITARY uses `https://youtu.be/MW0XjrVJ2_E`.
- [ ] MONTAGEM CAMERA LENTA is third.
- [ ] MONTAGEM CAMERA LENTA uses `https://youtu.be/S0m32JT64OM`.
- [ ] Im Sorry Mom is fourth.
- [ ] Im Sorry Mom uses `https://youtu.be/xUc7LISGQl8`.
- [ ] Every other previous song has been removed.
- [ ] No old songs remain hidden/commented out as active data.
- [ ] The existing music player UI/behavior remains unchanged.

## Safety

- [ ] No unrelated source code was changed.
- [ ] No unrelated files were created.
- [ ] No dependencies were changed.
- [ ] No configuration was changed.
- [ ] No website redesign was performed.
- [ ] No unrequested features were added.
- [ ] No unrequested "improvements" were made.

---

# FINAL RULE

If you are unsure whether a change is required:

**DO NOT MAKE THE CHANGE.**

Inspect the existing implementation first.

The project owner's explicit instructions in this document have priority over any personal preference or automatic improvement you might otherwise make.

The desired result is:

**The exact supplied profile image + exactly four songs in the specified order, with everything else left untouched.**
