---
order: 900
icon: paintbrush
label: Themes
nav:
  badge: NEW|info
tags: [guide]  
---

# Themes
Profilie's theme system empowers you to effortlessly customize the visual style of your website, giving it a unique personality and aesthetic appeal.  

With themes, you can easily change the color schemes and overall look of your profile to match your personal branding or preferred vibe.

Currently, Profilie offers **4 amazing themes**:

- [x] Azure
- [x] Sapphire
- [x] Mint
- [x] Maple

## Azure Theme
The Azure theme features a clean, sky-blue palette inspired by serene skies and expansive horizons.  

**Highlights:**  
- Bright, calming sky blue tones  
- Modern, minimalistic design  
- Perfect for a fresh, professional look

Ideal for professional portfolios, personal sites, or any project seeking a fresh, crisp look

### How to Apply
To apply the Azure theme, include the following link in your HTML <head>:

```html
<link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/azure.css">
```

## Sapphire Theme
The Sapphire theme offers a deep, luxurious dark blue aesthetic reminiscent of precious sapphires.  

**Highlights:**  
- Elegant, dark color scheme  
- Emphasizes content with contrasting lighter text  
- Suitable for a sleek, sophisticated vibe

### How to Apply

Add this line to your <head> section:

```html
<link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/sapphire.css">
```

## Mint Theme
The Mint theme presents a vibrant, refreshing green palette inspired by fresh mint leaves.  

**Highlights:**  
- Refreshing, lively green colors  
- Playful yet professional design  
- Easy on the eyes

### How to Apply
Include this link in your <head>:

```html
<link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/mint.css">
```

## Maple Theme
Maple showcases warm, inviting orange tones inspired by autumn leaves and maple syrup.  

**Highlights:**  
- Warm, inviting color palette  
- Rustic and cozy aesthetic  
- Suitable for personal profiles, creative portfolios, or socials

### How to Apply
Add this stylesheet link:

```html
<link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/maple.css">
```

## Switching Themes
To change your website’s appearance, simply update the link tags in your `index.html`.  

**Best Practices:**
Use only one theme at a time!
Uncomment only the stylesheet for your chosen theme; comment out or remove others to avoid conflicts.

```html Example
<!-- <link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/mint.css"> -->
<!-- <link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/maple.css"> -->
<!-- <link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/azure.css"> -->
  
<link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/sapphire.css">
```

!!!danger
Only include one stylesheet at a time.
Having multiple active stylesheets can cause `JavaScript Loading Error` and break your site's appearance.
!!!

### How to Change Your Theme
Suppose you're using the Sapphire theme and want to switch to Mint. To switch from Sapphire to Mint:

1. In your `<head>`, find the theme stylesheet links.
2. **Comment out** or **remove** the current theme stylesheet (e.g., Sapphire):

```html
<!-- <link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/sapphire.css" /> -->
```

3. **Uncomment** the new theme (Mint):

```html
<link rel="stylesheet" href="//cdn.harys.is-a.dev/profilie/lib/themes/mint.css" />
```

## Need help or want to request new themes?
Feel free to open an issue or the discussion in our [**GitHub repository**](https://github.com/profilie/profilie/). We love hearing your ideas!
