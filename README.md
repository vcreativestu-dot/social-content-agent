# Social Content Agent

AI-powered social content generation tool for V Create Stu (VCREATIVE) — creating captions and visual assets for Facebook and Instagram.

## 📁 Project Structure

- `01-social-content.md` — Brand voice guidelines and caption writing rules
- `02-creative-designer.md` — Visual design guidelines  
- `creative-api.py` — API integration for image generation (FAL AI + ImgBB)
- `generate_*.py` — Utility scripts for specific design mockups
- `context/` — Context and reference materials
- `images/` — Source image assets
- `output/` — Generated images and content

## 🚀 Quick Start

1. Install dependencies:
```bash
pip install requests python-dotenv
```

2. Set up environment:
   - Copy `.env` template and add your API keys:
     - `FAL_API_KEY` — FAL AI API key for image generation
     - `IMGBB_API_KEY` — ImgBB API key for image hosting

3. Generate creative assets:
```bash
python creative-api.py v-core fb "Your prompt here"
```

## 🎨 Brand Guidelines

See `01-social-content.md` for:
- Brand voice and tone requirements
- Target audience persona
- Content categories and formats
- Product offerings (V-Core, V-Premium, V-Packaging, V-Digital Portfolio)

## 📧 Contact

vcreativestu@gmail.com
