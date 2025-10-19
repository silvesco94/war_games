# Baseball Analytics Blog

This is a co-authored baseball analytics blog built with GitHub Pages.

## Purpose

A shared analytics-focused blog where each article is:

- A standalone GitHub repository
- Includes Python-based analysis (Colab or scripts)
- Static images and charts
- Linked or embedded code
- Lightweight, Git-backed publishing

## Structure

This central repository serves as the homepage and index:

- `index.md`: The home page of the blog — links to individual article repos and preview images
- `_config.yml`: Site settings for GitHub Pages (Jekyll)
- `assets/images/`: Contains preview images (thumbnails) for each article

baseball-analytics-blog/

├── README.md # How the hub works

├── _config.yml # Tells GitHub Pages how to render the site

├── index.md # Homepage - links to each article's repo

└── assets/images/ # Article thumbnails (e.g., batting-trends-2025.png)


## Contributing

1. Create a new GitHub repository for your article  
   (e.g., `batting-trends-2025` or `pitching-heatmaps`)
2. Include the following in your article repo:
   - `README.md` with article content
   - Any `.py` or `.ipynb` scripts
   - Charts/images
3. Add the thumbnail image for your article to the `assets/images/` folder in this central repo  
   (e.g., `assets/images/batting-trends-2025.png`)
4. Add a link + author byline + thumbnail to your article in the `index.md` file.  
   Example format:
   ```markdown
   ### [Article Title](https://github.com/your-org/article-repo)
   *by **Your Name***

   ![Article Preview](assets/images/your-thumbnail.png)
   
5. Submit a Pull Request to this repo with your updates to:
   - `assets/images/`
   - `index.md`
6. Add a Back to War Games button at the very top of your article’s README.md for easy navigation:
   - [⬅️ Back to War Games](https://silvesco94.github.io/war_games/)
   

## Live Blog

🔗 (https://silvesco94.github.io/war_games/)

Explore our posts via the homepage — each includes a visual preview.

