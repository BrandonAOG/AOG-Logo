# AOG Logo Repository — README

```markdown
# 🔥 AOG Logo — Always On Generators

Official brand logo assets for **Always On Generators**.
Used across all AOG Field Operations Hub tools, forms, and
internal business applications.

> **Repository:** https://github.com/BrandonAOG/AOG-Logo

---

## 🖼 Asset Overview

| File | Description |
|---|---|
| `AOG-Logo.png` | Primary brand logo — full color |

---

## 🚀 Usage in AOG Hub Tools

All AOG Field Operations Hub applications reference this logo
directly via the GitHub raw content CDN so every tool always
displays the current approved version without manual updates.

### Direct Image URL

```html
<!-- Always points to the latest committed version -->
<img
  src="https://raw.githubusercontent.com/BrandonAOG/AOG-Logo/main/AOG-Logo.png"
  alt="Always On Generators Logo"
>
```

### Circular Profile Style (used across all AOG forms)

```html
<img
  src="https://raw.githubusercontent.com/BrandonAOG/AOG-Logo/main/AOG-Logo.png"
  alt="Always On Generators Logo"
  style="
    width: 40px;
    height: 40px;
    border-radius: 50%;
    object-fit: cover;
    display: block;
  "
>
```

### Google Profile CDN (current implementation)

```html
<!-- Used in production across all AOG tools -->
<img
  src="https://lh3.googleusercontent.com/a/ACg8ocJP3abFJ_3mTYZ2vCcFGJ5eDsMroNqrPrfd3aX3T5Pa-Xq7SVg=s317-c-no"
  alt="Always On Generators Logo"
  style="width:40px;height:40px;border-radius:50%;object-fit:cover;"
>
```

---

## 🎨 Brand Colors

These colors are consistent across all AOG tools and documents.

| Role | Color Name | Hex | Usage |
|---|---|---|---|
| **Primary** | AOG Amber | `#D97706` | Logo text, accents, borders |
| **Primary Dark** | Amber Dim | `#B45309` | Hover states, depth |
| **Primary Darker** | Amber Dark | `#92400E` | Pressed states |
| **Dark UI Accent** | Neon Cyan | `#00FFC8` | Dark mode highlights |
| **Dark UI Secondary** | Cyan Dim | `#06B6D4` | Dark mode borders |
| **Success / Yes** | Emerald | `#059669` | YES checkboxes |
| **Danger / No** | Red | `#DC2626` | NO checkboxes |
| **Background Light** | Pure White | `#FFFFFF` | Light mode panels |
| **Background Dark** | Deep Navy | `#0A0E27` | Dark mode base |
| **Text Light** | Charcoal | `#1F2937` | Light mode body text |
| **Text Dark** | Ice Blue | `#E0F7FF` | Dark mode body text |

---

## 🔤 Brand Typography

| Role | Font | Source |
|---|---|---|
| **Display / Headers** | Orbitron | Google Fonts |
| **Monospace / Data** | Share Tech Mono | Google Fonts |
| **Body / UI** | Exo 2 | Google Fonts |
| **Fallback** | Arial, sans-serif | System |

```html
<!-- Google Fonts import used across all AOG tools -->
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;500;700;900&family=Share+Tech+Mono&family=Exo+2:wght@300;400;500;600&display=swap" rel="stylesheet">
```

---

## 🗂 File Structure

```
AOG-Logo/
├── AOG-Logo.png     ← Primary logo asset
└── README.md        ← Readme 
```

---

## 📐 Recommended Display Sizes

| Context | Size | Shape |
|---|---|---|
| Action bar / form header | 40 × 40 px | Circle |
| Print header | 50 × 50 px | Circle |
| Hub dashboard card | 60 × 60 px | Circle |
| Full-size display | Native resolution | Original |

---

## 🔗 Used In

| Repository | Tool |
|---|---|
| [`AOG-hub`](https://github.com/BrandonAOG/AOG-hub) | Central Forms Hub dashboard |
| [`Installforms`](https://github.com/BrandonAOG/Installforms) | Electrical installation checklist |
| [`Maintenance`](https://github.com/BrandonAOG/Maintenance) | Generator maintenance report |
| [`Generator-estimate-form`](https://github.com/BrandonAOG/Generator-estimate-form) | Estimate & quote form |
| [`Site-visit`](https://github.com/BrandonAOG/Site-visit) | Site inspection log |
| [`Sketchpad`](https://github.com/BrandonAOG/Sketchpad) | Freehand field drawing tool |
| [`Permit`](https://github.com/BrandonAOG/Permit) | Permitting info request form |

---

## ✏️ Updating the Logo

1. Prepare the new file — name it exactly `AOG-Logo.png`
2. Open the repository on GitHub
3. Click **Add file → Upload files**
4. Drag and drop the new `AOG-Logo.png` and commit
5. All AOG tools referencing the raw GitHub URL will
   automatically display the updated logo on next page load

> ⚠️ **Keep the filename identical.**
> All production tools reference `AOG-Logo.png` by name.
> Renaming the file will break the logo across every AOG application.

---

## 📄 License

Internal brand asset — © Always On Generators.  
Not licensed for redistribution or external use.

---

## 👤 Author

**Brandon** — Always On Generators  
GitHub: [@BrandonAOG](https://github.com/BrandonAOG)
```

---

### Optional badges

```markdown
![Brand Asset](https://img.shields.io/badge/Type-Brand%20Asset-orange?style=flat-square)
![PNG](https://img.shields.io/badge/Format-PNG-blue?style=flat-square)
![AOG Hub](https://img.shields.io/badge/Used%20In-AOG%20Hub-green?style=flat-square)
![CDN Ready](https://img.shields.io/badge/CDN-GitHub%20Raw-lightgrey?style=flat-square&logo=github)
```
