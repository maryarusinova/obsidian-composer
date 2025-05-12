comparison.md
Here’s a **side-by-side** of your current Coruscant dark theme and the new Coruscant Sunrise light palette, with each color-base variable mapped to its counterpart.  
Below, I’ll give you concrete suggestions to make them even more cohesive.

---

### **Side-by-Side: Coruscant Dark vs. Coruscant Sunrise Light**

| Variable         | Coruscant Dark         | Coruscant Sunrise Light   |
|------------------|-----------------------|--------------------------|
| --color-base-00  | #F0F1F2 (light gray)  | #F2D3AC (light gold/cream)|
| --color-base-05  | #F2C6B6 (peach)       | #BFBFBF (light metallic gray)|
| --color-base-10  | #F2A285 (peach-orange)| #E6A84A (sunrise gold)   |
| --color-base-20  | #F29472 (muted orange)| #F2C0A2 (warm peach)     |
| --color-base-25  | #F26B5E (coral)       | #BF7D65 (urban clay)     |
| --color-base-30  | #38464B (slate blue)  | #A6A1A1 (cool metallic gray)|
| --color-base-35  | #3C3E40 (dark gray)   | #2F3240 (urban blue-gray)|
| --color-base-40  | #313D40 (blue-gray)   | #152C40 (deep city blue) |
| --color-base-50  | #38464B (slate blue)  | #3B3C59 (muted purple/blue)|
| --color-base-60  | #1B3240 (deep blue)   | #A67D03 (urban gold)     |
| --color-base-70  | #1B363D (deep blue-green)| #D0D0DD (pale blue-gray)|
| --color-base-100 | #593325 (deep brown)  | #0D0D0D (deepest black)  |

---

### **How to Make It More Cohesive**

#### 1. **Echo Key Accents**
- Use the same gold for --color-base-10 in both (or as close as possible).
- Use a similar peach/coral for --color-base-20/25.

#### 2. **Match Contrast Levels**
- Make sure the light theme’s darkest color (--color-base-100) is as deep as the dark theme’s lightest color (--color-base-00) is bright.
- Consider using #593325 (deep brown) as --color-base-100 in the light theme for a more direct callback.

#### 3. **Keep Blues and Grays in Sync**
- Use the same blue-gray family for --color-base-30, 35, 40, 50 in both themes, just inverted in intensity.
- For example, if --color-base-30 is #38464B in dark, use a lighter version in light, like #A6A1A1.

#### 4. **Accent Consistency**
- If you use a neon accent (like #D25EF2 or #F24949) in one, use it in the other for links, highlights, or selection.

#### 5. **UI Element Mapping**
- Map backgrounds, cards, and borders to the same variable numbers in both themes for a seamless switch.

---

### **Tweaked Palette for Maximum Cohesion**

Here’s a slightly tweaked “Coruscant Sunrise” palette, with even more direct callbacks:

| Variable         | Hex      | Note (callback)             |
|------------------|----------|-----------------------------|
| --color-base-00  | #F0F1F2  | (same as dark)              |
| --color-base-05  | #F2C6B6  | (same as dark)              |
| --color-base-10  | #E6A84A  | (gold, matches dark accent) |
| --color-base-20  | #F29472  | (muted orange, matches dark)|
| --color-base-25  | #F26B5E  | (coral, matches dark)       |
| --color-base-30  | #A6A1A1  | (light blue-gray echo)      |
| --color-base-35  | #BFBFBF  | (light gray echo)           |
| --color-base-40  | #2F3240  | (urban blue-gray, dark echo)|
| --color-base-50  | #3B3C59  | (muted purple/blue)         |
| --color-base-60  | #A67D03  | (urban gold)                |
| --color-base-70  | #D0D0DD  | (pale blue-gray)            |
| --color-base-100 | #593325  | (deep brown, matches dark)  |

**This version is even more “mirrored” and will feel like a true sibling to your Coruscant dark.**

---

**Want a CSS variable block for this? Want to see a UI mockup? Want to tweak any color further? Drop your feedback or more screenshots if you want to push the metallic/urban vibe even harder!**
