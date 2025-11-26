# Static Site Generator Research for MetaRoss Blog

*Research date: 2025-01-26*

## The Goal
A **minimal, beautiful, life-healing** blog platform for medium-long form articles. Old-school blog aesthetic with:
- Clean list of articles
- Beautiful article pages
- Drop markdown → auto-publish via GitHub Actions
- Zero local tooling required
- Works on GitHub Pages

---

## Top Contenders

### 🐻 **#1: jekyllBear** (RECOMMENDED)
*Bear Blog aesthetic for Jekyll*

**Why it's special:**
- Philosophy: "No trackers, no javascript, no stylesheets. Just your words."
- IBM Plex Mono typography - technical yet natural
- Pages are ~2.7kb - incredibly fast
- Native GitHub Pages support (Jekyll)
- Focus on writing, not styling

**Setup complexity:** ⭐⭐ (Very easy)

**Perfect for:** Writers who want pure, distraction-free content delivery

**Links:**
- [GitHub](https://github.com/knhash/jekyllBear)
- [Demo](https://knhash.in/jekyllBear/)
- [Bear Blog Philosophy](https://bearblog.dev/)

---

### 📝 **#2: Jekyll Chirpy**
*Feature-rich technical writing theme*

**Why it's special:**
- Minimal sidebar layout
- Excellent for technical content
- Built-in search, tags, archives
- Dark mode toggle
- Active development (updated 2025)

**Setup complexity:** ⭐⭐⭐ (Moderate - more features = more config)

**Perfect for:** Technical blogs with categorization needs

**Links:**
- [Official Site](https://chirpy.cotes.page/)
- [GitHub](https://github.com/cotes2020/jekyll-theme-chirpy)
- [Quick Start Guide](https://chirpy.cotes.page/posts/getting-started/)

---

### ⚡ **#3: md2blog**
*Zero-config static site generator*

**Why it's special:**
- LITERALLY zero configuration
- Drop markdown files → instant blog
- Clean semantic HTML
- Only a few KB of CSS
- No JavaScript required
- Written in TypeScript/Deno

**Setup complexity:** ⭐ (Easiest possible)

**Perfect for:** Absolute minimalists who want hands-off publishing

**Caveat:** Less established, fewer examples, may need custom GitHub Action

**Links:**
- [GitHub](https://github.com/jaredkrinke/md2blog)
- [Documentation](https://jaredkrinke.github.io/md2blog/)

---

### 🚀 **#4: Hugo with Minimal Theme**
*Blazingly fast, single binary*

**Why it's special:**
- Builds in milliseconds (even 1000s of pages)
- Single binary (no Ruby/Node dependencies)
- Huge theme ecosystem
- Archie, Anatole, Paper themes are gorgeous

**Setup complexity:** ⭐⭐⭐ (Need custom GitHub Action, steeper learning curve)

**Perfect for:** Speed freaks and those who want ultimate performance

**Popular Minimal Themes:**
- [Archie](https://github.com/athul/archie) - Minimal and clean
- [Paper](https://github.com/nanxiaobei/hugo-paper) - Simple, beautiful
- [Anatole](https://github.com/lxndrblz/anatole) - Two-column minimal

**Links:**
- [Hugo](https://gohugo.io/)
- [Hugo Minimal Themes](https://themes.gohugo.io/tags/minimal/)

---

### 🎈 **#5: Eleventy (11ty)**
*Sweet spot of minimal + flexible*

**Why it's special:**
- JavaScript-based (easier for web devs)
- Extremely flexible templating
- Very active community
- "Minimal but not limiting"

**Setup complexity:** ⭐⭐⭐⭐ (Most flexible = most choices to make)

**Perfect for:** Those who want full control and customization

**Popular Themes:**
- Eleventy Duo - Minimal personal blog
- Eleventy Excellent - Modern starter

**Links:**
- [11ty](https://www.11ty.dev/)
- [11ty Themes](https://jamstackthemes.dev/ssg/eleventy/)

---

## Comparison Matrix

| Generator | Speed | Ease | Beauty | GH Pages | Zero Config |
|-----------|-------|------|--------|----------|-------------|
| jekyllBear | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | Native ✅ | Near-zero |
| Chirpy | ⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | Native ✅ | Low config |
| md2blog | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | Custom Action | TRUE zero |
| Hugo | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐ | Custom Action | Medium |
| 11ty | ⭐⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐⭐ | Custom Action | High config |

---

## Recommendation Hierarchy

### For "Life-Healing" Minimal Beauty:
**1. jekyllBear** - Pure, distraction-free, beautiful typography, zero bloat

### For Technical Writing:
**2. Jekyll Chirpy** - More features, still minimal, great for dev blogs

### For Absolute Simplicity:
**3. md2blog** - Drop files and forget, though less polished

### For Speed Demons:
**4. Hugo with Paper/Archie theme** - Millisecond builds, gorgeous themes

---

## Beautiful Example Sites

**Bear Blog Aesthetic:**
- [Bear Blog Examples](https://bearblog.dev/discover/) - Pure minimal blogs
- [jekyllBear Demo](https://knhash.in/jekyllBear/)

**Jekyll Chirpy Examples:**
- [Chirpy Demo](https://chirpy.cotes.page/)
- Active in 2025 blogging community

**Hugo Minimal:**
- [Hugo Showcase](https://gohugo.io/showcase/)
- Many personal blogs with Paper/Archie themes

---

## Setup Requirements (GitHub Pages)

### jekyllBear (EASIEST):
```
1. Fork jekyllBear repo or use as theme
2. Drop markdown in _posts/
3. Push to GitHub
4. Enable GitHub Pages
5. Done
```

### Jekyll Chirpy:
```
1. Use chirpy-starter template
2. Customize _config.yml
3. Add posts to _posts/
4. Push to GitHub
5. Auto-deploys
```

### md2blog:
```
1. Create GitHub Action for Deno
2. Add markdown files
3. Push
4. Custom action builds and deploys
```

### Hugo:
```
1. Create Hugo site structure
2. Add custom GitHub Action
3. Choose theme
4. Add markdown to content/
5. Push
```

---

## The "Life-Healing" Factor

**jekyllBear wins** because:
- No visual noise
- Pure typography focus
- Loads in milliseconds
- Feels like reading a book
- No distractions, no tracking, no bloat
- "Just your words"

This is the digital equivalent of a quiet room with good lighting and a comfortable chair.

---

## Next Steps

**Recommended:** Try jekyllBear first
- If you want more features → Chirpy
- If you need blazing speed → Hugo
- If you want full control → 11ty

All are checkpointed in git, so switching is risk-free.

---

## Sources
- [Jekyll Bear GitHub](https://github.com/knhash/jekyllBear)
- [Bear Blog Philosophy](https://bearblog.dev/)
- [Jekyll Chirpy](https://chirpy.cotes.page/)
- [md2blog](https://github.com/jaredkrinke/md2blog)
- [Hugo](https://gohugo.io/)
- [Eleventy](https://www.11ty.dev/)
- [Static Site Generators Comparison](https://jamstack.org/generators/)
- [Minimal Jekyll Themes](https://jekyllthemes.io/free)
