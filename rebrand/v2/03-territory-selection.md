## TERRITORY EVALUATION

### Territory 1: Ink & Conviction
The cobalt-ink accent is intelligent and the white editorial stance is a clean break from the current brand, but this direction walks directly into the trap its own risk analysis names and then cannot escape: the DRI already pays for four financial newsletters, and this looks precisely like a fifth. In a mobile feed the differentiation from Seeking Alpha, Axios Macro, and Morning Brew is entirely dependent on copywriting quality and typographic craft that no CSS system can guarantee — one underfunded sprint and this becomes another premium news reader with a fancier font. For B2B pitch decks it performs well, but "reads well" is not the same as "owns a category," and at Boosted.ai's inflection point those are not equivalent outcomes.

**Score: 6/10**

### Territory 2: The Bound Edition
The warm charcoal and claret execution is genuinely beautiful and the emotional argument for warm-vs-cold dark is strategically sound — it directly addresses the current brand's coldness problem. The drop cap gesture is an unusually brave move for software. The fatal problem is the one the brief identifies itself and then underweights: this is the correct answer a senior brand consultant would give. Mercury, Brex's premium executions, and a wave of wealth management rebrands from the past 18 months have already colonized warm-dark-editorial territory. The risk is not failure — it is quiet success, which at this company's inflection point is equally bad. "Harvey for finance" is a derivative positioning move for a company attempting to define a new category, not join an existing aesthetic.

**Score: 7/10**

### Territory 3: The Official Record
The parchment-violet-condensed system is the only direction here that owns a visual category rather than inhabiting one already in occupation. Nothing in the competitive landscape — Bloomberg, FactSet, Robinhood, Public.com, Kalshi, Harvey — occupies parchment-plus-electric-violet. The stamp gesture solves a genuine product design problem that the other territories do not address: visually segregating AI-generated output from editorial context is a real trust and credibility problem, and The Official Record resolves it through brand language rather than UI chrome. The condensed single-typeface constraint is operationally a feature — systems that are hard to execute consistently are hard for competitors to copy and hard for internal teams to dilute through off-brand decisions. The institutional entry point is the strongest of the three territories: financial institutions live in documents, and parchment creates unconscious familiarity with their native visual world while looking nothing like any current vendor. The DRI entry point — access to the previously restricted — is more emotionally specific and acquisition-useful than the aspiration-through-warmth of Territory 2 or the premium-newsletter feel of Territory 1.

**Score: 9/10**

---

## SELECTED TERRITORY: THE OFFICIAL RECORD

Territory 3 wins because it is the only direction in which the same visual system serves both audiences through a single coherent logic rather than a split-the-difference compromise. Institutional buyers live in documents — filings, prospectuses, research reports, compliance submissions — and parchment creates native visual familiarity while being completely novel in their vendor landscape. For the DRI, parchment-plus-violet reads as simultaneously premium and modern, which is the exact emotional tension required for "this was made for someone I want to become." Territory 1 blends with the newsletter stack it is trying to transcend. Territory 2 is the competent, trend-adjacent answer. Territory 3 is the only one with enough visual specificity to become defensible intellectual property: the stamp gesture, the condensed single-face system, and the violet-as-AI-layer are all load-bearing brand assets simultaneously. The biggest acknowledged risk — violet adjacency with Notion and Figma — is neutralized by execution context: at Alfa's financial-document register, on parchment, with condensed architectural type, the violet reads nothing like a productivity tool. The color becomes the brand.

---

## NAMING RECOMMENDATION

**Company:** Alfa — elevated from product name to master brand. Replace Boosted.ai at the corporate entity level. Alfa has eight years of institutional relationship equity, speaks finance natively, carries an implicit performance claim (alpha generation) that no other single word delivers with equivalent authority, and the endorsed master brand architecture is clean and scalable.

**Consumer product:** Alfa — unmodified, no suffix. The flagship consumer product carries the parent name directly. This is the strategic signal that consumer is the company's primary future: the unmodified name goes to the most important product.

**Institutional suite:** Alfa Pro for the PM and analyst research tool at hedge funds and asset managers. Alfa Platform for the API and MCP developer infrastructure serving quants and engineers. Both products carry master brand credibility; the suffix targets the specific buyer without diluting the parent.

**Fallback if trademark is blocked:** Vela as the company name, Alfa product family retained underneath in an endorsed architecture. Do not replace both simultaneously — the institutional equity embedded in eight years of Alfa product relationship is real and worth preserving even under a new corporate name.

---

## CSS EXECUTION BRIEF

