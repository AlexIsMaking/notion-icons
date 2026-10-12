---
name: notion-icons
description: Look up available Notion custom icons and colours from the aNotioneer Icons database before applying them to pages. Use this skill whenever you need to choose or validate a Notion icon name or icon colour — including when setting icons on new pages, updating existing page icons, bulk-updating icons, or when the user asks what icons or colours are available. Always consult this skill before writing an icon value into any notion-create-pages or notion-update-page call that uses a custom (non-emoji) icon, so the chosen name and colour are guaranteed to exist.
---

# Notion Icons Skill

Hard-coded reference of all available custom icons from the aNotioneer Icons database, for use when setting icons on Notion pages.

## Available Colours

Every icon is available in every colour. Valid values (use exact strings):

`gray` · `lightgray` · `brown` · `yellow` · `orange` · `pink` · `blue` · `green` · `purple` · `red`

## Icon URL Format

Pass the icon to `notion-create-pages` or `notion-update-page` as a custom emoji in the format:

```
:<icon-name>-<colour>:
```

Examples: `:calendar-blue:` · `:rocket-orange:` · `:folder-gray:`

## Workflow

1. **Identify the concept** — what should the icon represent?
2. **Find a match** — scan the relevant category or use Cmd+F on the icon name below.
3. **Confirm the colour** — if the user hasn't specified one, suggest a contextually appropriate colour or ask them to choose.
4. **Apply** — use the exact `name` string and colour in the `:<name>-<colour>:` format.

If no icon fits well, fall back to a standard emoji instead.

---

## Icon Reference

### Activity (106)

archery, art, balloon, bicycle, binoculars, camping-tent, camping-trailer, card-club, card-diamond, card-heart, card-spade, cards, cd, check, chemistry, chess-bishop, chess-king, chess-knight, chess-pawn, chess-queen, chess-rook, clarinet, color-palette, color-picker, color-swatch, conversation, credit-card, dental, die1, die2, die3, die4, die5, die6, dish-soap, electric-guitar, fan-deck, gift, gradebook, graduate, guitar, gym, hammer, headphones, hot-air-balloon, ice-skate, magic-wand, metronome, microphone, microphone-off, microscope, movie, movie-camera, movie-clapboard, movie-clapboard-play, music, music-album, music-artist, note-eighth, note-half, note-quarter, note-sixteenth, note-sixteenth-beamed, note-whole, paint-brush, paint-brush-wide, paint-bucket, paint-roller, phone, phone-call, phone-end-call, phone-speaker, photo-landscape, piano, playlist, radio, roller-skate, shield, shopping-bag, shopping-basket, shopping-cart, shovel-and-pail, shower, skateboard, snare-drum, sponge, stethoscope, stopwatch, suit-club, suit-diamond, suit-heart, suit-spade, target, theatre, ticket, ticket-admission, trophy, trumpet, tv, video-camera, video-camera-off, video-game, videotape, vinyl-record, violin, wrapping-paper

### Animals & Nature (42)

bone, bug, cloudy, daisy, donkey, elephant, fire, fish, flood, fog, forest-fire, hail, hare, hurricane, leaf, moon, partly-cloudy-day, partly-cloudy-night, rain, rainbow, shell, skull, skull-profile, sleet, snowflake, soap, star, star-outline, stars, storm, sun, sunrise, sunset, temperature-cool, temperature-warm, tornado, tortoise, tree, tulip, water, wheat, wind

### Food & Drink (54)

apple, banana, beer, beer-bottle, bowl, bread, cafe, cake, carrot, champagne, champagne-bottle, cherries, chili-pepper, coaster, cocktail, coffee, coffee-maker, dairy, dining, drink, egg, flatware, food-and-drink, fork, fork-and-knife, frying-pan, grocery, highball, jar, knife, meat, microwave, nut, orange, oven, peanut, pear, pitcher, pot, poultry, pretzel, refrigerator, seed, soda-bottle, soy, spoon, squeeze-tube, stovetop, strawberry, toaster, tropical-cocktail, tumbler, wine, wine-bottle

### Objects (93)

