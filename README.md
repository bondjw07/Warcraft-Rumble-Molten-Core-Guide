
# Warcraft Rumble Boss Guides by Old Guardian

This project is a website dedicated to providing detailed boss guides for the game **Warcraft Rumble**, featuring builds and strategies from the YouTuber Old Guardian. Each boss guide includes recommended leaders, their respective minis, and unique talents for optimal gameplay, particularly for the **Molten Core Raid**.

## Features

- **Boss Guides**: Each boss section includes a list of recommended builds, each organized by **Leader** and **Mini** roles, complete with talent descriptions.
- **Responsive Design**: The site is fully responsive and can be easily accessed on both desktop and mobile devices.
- **Expanding Deck Details**: Each guide features an expandable "Deck Details" section, allowing users to view recommended builds without cluttering the interface.
- **Lightbox Image Display**: Each video thumbnail can be clicked to open a larger version in a lightbox overlay, enhancing the browsing experience.

## File Structure

```
/project-root
├── index.html          # Main HTML file for the website
├── images/             # Folder containing video thumbnail images for each boss guide
├── README.md           # This README file
```

## Setup

### Prerequisites

To host this project, you can use any static site hosting provider. **Cloudflare Pages**, **GitHub Pages**, and **Netlify** are popular options.

### Instructions

1. **Clone the Repository**: Clone or download this repository.
2. **Upload Files**: Ensure the `index.html` and `images/` folder are in the root directory of your hosting provider.
3. **Update Image Paths**: If you host images separately (e.g., on a CDN), update the `<img>` tags in `index.html` to reflect the correct URLs.

## Technologies Used

- **HTML/CSS**: For the structure and styling of the website.
- **JavaScript**: Adds functionality for the expanding deck details and lightbox image viewing.
- **Responsive Design**: Designed to work well on all screen sizes.

## Usage

- **Deck Details**: Click on the "Deck Details" button under each boss to view detailed mini and talent lists.
- **Lightbox**: Click on any video thumbnail to view a larger image in the center of the screen. Click the `X`, image, or press `Escape` to close the lightbox.

## Example Data Structure

Each boss guide section includes two leaders with their associated minis and talents. Below is a sample data structure for reference:

```html
<h4>Leader: Emperor Thaurissan</h4>
<div class="leader-talent">Talent: Hubris</div>
<ul>
    <li><span class="mini-name">Dark Iron Miner</span><span class="mini-talent">Gold Mine</span></li>
    <li><span class="mini-name">Whelp Eggs</span><span class="mini-talent">Flame Burst</span></li>
</ul>
```

## Contributing

Contributions to enhance the content, improve design, or add features are welcome! Please submit a pull request with any changes.

## License

This project is open-source and available under the MIT License.

---

Enjoy mastering Warcraft Rumble with these detailed boss guides!