:root {

  /* ============================================
     SURFACES
     Primary ground: parchment #E8E0CE
     The warmth is load-bearing — do not substitute
     cool white or neutral gray
  ============================================ */
  --surface-page:        #E8E0CE;
  --surface-card:        #DDD4BC;
  --surface-raised:      #EDE6D5;
  --surface-overlay:     rgba(12, 9, 6, 0.55);
  --surface-stamp:       #D8CEBC;
  --surface-on-brand:    #F0EBE0;

  /* ============================================
     TEXT
     Near-black is warm-undertoned ink, not
     digital black. Preserve the undertone.
  ============================================ */
  --text-primary:        #0C0906;
  --text-secondary:      #3A3028;
  --text-muted:          #6B5D52;
  --text-disabled:       #A0918A;
  --text-on-brand:       #F0EBE0;
  --text-on-dark:        #E8E0CE;

  /* ============================================
     BRAND
     Electric Violet #4718DC.
     This color has one job: marking Alfa output.
     It appears on: stamp borders, active states,
     model-generated signals, scored outputs.
     It never appears decoratively.
  ============================================ */
  --brand:               #4718DC;
  --brand-hover:         #3910B8;
  --brand-active:        #2D0A96;
  --brand-subtle:        rgba(71, 24, 220, 0.07);
  --brand-subtle-hover:  rgba(71, 24, 220, 0.13);
  --brand-border:        rgba(71, 24, 220, 0.38);

  /* ============================================
     SEMANTIC
     Colors must hold legibility against
     --surface-page (#E8E0CE). All are dark,
     saturated, warm-undertoned.
  ============================================ */
  --success:             #1A6B3A;
  --success-subtle:      rgba(26, 107, 58, 0.09);
  --warning:             #7A4800;
  --warning-subtle:      rgba(122, 72, 0, 0.09);
  --error:               #8C1F2E;
  --error-subtle:        rgba(140, 31, 46, 0.09);

  /* ============================================
     BORDERS
     --border-stamp is always violet.
     No other border uses color.
  ============================================ */
  --border:              rgba(12, 9, 6, 0.16);
  --border-subtle:       rgba(12, 9, 6, 0.08);
  --border-strong:       rgba(12, 9, 6, 0.32);
  --border-stamp:        #4718DC;

  /* ============================================
     TYPOGRAPHY
     One typeface family. No exceptions.
     Primary: Barlow Condensed (Google Fonts, free).
     Licensed alternative: Aktiv Grotesk Condensed.
     No serifs. No italics. No other families.
  ============================================ */
  --font-sans:           'Barlow Condensed', 'Aktiv Grotesk Condensed',
                         'Helvetica Neue Condensed', 'Arial Narrow',
                         'Liberation Sans Narrow', sans-serif;
  --font-mono:           'IBM Plex Mono', 'Fira Code',
                         'Cascadia Code', 'Courier New', monospace;

  --font-weight-light:   300;
  --font-weight-regular: 400;
  --font-weight-medium:  500;
  --font-weight-bold:    700;
  --font-weight-black:   900;

  /* ============================================
     TYPE SCALE
     All values in rem. 1rem = 16px default.
     Three operational registers:
     — Display (--text-4xl and above): hero, page title
     — Body (--text-base to --text-xl): prose, UI
     — Data/Label (--text-xs to --text-sm): numbers, caps
     Hierarchy through scale contrast only.
  ============================================ */
  --text-xs:             0.625rem;
  --text-sm:             0.75rem;
  --text-base:           1rem;
  --text-lg:             1.125rem;
  --text-xl:             1.375rem;
  --text-2xl:            1.75rem;
  --text-3xl:            2.5rem;
  --text-4xl:            4rem;

  /* ============================================
     LINE HEIGHTS
     Condensed face at display sizes needs
     --leading-tight to preserve architectural
     density. Never use loose leading above
     --text-2xl.
  ============================================ */
  --leading-tight:       0.95;
  --leading-snug:        1.1;
  --leading-normal:      1.4;
  --leading-relaxed:     1.65;

  /* ============================================
     LETTER SPACING
     --tracking-wider is for uppercase labels,
     stamp headers, and field names only.
     Do not use on body or display type.
  ============================================ */
  --tracking-tight:      -0.02em;
  --tracking-normal:     0em;
  --tracking-wide:       0.06em;
  --tracking-wider:      0.12em;

  /* ============================================
     SPACING
     4px base unit throughout.
  ============================================ */
  --space-1:             0.25rem;
  --space-2:             0.5rem;
  --space-3:             0.75rem;
  --space-4:             1rem;
  --space-5:             1.25rem;
  --space-6:             1.5rem;
  --space-8:             2rem;
  --space-10:            2.5rem;
  --space-12:            3rem;
  --space-16:            4rem;
  --space-20:            5rem;
  --space-24:            6rem;

  /* ============================================
     RADII
     The Official Record is rectilinear.
     Minimal rounding for usability only.
     No pill shapes. No decorative curves.
     --radius-full is 2px — even badge elements
     stay nearly square.
  ============================================ */
  --radius-sm:           1px;
  --radius-md:           2px;
  --radius-lg:           2px;
  --radius-xl:           3px;
  --radius-full:         2px;

  /* ============================================
     LAYOUT
  ============================================ */
  --max-width:           1280px;
  --max-width-text:      72ch;
  --container-padding:   clamp(1rem, 4vw, 4rem);
  --column-gap:          var(--space-8);

  /* ============================================
     SHADOWS
     Restrained. Stamps use inset border, not
     drop shadow. Depth through surface color
     differentiation, not elevation.
  ============================================ */
  --shadow-sm:           0 1px 2px rgba(12, 9, 6, 0.10);
  --shadow-md:           0 2px 8px rgba(12, 9, 6, 0.09),
                         0 1px 2px rgba(12, 9, 6, 0.07);
  --shadow-stamp:        inset 0 0 0 1.5px var(--brand);

  /* ============================================
     TRANSITIONS
  ============================================ */
  --transition-fast:     100ms ease;
  --transition-base:     180ms ease;
  --transition-slow:     280ms ease;

}

