# MacDigiPet website

Static Astro site. Run `npm run dev` for local preview and `npm run build` to generate `dist/`. Publish the generated directory using the intended static host. Hosting and the final domain are not configured here; `astro.config.mjs` still uses an example domain.

## Community and support

Ko-fi is the primary support option for an international audience; Saweria follows for local Indonesian support. `src/config.ts` keeps both support links and the supplied Discord invite. All three public destinations were checked on 13 October 2026 and showed MacDigiPet.

Discord is the primary community invitation across the site. Everyone can join to follow development, chat and share ideas without applying for beta testing or having completed Digimon World 1. A beta is planned, but no release date has been set; copy must not imply immediate access or available early builds.

`/beta` explains the community and planned beta, with optional future-testing interest collected in Discord’s public `#beta-interest` channel. All beta testers must have played and completed Digimon World 1. Interested testers provide Mac model/chip, macOS version, completion confirmation, a brief playthrough description and intended testing focus. When testing is ready, the developer reviews interest and assigns `Beta Tester` manually; Discord does not verify game completion automatically. The site does not collect email, store signups, grant roles or reserve slots. Donations do not determine beta access.

## Wallpaper preview

`/wallpaper` offers the existing village V4 HEIC as a free direct download, four lightweight JPEG previews, setup steps and optional Saweria/Ko-fi support. The source asset is `../Assets/Wallpapers/Village-v4/consistent-cg-4k/dw1-village-v4-dynamic.heic`; its site copy is `public/downloads/macdigipet-village-v4-dynamic.heic`.

SHA-256: `4569c0aaf38641e947ccf57239f6057c2b996f2a29670f55a1289d79f3673248`. Size: 25,133,535 bytes. Four 3840×2400 frames, with local time boundaries at 05:00, 10:00, 16:00 and 19:00.

The existing native `VillageWallpaperExportChecks` passed unchanged: image dimensions and colors, primary day frame, light/dark indices and all 1440 minute selections. macOS HEIC decoding required access outside the shell sandbox; sandboxed decoding produced empty pixels. Installing in System Settings and observing automatic changes across sleep/wake and time boundaries remain untested. Keep the preview label until those checks pass. No wallpaper settings were changed.

## Review and launch priorities

`/license` explains original project material, AI-assisted artwork, franchise rights, a limited personal non-commercial wallpaper permission, code/dependency licensing, voluntary support and rights inquiries through Discord. It grants no third-party rights or blanket open-source license. Links appear in the shared footer, support and wallpaper pages.

- The configured public app release URL currently returns GitHub 404. Resolve release availability before advertising a ready app download. `/download` now describes development status rather than promising a ready DMG.
- Set the final domain and absolute social-sharing image URL before launch.
- Add a short real app demo showing care, movement and village interactions.
- Test the dynamic wallpaper on supported macOS versions, including sleep/wake and different display ratios.
- Review artwork and franchise rights before a public release. Free access, voluntary donations and a fan-project disclaimer do not establish authorization to use protected work. See [WIPO’s copyright FAQ](https://www.wipo.int/en/web/copyright/faq-copyright).

## Verification

Astro built all 10 routes successfully. The home, wallpaper, beta and support pages were checked at 320, 768, 1024 and 1440px with no horizontal overflow, broken images or browser console warnings/errors. Every built local link and asset resolves, placeholder links are gone, and the shipped HEIC matches the source checksum. Saweria and Ko-fi are both available on support, home, beta, wallpaper and the shared footer. Changes are local; no public deployment was performed.

Copyright & License addition: all 11 routes built successfully, internal license links and anchors resolve, and the new page passed responsive checks at 320, 768, 1024 and 1440px with no console warnings/errors.

Community and planned-beta copy update: all 11 routes built successfully. Home, community/beta, app updates, support and wallpaper pages passed browser checks at 320, 768, 1024 and 1440px with no horizontal overflow, broken images or console warnings/errors. The primary invitation is to join Discord; future beta testing is optional and has no announced release date. Changes remain local.

## Discord beta setup — 13 October 2026

Configured in the existing MacDigiPet server through its owner’s Discord session after explicit approval:

- `Beta Tester`: no server-wide permission grants, no Administrator or management permissions, zero assigned members at completion.
- Public `#beta-interest`: application instructions and completed-Digimon-World-1 requirement in its topic.
- Private `Beta` category: `@everyone` denied visibility; `Beta Tester` allowed visibility, message history and sending messages. Server owner retains access.
- Private `#beta-downloads`: topic with release-post guidance; tester overrides deny Send Messages, Send Messages in Threads, Create Public Threads and Create Private Threads. Visibility and history access remain available.
- Private `#beta-feedback` and `#beta-bugs`: inherit category access; topics provide feedback and reproduction guidance.

Verified with Discord’s View Server As Role: `@everyone` sees the public application channel and none of the three private beta channels; `Beta Tester` sees all three private channels, gets a no-send-permission notice in downloads, and has a message composer in feedback and bugs. Role preview was disabled afterwards. No messages were sent, testers assigned or app builds uploaded.

Channel links:

- [Applications](https://discord.com/channels/1559478817733615738/1559503654892081162)
- [Downloads](https://discord.com/channels/1559478817733615738/1559505688630136842)
- [Feedback](https://discord.com/channels/1559478817733615738/1559505768787607593)
- [Bugs](https://discord.com/channels/1559478817733615738/1559505845778124901)
