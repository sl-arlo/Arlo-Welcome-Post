# Arlo Welcome Post Generator

How to use the Arlo welcome post generator.

## How to use

1. **Open the generator**  
   Use the hosted version: [sl-arlo.github.io/Arlo-Welcome-Post](https://sl-arlo.github.io/Arlo-Welcome-Post/).

   Or serve this folder over HTTP (required for fonts and PNG export):
   ```bash
   python3 -m http.server 8080
   ```
   Then visit `http://localhost:8080`.

2. **Fill in your details**
   - **Name** – Full name (e.g. Jane Doe).
   - **Role** – Job title (e.g. Head of Engineering).
   - **Photo** – Upload a headshot, then use **Zoom**, **Horizontal**, and **Vertical** to frame it.
   - **Quote** – Optional quote used by the **With Quote** style.

3. **Pick a style**  
   Choose **Default** or **With Quote** in the preview.

4. **Export**  
   Click **Download PNG** (or **Copy image**) under the style you want. Output is 1200×1200.

5. **Adjust typography** (optional)  
   Use the **Title**, **Role**, and **Quote** sliders under Role. Each has a Reset button.

## Styles

- **Default** – Large headline (“Meet the {Role}, {Name}!”) with a bordered headshot and role pill.
- **With Quote** – “Welcome to the Arlo Team!” with a smaller headshot, name/role, and quote.