/* ============================================
   DARK MODE
   Dark mode is the parchment palette inverted
   to warm near-black. The parchment color
   migrates from background to text.
   Violet brightens slightly for contrast.
============================================ */
@media (prefers-color-scheme: dark) {
  :root {
    --surface-page:        #1A1510;
    --surface-card:        #221D17;
    --surface-raised:      #2A2318;
    --surface-overlay:     rgba(232, 224, 206, 0.08);
    --surface-stamp:       #201A13;
    --surface-on-brand:    #F0EBE0;

    --text-primary:        #E8E0CE;
    --text-secondary:      #C4B89E;
    --text-muted:          #8A7B6A;
    --text-disabled:       #57493D;
    --text-on-brand:       #F0EBE0;
    --text-on-dark:        #E8E0CE;

    --brand:               #6B40FF;
    --brand-hover:         #7B55FF;
    --brand-active:        #5530E0;
    --brand-subtle:        rgba(107, 64, 255, 0.12);
    --brand-subtle-hover:  rgba(107, 64, 255, 0.20);
    --brand-border:        rgba(107, 64, 255, 0.42);

    --success:             #3DA05A;
    --success-subtle:      rgba(61, 160, 90, 0.12);
    --warning:             #C4873A;
    --warning-subtle:      rgba(196, 135, 58, 0.12);
    --error:               #C44058;
    --error-subtle:        rgba(196, 64, 88, 0.12);

    --border:              rgba(232, 224, 206, 0.13);
    --border-subtle:       rgba(232, 224, 206, 0.06);
    --border-strong:       rgba(232, 224, 206, 0.26);
    --border-stamp:        #6B40FF;

    --shadow-sm:           0 1px 2px rgba(0, 0, 0, 0.32);
    --shadow-md:           0 2px 8px rgba(0, 0, 0, 0.30),
                           0 1px 2px rgba(0, 0, 0, 0.22);
    --shadow-stamp:        inset 0 0 0 1.5px var(--brand);
  }
}

:root[data-theme="dark"] {
  --surface-page:        #1A1510;
  --surface-card:        #221D17;
  --surface-raised:      #2A2318;
  --surface-overlay:     rgba(232, 224, 206, 0.08);
  --surface-stamp:       #201A13;
  --surface-on-brand:    #F0EBE0;
  --text-primary:        #E8E0CE;
  --text-secondary:      #C4B89E;
  --text-muted:          #8A7B6A;
  --text-disabled:       #57493D;
  --text-on-brand:       #F0EBE0;
  --text-on-dark:        #E8E0CE;
  --brand:               #6B40FF;
  --brand-hover:         #7B55FF;
  --brand-active:        #5530E0;
  --brand-subtle:        rgba(107, 64, 255, 0.12);
  --brand-subtle-hover:  rgba(107, 64, 255, 0.20);
  --brand-border:        rgba(107, 64, 255, 0.42);
  --success:             #3DA05A;
  --success-subtle:      rgba(61, 160, 90, 0.12);
  --warning:             #C4873A;
  --warning-subtle:      rgba(196, 135, 58, 0.12);
  --error:               #C44058;
  --error-subtle:        rgba(196, 64, 88, 0.12);
  --border:              rgba(232, 224, 206, 0.13);
  --border-subtle:       rgba(232, 224, 206, 0.06);
  --border-strong:       rgba(232, 224, 206, 0.26);
  --border-stamp:        #6B40FF;
  --shadow-sm:           0 1px 2px rgba(0, 0, 0, 0.32);
  --shadow-md:           0 2px 8px rgba(0, 0, 0, 0.30),
                         0 1px 2px rgba(0, 0, 0, 0.22);
  --shadow-stamp:        inset 0 0 0 1.5px var(--brand);
}

