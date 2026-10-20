# KKHomeAI UGC Media Production

## When this skill applies

- Use this skill when the user provides a product photo and asks to create product images, a UGC advertising script, a poster, or a full package for TikTok Shop or Shopee.

- Work in Vietnamese with the user and keep every command and prompt in English.

## Load the command dictionary

- Read `references/bo-lenh-ngan.md` in this skill folder before proposing anything.

- Build every image option, script scene and poster from the commands in that dictionary and name the combo used in each output.

## Guide the user with ready made commands

- Offer these starter commands when the user is unsure what to ask for.

  - "Tạo ảnh cho sản phẩm này" runs the image workflow.
  - "Tạo kịch bản cho sản phẩm này" runs the script workflow.
  - "Tạo poster cho sản phẩm này" runs the poster workflow.
  - "Làm trọn gói sản phẩm này" runs all three workflows in order without asking again between stages.

- Ask at most two short questions when the product description is missing, then start working.

## Create images

- Propose exactly five image options before generating, each with a short name, the command combo, its purpose and a complete ready to run prompt.

- Cover varied purposes across the five options, such as a UGC cover photo with a character holding the product, a premium studio shot for the shop page, a try-on or in-use shot, a lifestyle shot in the real usage setting and a six panel storyboard sheet.

- Generate the option the user picks, or all five when the user asks for the full set.

- Default to vertical 9:16 at the highest available quality, aiming for 4K sharpness with upscaling when the tool supports it.

- Keep the product identical to the sample photo in shape, color, material and details, and never invent text or logos on the packaging.

- Lock the character face and body to the reference photo when one is provided, and describe only action and setting in prompts, never the character appearance.

## Write the seamless two scene UGC script

- Build exactly two scenes of ten seconds each that flow as one continuous story, using the generated images as start frames and visual references.

- Give scene one the hook and the product introduction or demo, and give scene two the clearest result plus the call to action.

- Keep the same character, outfit, setting and lighting across both scenes, and let scene two continue naturally from the final frame of scene one.

- Write dialogue in Vietnamese only, about twenty to twenty eight words per scene, sized to ten seconds at natural speed.

- Paste this voice lock into every scene prompt.

```
VOICE LOCK: young female voice, SOUTHERN Vietnamese accent, sweet, clear and bright, friendly energetic UGC creator tone. She speaks ONLY Vietnamese, lip-synced.
```

- Output each scene as one standalone copyable prompt block that runs on both Muse and Google Flow, headed by the scene number, its name and the command combo.

- Add one summary line of the two scene story plus a short suggested TikTok caption after the blocks.

## Create the poster

- Create the poster after the images and the script, reusing the same character and product so the poster promises exactly what the video delivers.

- Compose a large expressive character, the product in the golden spot with a light accent, and a Vietnamese title of five to seven words taken from the script hook, rendered in big bold material typography that stays readable on a phone screen.

- Default to vertical 9:16 at the highest available quality, aiming for 4K sharpness.

- Check the finished poster before delivering it and regenerate when any Vietnamese diacritic is wrong, when the product shape or color drifted, or when text covers the face or the product.

## Iron rules

- Use only commands from the dictionary and flag any new command as a fresh suggestion.

- Keep the product unchanged across the images, both scenes and the poster, with no deformation and no invented features.

- Keep the character face consistent across the images, both scenes and the poster.

- Keep all motion at natural real life speed with no slow motion and no stiff standing and talking shots.

- End every sales video with the shopping cart call to action at the bottom left corner in the final three seconds plus a spoken Vietnamese call to action line.
