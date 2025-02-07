# hugo-kicking-the-tires

This repository is for **CIS 3500 at Penn**, where I am learning to use **Hugo** for building static websites. 

Apart from following the tutorial, I have added an extra page (resumé) for more practice and have made hyperlinks between pages (also clicking the page title redirects you to the main page).

## How to Run the Site

1. **Install Hugo** (if not already installed):  
   ```sh
   brew install hugo  # macOS
   sudo apt install hugo  # Linux (Debian-based)
   choco install hugo  # Windows (Chocolatey)
   ```
   Alternatively, download it from [Hugo's official site](https://gohugo.io/).

2. **Clone this repository**:
   ```sh
   git clone https://github.com/jm-wltr/hugo-kicking-the-tires.git
   cd hugo-kicking-the-tires
   ```

3. **Start the Hugo development server**:
   ```sh
   hugo server
   ```
   - The site will be available at **http://localhost:1313/**.

4. **To build the static site** (optional):
   ```sh
   hugo
   ```
   The generated site will be in the `public/` directory.

## Repository Structure
```
/hugo-kicking-the-tires
│── content/        # Markdown content files for the site
│── layouts/        # Custom HTML templates
│── static/         # Static assets (CSS, JS, images)
│── hugo.toml     # Hugo configuration file
│── themes/         # Theme files (if any)
└── public/         # Generated static site (after running `hugo`)
```