:root[data-theme="light"] {
  --surface-page:        #E8E0CE;
  --surface-card:        #DDD4BC;
  --surface-raised:      #EDE6D5;
  --surface-overlay:     rgba(12, 9, 6, 0.55);
  --surface-stamp:       #D8CEBC;
  --surface-on-brand:    #F0EBE0;
  --text-primary:        #0C0906;
  --text-secondary:      #3A3028;
  --text-muted:          #6B5D52;
  --text-disabled:       #A0918A;
  --text-on-brand:       #F0EBE0;
  --text-on-dark:        #E8E0CE;
  --brand:               #4718DC;
  --brand-hover:         #3910B8;
  --brand-active:        #2D0A96;
  --brand-subtle:        rgba(71, 24, 220, 0.07);
  --brand-subtle-hover:  rgba(71, 24, 220, 0.13);
  --brand-border:        rgba(71, 24, 220, 0.38);
  --success:             #1A6B3A;
  --success-subtle:      rgba(26, 107, 58, 0.09);
  --warning:             #7A4800;
  --warning-subtle:      rgba(122, 72, 0, 0.09);
  --error:               #8C1F2E;
  --error-subtle:        rgba(140, 31, 46, 0.09);
  --border:              rgba(12, 9, 6, 0.16);
  --border-subtle:       rgba(12, 9, 6, 0.08);
  --border-strong:       rgba(12, 9, 6, 0.32);
  --border-stamp:        #4718DC;
  --shadow-sm:           0 1px 2px rgba(12, 9, 6, 0.10);
  --shadow-md:           0 2px 8px rgba(12, 9, 6, 0.09),
                         0 1px 2px rgba(12, 9, 6, 0.07);
  --shadow-stamp:        inset 0 0 0 1.5px var(--brand);
}

---

## SIGNATURE VISUAL GESTURE: THE STAMP

The stamp is a rectangular block element — no border radius beyond --radius-md — defined by a 1.5px solid border in --border-stamp (var(--brand) violet). Background inside the stamp is --surface-stamp, fractionally darker than the page ground to create material separation without elevation.

The stamp's purpose is categorical and non-negotiable: it appears exclusively when Alfa has generated a specific output. It marks price targets, earnings revisions, high-conviction signals, scored recommendations, and model-derived classifications. It does not appear on editorial content, user-generated context, third-party data, or navigational elements. The visual rule is: violet border means the model said this. Everything else has no violet border.

Implementation: a .stamp utility class carries `box-shadow: var(--shadow-stamp)` as the border mechanism (inset, so it does not affect layout). Padding inside stamps is --space-3 on all sides minimum. Data values inside stamps render at --font-weight-bold, 1.5–2x the surrounding text scale. The stamp label (e.g., "ALFA SIGNAL", "CONVICTION: HIGH") renders at --text-xs, --font-weight-medium, --tracking-wider, uppercase, in --text-muted — never in violet itself. The signal value renders in --text-primary at increased scale. The stamp is the only place in the UI where --font-weight-black appears at sizes below --text-3xl.

On filled stamps (e.g., a high-conviction CTA block): background becomes --brand, all text becomes --text-on-brand, border is removed. This variant is used sparingly — maximum once per full-page view.

---

## TYPOGRAPHY RULES

One typeface family only: Barlow Condensed. No exceptions at any breakpoint, in any context, across any product surface. The constraint is the system. Violation of this rule does not produce a slightly off-brand result — it collapses the entire architectural argument.

Three scale registers, each with a single permitted weight:

Display register (--text-3xl and above): --font-weight-black (900), --leading-tight (0.95), --tracking-tight (-0.02em). Left-aligned always. Never centered. Used for: homepage hero, section landmarks, and modal headers. At hero scale (96–120pt equivalent, above the --text-4xl token), the type fills the container width edge-to-edge with maximum optical compression. The text-align is left and the type is set to fill — not a fixed font-size, but a clamp or viewport unit that produces edge-to-edge presence.

