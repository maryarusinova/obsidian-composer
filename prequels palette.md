prequels palette

You want 12 “color-base” values for the light theme (Tatooine), matching the structure of your dark theme, with strong cohesion and intensity, and a vibe that fits the prequel era (think: sun-bleached Tatooine, Coruscant, Naboo, Geonosis, etc). You like the “bold” options—so, richer, more saturated, not washed out.

Here are **three full 12-color base palettes** for your light theme, each with a slightly different flavor but all designed to pair perfectly with your Coruscant dark theme.

---

## Option 1: “Twin Suns Bold” (Classic Tatooine, warm and sandy)

| Variable         | Hex      | Description                |
|------------------|----------|----------------------------|
| --color-base-00  | #F5E3C6  | Lightest sand (background) |
| --color-base-05  | #F6E6DE  | Pale highlight             |
| --color-base-10  | #E6A84A  | Bold gold (sun accent)     |
| --color-base-20  | #E28A7A  | Warm coral                 |
| --color-base-25  | #C97A7A  | Dusty pink                 |
| --color-base-30  | #A3A98C  | Sage/olive                 |
| --color-base-35  | #B8BCB1  | Muted sage                 |
| --color-base-40  | #6B4F7A  | Deep purple accent         |
| --color-base-50  | #6E4B2F  | Rich brown                 |
| --color-base-60  | #A89B6B  | Warm stone                 |
| --color-base-70  | #C2C3B6  | Cool light gray            |
| --color-base-100 | #2C241A  | Deepest brown (contrast)   |

---

## Option 2: “Coruscant Sunrise” (urban, golden, a bit more neutral)

| Variable         | Hex      | Description                |
|------------------|----------|----------------------------|
| --color-base-00  | #F6E6DE  | Lightest cream             |
| --color-base-05  | #F5E3C6  | Sand highlight             |
| --color-base-10  | #E6A84A  | Gold (sunrise)             |
| --color-base-20  | #E6B0A2  | Warm peach                 |
| --color-base-25  | #C97A7A  | Muted rose                 |
| --color-base-30  | #A3A98C  | Sage                       |
| --color-base-35  | #BFB8A3  | Warm gray                  |
| --color-base-40  | #8B4A54  | Deep mauve                 |
| --color-base-50  | #6E4B2F  | Rich brown                 |
| --color-base-60  | #A89B6B  | Stone                      |
| --color-base-70  | #C2C3B6  | Cool gray                  |
| --color-base-100 | #2C241A  | Deep brown                 |

---

## Option 3: “Prequel Era” (Naboo/Geonosis, more color variety)

| Variable         | Hex      | Description                |
|------------------|----------|----------------------------|
| --color-base-00  | #F6E6DE  | Lightest cream             |
| --color-base-05  | #F5E3C6  | Sand                       |
| --color-base-10  | #E6A84A  | Gold                       |
| --color-base-20  | #E28A7A  | Coral                      |
| --color-base-25  | #C97A7A  | Pink                       |
| --color-base-30  | #6A8CB2  | Sky blue (Naboo lake)      |
| --color-base-35  | #A3A98C  | Sage                       |
| --color-base-40  | #5A5A6E  | Deep blue-violet           |
| --color-base-50  | #6E4B2F  | Rich brown                 |
| --color-base-60  | #A89B6B  | Stone                      |
| --color-base-70  | #C2C3B6  | Cool gray                  |
| --color-base-100 | #2C241A  | Deep brown                 |

---

**How to use:**  
- Use 00/05 for backgrounds, 10/20/25 for accents, 30/35/40 for secondary UI, 50/60/70 for text/contrast, 100 for deepest contrast.
- All colors are bold enough to stand up to your dark theme, and the palette structure matches your Coruscant setup for easy theme switching.

Want a CSS variable block for any of these? Want a palette with more blue, more pink, or more “Coruscant city” vibes? Just say the word.

Perfect, you want to **keep Coruscant dark as-is** (no changes), and explore how to build a light theme that’s either:
- A mirrored/echoed structure of the dark theme (using the same 12 color-base variables, mapped to similar UI roles), or
- A new, cohesive Coruscant light theme (“Coruscant Sunrise”) that’s a true sibling to your dark (“Coruscant Sunset”), possibly with more metallic/urban vibes.

You’re open to splitting Tatooine off as its own thing later, and you have more Coruscant screenshots/palettes if needed.

Let’s proceed step by step, starting with the **mirrored structure** using the bold options you listed.  
**I’ll show you how each palette would look if you mapped the 12 color-base variables to the same roles as your dark theme, but with the new light colors.**

---

## 1. “Tatooine Classic Bold” (mirrored structure)

| Variable         | Hex      | Description                |
|------------------|----------|----------------------------|
| --color-base-00  | #F5E3C6  | Lightest sand (background) |
| --color-base-05  | #F6E6DE  | Pale highlight             |
| --color-base-10  | #E6A84A  | Bold gold (sun accent)     |
| --color-base-20  | #E28A7A  | Warm coral                 |
| --color-base-25  | #C97A7A  | Dusty pink                 |
| --color-base-30  | #A3A98C  | Sage/olive                 |
| --color-base-35  | #B8BCB1  | Muted sage                 |
| --color-base-40  | #6B4F7A  | Deep purple accent         |
| --color-base-50  | #6E4B2F  | Rich brown                 |
| --color-base-60  | #A89B6B  | Warm stone                 |
| --color-base-70  | #C2C3B6  | Cool light gray            |
| --color-base-100 | #2C241A  | Deepest brown (contrast)   |

