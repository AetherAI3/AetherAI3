# Profile badges

The Cloud and Bolt badges and icons are the original user-supplied animations, copied without changing their pixels or timing. The profile uses the transparent, icon-only GIFs. The labeled GIF and SVG versions remain available as alternatives.

Four matching SVG badges provide useful navigation: **Open Source**, **Aether Sites**, **Work With Me**, and **Sponsor**. Their pixel icons, dark background, border, and divider follow the supplied badge style. Text is stored as vector paths, so these badges need no external fonts, scripts, or image service.

The centered primary navigation adds **Aether AI** and **App Portal** badges. The Aether AI badge reuses the website mark from [`predator-cli/docs/assets/aether-website-mark.svg`](https://github.com/AetherAI3/predator-cli/blob/main/docs/assets/aether-website-mark.svg); its Æ symbol uses the original system-font fallback. The labels are vector paths. Both badges are self-contained.

Five smaller SVG badges link to **Online**, **Chat**, **Code**, **Design**, and **Trading**. They share a 30-pixel height, line icons, and vector text.

| Assets | Display size |
| --- | --- |
| Cloud and Bolt icon-only GIFs | 48 × 48 |
| Cloud, Bolt, Aether AI, App Portal, Open Source, Aether Sites, Work With Me, Sponsor badges | 176 × 36 |
| Online, Chat, Code, Design, Trading badges | 106 × 30 |

Use these display sizes for crisp pixels. Link destinations and accessible descriptions belong to the surrounding README link and image.

```html
<a href="https://github.com/AetherAI3/aether-agent">
  <img src="./assets/badges/bolt-icon.gif" width="48" height="48" alt="Explore Aether Agent">
</a>
```

Cloud loops every 1.85 seconds; Bolt loops every 1.43 seconds. GIF playback does not follow a reduced-motion preference. The original animated SVGs include a reduced-motion rule; support depends on the viewer.