Body register (--text-base to --text-xl): --font-weight-regular (400), --leading-normal (1.4), --tracking-normal. This is the prose register for analysis, explanations, and running content. Line length is capped at --max-width-text (72ch). No bold in prose runs — if emphasis is required, it appears through scale promotion to the next register, not through weight change within the same scale.

Data and label register (--text-xs to --text-sm): --font-weight-medium (500), --leading-tight, --tracking-wider (0.12em), uppercase. Used for: field labels, column headers, category stamps, navigation items, metadata. The combination of condensed face at small size with wide tracking and uppercase produces a dense, architectural label that references form-field and filing typography.

No italics anywhere in the system. The typeface has an italic cut — it is not used. The reason is categorical: italic in this system would introduce a humanist, expressive gesture that contradicts the declarative, documentary character of the brand.

---

## BUTTON STYLE

Primary button: background --brand (#4718DC), text --text-on-brand (#F0EBE0), border: none, border-radius: --radius-md (2px). Label is uppercase, --font-weight-bold, --tracking-wider, --text-sm. Height 40px standard, 32px compact (dense data tables), 48px hero CTAs. Hover state: background --brand-hover, no transform, no shadow. Active state: background --brand-active. Focus state: outline 2px solid --brand, outline-offset 2px. No gradient fills. No icon-only variants at sizes below 32px.

Secondary button: background transparent, border 1.5px solid --brand, color --brand, same label treatment as primary. Hover: background --brand-subtle. The secondary button's border matches the stamp border weight (1.5px) — this is intentional visual rhyming.

Ghost button: no border, no background, color --brand, label underline on hover only (text-decoration: underline, text-underline-offset: 3px). Used for tertiary actions and inline links within dense data contexts.

Destructive button: primary button spec with --error substituted for --brand across all states. Never use red for anything non-destructive.

Never use rounded buttons (pill shape). Border radius maximum is --radius-md. The rectilinear shape is load-bearing.

---

## CARD AND PANEL TREATMENT

Standard card: background --surface-card, border 1px solid --border, border-radius --radius-md (2px), padding --space-6. No drop shadow by default. Cards do not use hover color transitions — on hover, the border upgrades to 1.5px solid --border-stamp (violet). This is the stamp gesture intrusion: interaction reveals the AI layer's visual signature.

Raised panel: background --surface-raised, box-shadow --shadow-md, border 1px solid --border-subtle, border-radius --radius-md. Used for: modals, popovers, dropdown menus. Not cards — raised panels are temporary surfaces.

Stamp panel: background --surface-stamp, box-shadow --shadow-stamp (inset 0 0 0 1.5px var(--brand)), border-radius --radius-sm (1px). This is the most opinionated surface treatment in the system. It is used exclusively for Alfa-generated content blocks. Under no circumstances should a stamp panel be used as a decorative card variant for non-AI content.

No gradients on any surface. No decorative illustrations, chart background patterns, or data visualizations used as card backgrounds. No rounded corners beyond --radius-xl (3px) on any element in the system. Content inside cards is left-aligned. Card headers use the data/label register (uppercase, --text-sm, --tracking-wider, --text-muted) separated from body content by a 1px --border line rule, not a size or weight change.

---

## BRAND MARK DIRECTION

The logotype is "ALFA" set in Barlow Condensed Black (--font-weight-black), fully uppercase, letter-spaced at approximately 0.04em. There is no logomark. There is no icon. There is no symbol. The typographic treatment is the mark. This is not a placeholder pending a symbol design — it is the final decision. The brand's authority comes from the word itself, not from an abstract form associated with it.

At large display scale — homepage hero, conference materials, large-format applications — the logotype fills the container width horizontally, edge-to-edge, maximum compression. This is the architectural gesture: the name as a building facade, not a badge. The type is set to fill the available horizontal space at whatever size that requires.

At standard UI scale — navigation bar, mobile header, email footer — the logotype is set at a fixed size, --font-weight-black, left-aligned, in --text-primary. It does not require clearspace rules beyond the standard container padding (--container-padding). It does not lock up with taglines at small sizes.

Color rule: the brand mark renders in --text-primary (#0C0906) on all parchment and light surfaces. It renders in --text-on-brand (#F0EBE0) when placed on violet backgrounds. It never renders in violet itself. This is a categorical rule with strategic logic: violet marks Alfa outputs. The brand mark is not an output — it is the entity that produces outputs. The color distinction enforces this separation at the visual layer.

Favicon and app icon: the letterform "A" from Barlow Condensed Black, contained in a 1:1 parchment (#E8E0CE) square field. No border radius on the app icon. The "A" is set at approximately 72% of the icon's height, vertically and horizontally centered, in --text-primary. This produces an icon that reads as a document, not an app — which is the correct register.