activity, alarm, anchor, barcode, bathtub-shower, bed, blood-pressure, book, book-closed, bookmark, boombox, broom, calculator, camera, cash, cash-register, cassette, chart, clipping, clock, code-scan, command-line, computer, computer-chip, couch, defibrillator, duster, fabric-swatch, facial-tissues, fire-extinguisher, first-aid-kit, flag, flag-pennant, flag-swallowtail, gavel, glasses, grave, hair-care, hairdryer, heart-rate-monitor, invitation, key, keyboard, keypad, laptop, laundry-basket, laundry-detergent, laundry-dryer, laundry-washer, light-bulb, lipstick, magnet, mail, makeup-brush, medication, mirror, mobile, mop, necktie, ornament, paper-towels, pencil, perfume, pin, power, pump-bottle, push-pin, puzzle, receipt, rubber-stamp, ruler, safety-pin, screwdriver, scrub-brush, server, set-square, spray-bottle, stairs, sticker, sword, syringe, t-square, tablet, telephone, telescope, toilet, toilet-paper, towel, tshirt, vacuum-cleaner, watch-analog, whistle, wrench

### Smileys & People (68)

apron, baby, bag, baseball-cap, belt, bikini, boot, brain, button, chat, child, coat, comb, conceal, dialogue, dress, emoji, emoji-angry, emoji-disappointed, emoji-grinning, emoji-grinning-smiling-eyes, emoji-heart-eyes, emoji-neutral, emoji-sad, emoji-smiling-eyes, emoji-sunglasses, emoji-winking, friends, groups, hand, heart-rate, heartbroken, long-bone, lungs, meeting, menstrual-pad, mouth, pants, people, person-feminine, person-masculine, pram, pregnancy-test, profile, public, pump, scarf, service-counter, shirt, shoe, shorts, skirt, sock, stomach, stroller, suit, tampon, thinking, thought, thought-alert, thought-dialogue, throat, tooth, underwear, user, user-circle, user-circle-filled, walk

### Symbols (179)

accessibility, add, alert, aquarius, archive, aries, arrow-down, arrow-left, arrow-right, arrow-up, asterisk, attachment, backward, battery, battery-charged, battery-charging, bell-off, bluetooth, branch, brightness-high, browser-stop, calendar, calendar-day, calendar-week, camera-roll, cancer, capricorn, categories, checkmark, clear, close, column, comment, compose, contrast, create, crop, cursor, cursor-click, cut, dashboard, database, delete, dna, document, download, downward, drafts, eject, error, exclamation-mark, feed, filtered, first-aid, flash, folder, follow, following, forward, fragile, gear, gemini, government, grid, hanafuda, hashtag, heart, heart-outline, help-alternate, history, hourglass, inbox, info-alternate, judicial-scales, junk, language, layers, leo, libra, link, list, litter-disposal, location, lock, lock-keyhole, log-in, log-out, looped-square, mahjong, mathematics, merge, more, move, move-document, network, new-badge, new-document, new-folder, news, no, no-entry, notification, notion, paste, peace, pisces, playback-fast-forward, playback-next, playback-pause, playback-play, playback-play-button, playback-previous, playback-rewind, playback-stop, preview, print, private, promoted, question-mark, redirect, redo, reference, refresh, remove, rename, reorder, repeat, reply, reply-all, report, sagittarius, save, science, scorpio, search, send, send-to, share, sharing, shuffle, slide, sliders-vertical, slideshow, slideshow-play, smoking, smoking-no, snippet, subtitles, swap-horizontally, swap-vertically, symbol, sync, table, tabs, tag, taurus, thumbs-down, thumbs-up, token, transfers, unfollow, unlock, unlock-keyhole, upload, upward, username, verified, view, view-off, virgo, voicemail, volume-high, volume-off, warning, wheelchair-access, wifi, window, yin-yang

### Travel & Places (87)

arrivals, atm, backpack, baggage-claim, barricade, boat, briefcase, bunk-bed, bus, bus-double-decker, bus-metro, car, card, castle, church, city, compass, connecting-flight, customs, delivery-truck, departures, directional-sign, directional-sign-left, directional-sign-right, directions, do-not-disturb, earthquake, elevator, factory, flashlight, fuel, geography, globe, handbag, hanger, helicopter, helm, home, immigration, library, lost-and-found, lounge, luggage, luggage-cart, mandir, map, map-pin, map-pin-alternate, monorail, mosque, motorcycle, mountains, navigation, orbit, package, paifang, palm-tree, parking, parking-no, passport, postage-stamp, postcard, rocket, sailboat, school, scooter, shop, sink, steering-wheel, suitcase, sunglasses, sunscreen, suspension-bridge, synagogue, taxi, temple, torii, traffic-light, train, train-high-speed, train-light-rail, train-metro, truck, umbrella, volcano, wall
