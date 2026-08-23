<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 024 project banner" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 024

### Let a real source-bound subject pass through one pale geometric emotion window

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#four-outputs-one-geometric-emotion-window-logic)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#boundaries-and-trust)

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> PHOTOGRAPHIC SUBJECT · NARROW PALE WINDOW · SOURCE-ADAPTIVE DIRECTION · EASTERN WHITESPACE · PREMIUM EDITORIAL TYPE

XXD Panel 024 is an image-generation Skill for Codex and compatible agents. It locks identity, contour, pose, action, function, material, and true colour, then chooses one horizontal, vertical, or diagonal narrow pale low-saturation geometric window according to subject weight, action direction, contour flow, and page rhythm.

The photographic or finely realistic subject enters that window and performs one clear local crossing, extension, frame break, or passage. A source-derived pale block, true subject colour, sparse neutral type, white/pale-grey/pale-warm ground, generous Eastern whitespace, and at most one faint cultural or linear support layer create a premium brand-advertising and magazine finish.

## Why it exists

A “subject through a colour block” easily collapses into a complete cut-out pasted over a decorative stripe, with a direction unrelated to action, over-smoothed material, and whitespace filled by pattern and sales copy.

024 reverses that logic:

```text
lock source identity / material / true colour / principal action → choose a horizontal / vertical / diagonal narrow pale window from weight and contour → make the real subject enter and perform one local crossing → place it on a white / pale-grey / pale-warm ground with generous whitespace → allow at most one faint cultural or linear support layer → combine source-derived pale window + true subject colour + sparse neutral type → finish title and microtype along the window-subject-whitespace relation
```

If an unrelated photograph could replace the source without materially changing window direction, subject crossing, material, true colour, focal balance, support layer, or copy, the result is not 024.

## The 024 visual contract

- **One narrow pale window:** horizontal, vertical, or diagonal orientation follows source weight, action, and contour; reject multiple blocks, huge boards, and fixed-direction templates.
- **Real subject crossing:** preserve at least three source-specific identity, material, colour, pose, action, and relation cues; the subject enters and performs one clear local crossing.
- **Never a complete pasted cut-out:** the subject feels naturally grown, frame-breaking, or spatially penetrating.
- **Eastern whitespace:** white, pale grey, or extremely pale warm ground remains light; centre, offset, vertical growth, or horizontal extension still yields one focus.
- **At most one support layer:** a faint cultural pattern, topographic line, ripple, light contour, or abstract linear mark stays subordinate.
- **Source-derived commercial colour:** pale window + true subject colour + sparse neutral type; no fluorescent saturation, muddy grey, heavy darkness, or global filter.
- **Premium editorial type:** one short title and sparse subtitle/place/state/microtext align with the window, crossing direction, or whitespace.

## Samples · Coming soon

The repository reserves [`assets/examples/`](assets/examples/) for future work. Only finished 024 artwork verified by the project owner will be added; no post or image from another style is used as a placeholder.

Future samples will demonstrate 024's adaptability. Their subjects, metaphors, palette, copy, and canvas ratios will never become generation references or defaults.

## Four outputs, one geometric-emotion-window logic

The four modes support single or multiple selection. Reply with `1`, `1+3`, `1,2,4`, or `all`; the Skill deduplicates and runs them in menu order 1→4. Every mode is delivered independently in its own task directory—never as an overview—and `all` yields seven PNGs per source (one for each ordinary mode plus four wallpapers). Sizes may be labelled by mode in the same reply; unlabeled ordinary modes remain source-adaptive. Copy is shared across selected modes by default and may be overridden per mode.

| Mode | Sizing logic | Deliverable |
| --- | --- | --- |
| `top-bottom` | source-adaptive | complete source above, 024 real-subject-through-pale-window design below; both panels retain the source size and split exactly 50/50 |
| `left-right` | source-adaptive | complete source left, 024 real-subject-through-pale-window design right; both panels retain the source size and split exactly 50/50 |
| `design-only` | source-adaptive | transformed design only, with no visible source photo; retains source ratio and dimensions |
| `wallpaper-pack` | four device sizes | separate phone, iPad, desktop, and children's-watch PNGs |

Exact user pixels > explicit ratio or destination > source adaptation for ordinary modes. The original `024.md` used a 3:4 creative canvas, but that historical example is not a silent default in the current Skill.

Photography in paired modes stays truthful, with only restrained grading and necessary environmental extension. Design-only and wallpapers still use the photograph as evidence but do not show it.

### Wallpaper packs: linked or independent

Wallpaper mode has no silent size default. Choose the common preset—phone `1440×3200`, iPad `2048×2732`, desktop `3840×2160`, watch `1024×1024`—or give labelled custom sizes.

- **Linked pack (recommended):** generate and approve the iPad anchor first; every other device references the original photo plus that same anchor and is recomposed for its canvas.
- **Independent set:** every device references only the source photograph and may explore different field orientation, subject occupancy, breakout feature, clean-line rhythm, single colour signal, and type relation.

Linked never means cropped. All four files are separately generated, composed, and reviewed, with no iPad→phone→desktop→watch reference chain.

## Copy must belong to the field and breakout action

Before generation, choose automatic copy, custom copy, or text-free output. Name the target language or locale whenever copy is present.