**How to use:**  
- 00/05: backgrounds, 10/20/25: accents, 30/35/40: secondary UI, 50/60/70: text/contrast, 100: deepest contrast.
- This palette is warm, sandy, and bold—mirrors the structure of your dark theme, but with a Tatooine vibe.

---

## 2. “Sunset Fade Bold” (mirrored structure)

| Variable         | Hex      | Description                |
|------------------|----------|----------------------------|
| --color-base-00  | #F5E3C6  | Lightest sand              |
| --color-base-05  | #A3A98C  | Sage                       |
| --color-base-10  | #C97A7A  | Dusty pink                 |
| --color-base-20  | #8B4A54  | Deep mauve                 |
| --color-base-25  | #E28A7A  | Strong coral               |
| --color-base-30  | #6E4B2F  | Rich brown                 |
| --color-base-35  | #E6A84A  | Bold gold                  |
| --color-base-40  | #B8BCB1  | Muted sage                 |
| --color-base-50  | #A89B6B  | Warm stone                 |
| --color-base-60  | #C2C3B6  | Cool light gray            |
| --color-base-70  | #6B4F7A  | Deep purple                |
| --color-base-100 | #2C241A  | Deepest brown              |

---

## 3. “Cave & Sky Bold” (mirrored structure)

| Variable         | Hex      | Description                |
|------------------|----------|----------------------------|
| --color-base-00  | #C2C3B6  | Deeper gray                |
| --color-base-05  | #A89B6B  | Warm stone                 |
| --color-base-10  | #5A5A6E  | Deep blue-violet           |
| --color-base-20  | #6A8CB2  | Bolder sky blue            |
| --color-base-25  | #E6A84A  | Bold gold                  |
| --color-base-30  | #2C241A  | Dark olive                 |
| --color-base-35  | #BFB8A3  | Warm gray                  |
| --color-base-40  | #A3A98C  | Sage                       |
| --color-base-50  | #C97A7A  | Dusty pink                 |
| --color-base-60  | #E28A7A  | Strong coral               |
| --color-base-70  | #F6E6DE  | Pale highlight             |
| --color-base-100 | #6E4B2F  | Rich brown                 |

---

## 4. “Desert Dusk Bold” (mirrored structure)

| Variable         | Hex      | Description                |
|------------------|----------|----------------------------|
| --color-base-00  | #E6B0A2  | Rich peach                 |
| --color-base-05  | #A89B6B  | Deeper stone               |
| --color-base-10  | #8B4A54  | Saturated mauve            |
| --color-base-20  | #6E4B2F  | Strong brown               |
| --color-base-25  | #6B4F7A  | Deep purple                |
| --color-base-30  | #E28A7A  | Strong coral               |
| --color-base-35  | #C97A7A  | Dusty pink                 |
| --color-base-40  | #B8BCB1  | Muted sage                 |
| --color-base-50  | #A3A98C  | Sage/olive                 |
| --color-base-60  | #C2C3B6  | Cool light gray            |
| --color-base-70  | #F6E6DE  | Pale highlight             |
| --color-base-100 | #2C241A  | Deepest brown              |

---

## 5. “Twin Suns Bold” (mirrored structure)

| Variable         | Hex      | Description                |
|------------------|----------|----------------------------|
| --color-base-00  | #F5E3C6  | Lightest sand              |
| --color-base-05  | #F6E6DE  | Pale highlight             |
| --color-base-10  | #E6A84A  | Bold gold                  |
| --color-base-20  | #E28A7A  | Warm coral                 |
| --color-base-25  | #C97A7A  | Dusty pink                 |
| --color-base-30  | #A3A98C  | Sage/olive                 |
| --color-base-35  | #B8BCB1  | Muted sage                 |
| --color-base-40  | #6B4F7A  | Deep purple                |
| --color-base-50  | #6E4B2F  | Rich brown                 |
| --color-base-60  | #A89B6B  | Warm stone                 |
| --color-base-70  | #C2C3B6  | Cool light gray            |
| --color-base-100 | #2C241A  | Deepest brown              |

---

## 6. “Coruscant Sunrise” (urban, golden, a bit more neutral)

| Variable         | Hex      | Description                |
|------------------|----------|----------------------------|
| --color-base-00  | #F6E6DE  | Lightest cream             |
| --color-base-05  | #F5E3C6  | Sand highlight             |
| --color-base-10  | #E6A84A  | Gold (sunrise)             |
| --color-base-20  | #E6B0A2  | Warm peach                 |
| --color-base-25  | #C97A7A  | Muted rose                 |
| --color-base-30  | #A3A98C  | Sage                       |
| --color-base-35  | #BFB8A3  | Warm gray                  |
| --color-base-40  | #8B4A54  | Deep mauve                 |
| --color-base-50  | #6E4B2F  | Rich brown                 |
| --color-base-60  | #A89B6B  | Stone                      |
| --color-base-70  | #C2C3B6  | Cool gray                  |
| --color-base-100 | #2C241A  | Deep brown                 |

---

**Next steps:**  
- If you want to see a side-by-side mapping of these with your current dark theme, or want to try a “Coruscant Sunrise” using your new screenshots for more metallic/urban accents, just say so and drop the screenshots/palettes.
- If you want to move forward with a Tatooine theme as a separate thing, we can do that too.

Let me know which direction you want to go next, or if you want a CSS variable block for any of these!

