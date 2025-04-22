# 🖼️ iplaceholder.com  
**Instant Custom Placeholder Image Generator**  
*Generate dynamic placeholder images via URL parameters. Perfect for developers, designers, and content creators.*  

---

## 🚀 Features  
- **Instant Image Generation**  
  - Specify dimensions, text, colors, and format directly in the URL.  
- **Multi-Format Support**  
  - Generate `WebP`, `PNG`, `SVG`, or `JPEG` images for optimal performance.  
- **Advanced Customization**  
  - Background/text colors using **hex codes**, **CSS names**.  
  - Custom fonts (web-safe) and adjustable font sizes.  
  - Multi-line text support with `\n` line breaks.  
  - Auto-word wrapping.  
- **Developer-Friendly API**  
  - Integrate placeholder images into projects with simple HTTP requests.  
- **Privacy-First**  
  - No tracking, cookies, or user data collection.  

---

## ⚡ Quick Start  
### Basic Syntax  
```bash
https://iplaceholder.com/{width}x{height}.{format}?param=value
```
OR
```bash
https://iplaceholder.com/{width}x{height}/{bgColor}/{textColor}.{format}?param=value
```

## 📌 Parameters

| Parameter     | Type       | Description                                         | Example Values                  |
|---------------|------------|-----------------------------------------------------|---------------------------------|
| **`width`**   | `integer`  | Image width in pixels (1–5000)                      | `800`                           |
| **`height`**  | `integer`  | Image height in pixels (1–5000)                     | `600`                           |
| **`format`**  | `string`   | Output format (`webp`, `png`, `jpg`, `svg`)         | `webp` (default)                |
| **`bg`**      | `string`   | Background color (hex, CSS nam)                     | `f5f5f5`, `lightblue`           |
| **`color`**   | `string`   | Text color (hex, CSS name)                          | `333`, `darkred`                |
| **`text`**    | `string`   | Custom text (URL-encoded, use `\n` for newlines)    | `Sample+Text`, `Line1\nLine2`   |
| **`font`**    | `string`   | Font family (web-safe or registered fonts)          | `Arial`, `Roboto`, `Open+Sans`  |
| **`fontsize`**| `integer`  | Font size in pixels                                 | `32` (default)                  |

### Notes:
1. **Color Formats**:
   ```bash
   # Hex (3/6-digit)
   bg=fff or bg=ffffff
   
   # CSS Names
   color=red
   ```

## 🖼️ Examples

### 1️⃣ Basic Placeholder
```bash
https://iplaceholder.com/300x300.png
```
OR
```bash
https://iplaceholder.com/300.png
```
![image](https://iplaceholder.com/300.png)

### 2️⃣ Custom Colors & Text
```bash
https://iplaceholder.com/1024x768/2d2d2d/81d4fa/png?text=Dashboard+Mockup
```
![image](https://iplaceholder.com/1024x768/2d2d2d/81d4fa/png?text=Dashboard+Mockup)

### 3️⃣ Multi-Line Text
```bash
https://iplaceholder.com/1200x630.jpg?text=Blog\nHeader&fontsize=42
```
![image](https://iplaceholder.com/1200x630.jpg?text=Blog\nHeader&fontsize=42)

### 4️⃣ WebP with High Quality
```bash
https://iplaceholder.com/1920x1080.webp
```
![image](https://iplaceholder.com/1920x1080.webp)


### 5️⃣ Custom Font (Georgia)
```bash
https://iplaceholder.com/600x400.png?font=Georgia&fontsize=28&text=Product+Card
```
![image](https://iplaceholder.com/600x400.png?font=Georgia&fontsize=28&text=Product+Card)

### 6️⃣ Transparent PNG
```bash
https://iplaceholder.com/500x500/transparent/000.png?text=Logo+Placeholder
```
![image](https://iplaceholder.com/500x500/transparent/000.png?text=Logo+Placeholder)

---

## 🚀 Why iplaceholder.com?
- **Zero Configuration**
  - Generate images instantly – no signup, API keys, or account required.
- **Blazing Fast**
  - Global CDN ensures responses in <100ms.
- **Free Forever**
  - Open for personal and commercial use.
- **Developer-Friendly**
  - Simple integration with frontend frameworks, CMS platforms, and design tools.

## 📚 Use Cases
- Rapid prototyping for web/mobile apps
- Database/CMS placeholder content
- Responsive layout testing
- Presentation/demo mockups
- Social media template designs

## Start Generating Now!
[https://iplaceholder.com](https://iplaceholder.com)

Built with ❤️ for developers, designers, and creators.