Automatic copy distils one short title from visible or supported emotion, action, relation, time, or small story. It may be warm, restrained, quiet, humorous, or lonely, but must remain inseparable from this image.

Add one or two micro-elements, a grounded quote-like line, number, or chapter mark only when useful. Dates, places, provenance, and numbers must be supplied or reliably established and are never fabricated merely to look sophisticated. Copy must still pass the unrelated-image swap test.

Finished user wording stays verbatim. A direction or editable draft is refined only while preserving audience, purpose, mandatory words, tone, and implication.

Language follows the intended audience rather than the command language:

```text
target market or audience > requested output language > direction language; if none is explicit, ask before generation
```

A Japanese edition uses natural Japanese, a Korean-audience edition uses natural Korean and correct spacing, a UK edition uses British English, and Arabic defaults to natural Modern Standard Arabic with genuine right-to-left composition. The Skill never guesses nationality from appearance, clothing, scenery, or signs and never uses pseudo-foreign text.

## Code guarantees geometry; image generation creates the artwork

The image model creates the source-bound realistic subject, narrow pale window, one local crossing, true material and colour, Eastern whitespace, faint support layer, and premium commercial editorial type. `scripts/compose_panel.py` only plans canvases, performs exact 50/50 raster composition, finalises dimensions, and audits results. It never fakes artwork with programmatic drawing.

```bash
python3 scripts/compose_panel.py --plan --layout top-bottom --source photo.png
python3 scripts/compose_panel.py --plan --layout left-right --size 2560x1440
python3 scripts/compose_panel.py --audit result.png --layout design-only --size 2048x2048
```

Exact top-bottom canvases need an even total height; left-right canvases need an even total width. Requested pixels are never silently changed.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-024.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-024" ~/.codex/skills/xxd-panel-024
```

Claude Code users may link the same directory to `~/.claude/skills/xxd-panel-024`. Restart the agent session after installation.

```text
$xxd-panel-024
Turn this photograph into a left-right composition. Derive the copy from the image and write it in natural Korean.
```

You may invoke the Skill with only a photograph. It first asks for one or more modes in a numbered multiline menu, then for copy settings; wallpaper mode also asks for linked/independent continuity and device sizes.

Full specifications:

- [Skill workflow](SKILL.md)
- [Chinese full prompt](references/xxd-panel-024-prompt.zh-CN.md)
- [English full prompt](references/xxd-panel-024-prompt.en.md)
- [Original style brief](references/024-source.md)

## Boundaries and trust

- Each photograph stays within its own task and never borrows subjects, colours, copy, or composition from other inputs, old results, or samples.
- Every invocation creates a fresh task directory; even identical sources and parameters must generate anew.
- Deliverables are PNG bitmaps, never SVG, HTML, Canvas, or programmatic-drawing substitutes.
- The configured bitmap bridge emits sanitised status only and does not expose providers, endpoints, headers, credentials, prompts, or response bodies.
- Each selected ordinary mode returns one file; selected `wallpaper-pack` adds four separate wallpapers. `all` returns seven PNGs per source across four sibling mode directories, never a contact sheet or overview.

Local composition needs Python 3 and Pillow. The safe bitmap bridge uses Python 3.11+ `tomllib`. Image generation still requires a host agent with built-in raster generation or an already configured compatible raster route.

## Repository

```text
xxd-panel-024/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/ (reserved for future local samples)
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-024-prompt.zh-CN.md
    ├── xxd-panel-024-prompt.en.md
    └── 024-source.md
```

## About XXD

XXD is the abbreviated brand name of Xiaoxiaodong. This project is created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and Membership

### In-depth Consultation · CNY 299/hour

One-to-one consultation for using the Skills is billed at CNY 299 per hour. Contact Xiaoxiaodong through the WeChat QR code below to book.

### Xiaoxiaodong Skills User Community · CNY 99 to join

A one-time CNY 99 fee joins the community for workflow sharing, work discussion, and peer support. It does not include hourly one-to-one consultation. Include “Skills User Community” in your WeChat message.

### Knowledge Planet + Member Prompt Library · CNY 699/year

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) and the [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/) are one membership: **one annual payment unlocks both, with no second purchase required.**

1. Subscribe through [Knowledge Planet](https://wx.zsxq.com/group/15554814142882), then contact Xiaoxiaodong on WeChat for a Prompt Library redemption code.
2. Subscribe through the [Member Prompt Library](https://vip.xiaoxiaodong.ai/), then contact Xiaoxiaodong on WeChat for a Knowledge Planet invitation.

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD paid community WeChat QR code" width="320"></a>
</p>

<div align="center">

**The block is not decoration; it is the space through which the real subject breathes.**

</div>

---

<div align="center">
  <h2>☕ Support this open-source project</h2>
  <p>If this project saved you time, a Star, a share, or a coffee helps keep it moving.</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Support Xiaoxiaodong through Buy Me a Coffee" width="180"></a><br>
        <strong>Buy me a coffee</strong><br>
        <sub>Scan or open the QR code to support Xiaoxiaodong</sub>
      </td>
    </tr>
  </table>
  <p><sub>Support is entirely optional and never changes access to this open-source project.</sub></p>
</div>
