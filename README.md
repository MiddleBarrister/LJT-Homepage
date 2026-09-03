# Junteng Liu - Personal Website

Personal website for Junteng Liu (刘俊腾), first-year PhD candidate at HKUST NLP Group.

## About

This website is built using the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template based on Jekyll and Markdown.

## Quick Start - Enable GitHub Pages

After cloning or pushing these files to your repository:

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "GitHub Pages" section
4. Under "Source", select branch `master` (or main)
5. Click "Save"

Your site will be built automatically and available at:
`https://MiddleBarrister.github.io/LJT-Homepage`

## Manual Steps Required

**You must manually enable GitHub Pages** through the web interface. The Jekyll site will not be served until this step is completed.

### Step-by-step:

1. Navigate to: https://github.com/MiddleBarrister/LJT-Homepage/settings
2. In the left sidebar, scroll down to "Code and automation"
3. Click on "Pages"
4. Under "Build and deployment" > "Source", select `Deploy from a branch`
5. Under "Branch", select `master` and `/ (root)`
6. Click "Save"

Wait about 2-3 minutes for the site to build.

## Setup

The site is configured for GitHub Pages at:

```
https://MiddleBarrister.github.io/LJT-Homepage
```

### Adding a Profile Picture

The site requires a profile picture to display in the sidebar. To add one:

1. Prepare a square image (recommended size: 200x200 pixels or higher)
2. Name it `profile.png`
3. Upload it to the `images/` directory in the repository

### Local Development

To run the site locally for testing:

1. Install Ruby and Bundler
2. Clone the repository
3. Run `bundle install` to install dependencies
4. Run `bundle exec jekyll serve -l -H localhost` to start the local server
5. Visit `http://localhost:4000/LJT-Homepage`

## Configuration

The site configuration is in `_config.yml`. Key settings:

- **Name**: Junteng Liu
- **Title**: Junteng Liu - Personal Website
- **URL**: https://MiddleBarrister.github.io (domain only)
- **Base URL**: /LJT-Homepage (project path)
- **Description**: First-year PhD Candidate at HKUST NLP Group

## Pages

The site contains the following pages:

- [**Homepage** (`/`)](https://MiddleBarrister.github.io/LJT-Homepage/): Introduction, bio, research interests, news, and contact links
- [**About**](https://MiddleBarrister.github.io/LJT-Homepage/about/): Personal information, academic background, research experience, skills, awards, contact details, and complete publications list

## Content Structure

### Homepage (`index.md`)

The homepage features:
- Profile section with name and tagline
- Biography with research focus
- Research interests with descriptions
- Recent news/milestones
- Contact information links
- Link to the About page for more details

### About Page (`about.md`)

The about page contains all personal information:

**Personal Details:**
- Full name (Junteng Liu / 刘俊腾)
- Email: jliugi@connect.ust.hk
- GitHub: Vicent0205
- Google Scholar profile
- X (Twitter): @junteng88716710

**Academic Background:**
- Ph.D. in Computer Science (2024-Present) at Hong Kong University of Science and Technology (HKUST)
- B.Eng. in Computer Science and Technology (2020-2024) at Shanghai Jiao Tong University (SJTU)

**Research Interests:**
- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

**Research Experience:**
- Research Intern at MINIMAX (February 2025 - Present)
- Research Intern at Tencent WXG (June 2024 - September 2024), advised by Zifei Shan
- Research Intern at Shanghai AI Lab (June 2023 - December 2023), advised by Prof. Yu Cheng

**Publications (6 total):**

2025:
- SynLogic: Synthesizing Verifiable Reasoning Data at Scale for Learning Logical Reasoning and Beyond (First author)
- On the Perception Bottleneck of VLMs for Chart Understanding (First author)

2024:
- On the Universal Truthfulness Hyperplane Inside LLMs (First author, EMNLP 2024)
- In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation (Co-author, ICML 2024)

2023:
- C-Eval: A Multi-Level Multi-Discipline Chinese Evaluation Suite for Foundation Models (Co-author, NeurIPS 2023)
- Composing Parameter-Efficient Modules with Arithmetic Operations (Co-author, NeurIPS 2023)

**Skills:**
- Programming Languages: Python, C++, MATLAB
- Frameworks: PyTorch, TensorFlow, Hugging Face
- Languages: English (Fluent), Chinese (Native)

**Awards:**
- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University (2023-2024)

## Features

- Responsive design using the "default" theme
- Publication list with conference annotations and co-authors
- SEO optimization
- Social media integration (GitHub, X/Twitter, Google Scholar)
- Clean, academic-focused layout
- Author profile in left sidebar

## Required Files

For the site to display correctly:

1. **Profile Picture**: Add a profile image as `images/profile.png` (square image recommended)

## Contact

- **Email**: jliugi@connect.ust.hk
- **GitHub**: [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar**: [Scholar Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter)**: [@junteng88716710](https://twitter.com/junteng88716710)

## Research Interests

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

## Academic Background

- **Ph.D. in Computer Science** (2024 - Present) - Hong Kong University of Science and Technology (HKUST)
- **B.Eng. in Computer Science and Technology** (2020 - 2024) - Shanghai Jiao Tong University (SJTU)

## Research Experience

- Research Intern at MINIMAX (February 2025 - Present)
- Research Intern at Tencent WXG (June 2024 - September 2024)
- Research Intern at Shanghai AI Lab (June 2023 - December 2023)

## Memory Data Source

All information on this site is sourced from the memory graph, containing:
- Personal details (name, email, social media)
- Academic background (Ph.D. and B.Eng. programs)
- Research experience (3 internships with advisors)
- Publications (6 papers from 2023-2025 with full details)
- Skills and awards
- Contact information

## Repository Structure

```
LJT-Homepage/
├── _config.yml          # Site configuration
├── index.md             # Homepage
├── about.md             # About page with all info and publications
├── README.md            # Documentation
├── .nojekyll            # GitHub Pages Jekyll flag
├── images/              # Image assets (add profile.png)
├── _pages/              # Page templates (if needed)
├── files/               # File uploads
└── ...
```

## License

MIT License (from original template)
