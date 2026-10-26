# ЛЕПАТА — a personal wardrobe, before the first appointment

Separate brand copy: 26 October 2026. The existing design and interactions are reused without redesign. This is an independent concept, not official identity or an actual garment catalogue. The purpose is to help a visitor find a direction and talk to the atelier.

## References and adaptations

- https://styles.refero.design/style/cdc4a162-cefa-49a1-81e7-4857e421ae24 — Adam Lippes: generous image proportions, editorial fashion hierarchy and paper surfaces. Here the existing ultramarine and Cyrillic Prata/Golos stay, with 18px body and 16px controls instead of small monochrome navigation.
- https://21st.dev/@ibelick/components/spotlight — bounded light over a fixed frame. Public description and usage inspected; the actual component source requires an account. The implementation is original vanilla JS; no React dependency or copied source.
- https://motionsites.ai/lesson/cursor-tracking-website-with-motionsites — pointer movement controls a bounded visual response. Here the cropped photo and its decorative label respond; buttons and text do not move. Public material was consulted, not a paid prompt archive.
- Existing Diamond Cup in this project: the user's accepted reference for a subject-focused photographic hero with layered depth. This separate copy retains the atelier paper/ultramarine visual direction.

Reference reading does not imply live behavior testing. Main browser QA is coordinated by the parent task.

## Visual system

Paper #efefeb; ink #202221; ultramarine #304bc4; quiet text #61655f; rules #c6c9c1; light studio surface #e5e7df. Prata for display typography and large ЛЕПАТА wordmark, Golos Text for body and controls. Existing max width1380px and mobile side gaps20px. The original large wordmark replaces a tiny emblem; its curved underline is a quiet signature. It is not presented as the company's official identity.

## Final interaction map

| Area | Input → response | Touch/keyboard/reduced motion |
| --- | --- | --- |
| Hero | Pointer moves a cropped photograph at most12px/10px and0.6°, with a1.14 crop reserve; light and decorative label respond | Native image drag disabled. No fake fabric button or instructions. Reduced motion removes transforms. |
| Approach | Pointer bends the connecting thread and moves the three motif drawings | Stable copy; reduced motion is static. |
| Your wardrobe | Choose a complete dress/jacket/skirt illustration, colour and occasion; summary changes; CTA carries it into the enquiry block | Native radios and select; whole click targets stable. Cards' inner drawings respond to pointer. There is no drawing editor, SVG download or separately placed garment detail. |
| Colour studio | Match a reference sample using hue/saturation/lightness. Compare → numerical feedback and directional hints. Three rounds → completion and replay | Native range inputs and buttons; touch and keyboard supported. Optional hint adjusts one parameter for people who cannot distinguish the tones. Target colours are never altered. Background fold highlights alone follow pointer. |
| Contacts/footer | Thread/border response; actual phone/Telegram and honest demo form | Sticky Contacts remains visible; no personal-data persistence or real submissions. |

## QA path

Wardrobe: choose jacket, rose, special event; verify all illustrations use the selected colour and only jacket is selected. Click Discuss → expected idea in the booking panel, name field focused and visible below sticky header. Repeat with skirt/sage and ensure the idea replaces the previous one. Validate form failure, local success and reset.

Colour game: initial mismatch → Compare gives score and directions. Adjust each slider; the own sample changes while target stays fixed. Targets:

1. Ultramarine: hue227, saturation58, lightness48.
2. Dusty rose: hue351, saturation28, lightness61.
3. Sage: hue105, saturation12, lightness65.

90% or more completes a round. For a deterministic accessible path, activate Hint up to three times, then Compare. Pass all rounds, verify final result and restart. Buttons01–03 freely switch samples, retaining each sample’s slider values and solved score in session memory. Completion requires all three distinct samples, in any order. Next opens the next unsolved sample, wrapping after03; Restart clears every attempt. Repeated Compare cannot duplicate a solved sample. The accuracy is a game metric, not a colour-calibration instrument; display differences are disclosed.

Arrow SVGs point northeast at rest and right on hover/focus, without scroll rotation. Text selection changes only letter colour. Finite pointer loops stop on settling, hidden page and offscreen sections.

## Brand copy and contact provenance

User requested a fresh business copy of the current atelier concept. The source-guided references and all repaired interactions above are preserved. The large wordmark is now ЛЕПАТА and the favicon is a Cyrillic Л. This demo identity is not claimed as the official logo.

Company: Лепата — бренд-ателье. Original source list index 323 / spreadsheet row 325. Public sources checked on 26 October 2026:

- https://2gis.ru/moscow/firm/70000001092883218 — current business name, brand-atelier category, Волоколамское шоссе, 24 к2, Telegram channel and direct phone chat.
- https://2gis.ru/moscow/firm/70000001092883218/tab/info — tailoring and clothing-repair categories. Specific bespoke services are not asserted as confirmed; copy invites discussing the garment with the atelier.
- https://urbanplaces.su/ru_moskva/moskva/metro-streshnevo?page=2 — matching name, address and phone.
- https://t.me/%2B79261993843 — public direct-chat page confirms the matching phone.

Phone: +7 926 199-38-43. Accent Telegram action: https://t.me/+79261993843. Public channel: https://t.me/lepata_msk. Email not found in checked sources; no mailto or invented address. Own domain and clients.site not found by name/address/phone/handle search; this is a bounded finding, not a guarantee.

No hours, prices, testimonials, owner details or unverified guarantees were added. The photo is a retained concept illustration, not a claim about actual portfolio. Demo forms remain local-only and clear input on success. All animation/gameplay JS is byte-identical to the current repaired source atelier, including 01–03 sample switching and per-round memory.

Additional copy QA: check 320/390px sticky header, visible Contacts, new phone/Telegram/route and source dialog. Full browser QA and publication are coordinated by the parent task.
