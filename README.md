<img width="1943" height="1093" alt="image" src="https://github.com/user-attachments/assets/cc2ff955-17c2-48c7-81c8-479a0f061850" />

# DevPortfolio Template

A modern, minimalist portfolio template built with Astro and Tailwind CSS. Perfect for developers looking to showcase their skills, experience, and projects in a clean, professional way.

This was completely rebuilt from the ground up from V1. This template was built to be entirely ready to go with a quick config edit (see below) but also provides the ability to easily extend in whatever way you want.

This template also comes with `CLAUDE.md` and `.cursor/rules` files for easy integration with your existing AI workflows.

> **📬 Connect & Share!**  
> For questions and updates, feel free to reach out on [**X (Twitter)**](https://x.com/rfitzio).  
> If you've built and published your personal site with this template, I'd love to see it! Send me a DM 🚀

## Preview

To view a live preview of the site, [click here](https://ryanfitzgerald.github.io/devportfolio/).

## Built With

- **[Astro](https://astro.build/)** - Static site generator for modern web apps
- **[Tailwind CSS v4](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Tabler Icons](https://tabler.io/icons)** - Free and open source icons
- **TypeScript** - For type-safe configuration

## Updating the Template

### Configuration

The template is designed to be easily customizable through the `src/config.ts` file. This single file controls:

- **Personal Information**: Name, title, description
- **Accent Color**: Primary color theme (changing this will change the accent color site wide)
- **Social Links**: Email, LinkedIn, Twitter, GitHub (all optional)
- **About Section**: Personal bio/description
- **Skills**: List of technical skills
- **Projects**: Project showcase with descriptions and links
- **Experience**: Work history with bullet points
- **Education**: Educational background and achievements

If skills, projects, experience, or education are removed from the config, those sections will be hidden entirely.

### Example structures

Here's what the config data structure looks like for each section:

#### Basic Information
```typescript
name: "AIRA JOY M.MACALOOD",
description: "4th Year Computer Engineering Student",
accentColor: "#1d4ed8", // Hex color for theme
```

#### Social Links (all optional)
```typescript
social: {
  email: "macalood.airajoy@marsu.edu.ph",
  linkedin: "https://linkedin.com/in/ryxxx",
  twitter: "https://twitter.com/ryxxx", 
  github: "https://github.com/ryxxx2004",
}
```

#### About Section
```typescript
aboutMe: "As a 4th year Computer Engineering student at Marinduque State University, I have developed a strong curiosity for how technology can be applied to improve everyday life. My academic journey has given me opportunities to explore both hardware and software, allowing me to work on projects that involve automation, embedded systems, and applied research. I enjoy turning ideas into working solutions and learning new methods to improve them.
What motivates me most is the challenge of problem-solving. Whether through designing circuits, writing code, or testing systems, I approach tasks with persistence and creativity. I also value collaboration, as working with others helps me gain new perspectives and produce better results. Beyond academics, I continue to explore technology through self-study and side projects, building a mindset that is adaptable and forward-looking."
```

#### Skills
```typescript technical
skills: ["Arduino", "Rasberry PI", "Microcontrollers", "Python", "C++", "C", "HTML", "CSS", "JavaScript"]
```typescript Software skills: ["Adaptability in fast-paced environments, Critical Thinking, Problem-Solving, Team Collaboration, Project Coordination, and Time Management.    "], // Technologies used

#### Education
```typescript
education: [
  {
    name: "Education",
    description: "Senior High School
Marinduque National High School (2020 – 2022)
With Honors",
    "Junior High School
Marinduque National High School (2018 – 2020)
With Honors", "Primary Education
Bantay Elementary School (2013 – 2016)
With Honors"
  }
]
```

#### Achievements & Certifications
```typescript
achievements & certification: 
  {
    10 Hours BOHS Training Course for SO1 (April 2025)
  }
```
#### Seminars & Trainings
```typescript
Seminars & Trainings: 
  {
    "Toxic Productivity: When Working Hard Becomes Harmful (April, 2025)",
"Fundamentals of Image processing using Open CV and Matlab (2023)"
  }
```


### Icons

The template uses [Tabler Icons](https://tabler.io/icons) for all icons. If you wish to add more icons and have it look consistent with what's already there, you can browse through their extensive icon library.

## Project Structure

```
devportfolio/
├── public/
│   └── favicon.svg          # Site favicon
├── src/
│   ├── components/          # Astro components
│   │   ├── About.astro      # About section
│   │   ├── Education.astro  # Education section
│   │   ├── Experience.astro # Work experience section
│   │   ├── Footer.astro     # Site footer
│   │   ├── Header.astro     # Navigation header
│   │   ├── Hero.astro       # Hero/intro section
│   │   └── Projects.astro   # Projects showcase
│   ├── pages/
│   │   └── index.astro      # Main page layout
│   ├── styles/
│   │   └── global.css       # Global styles
│   └── config.ts            # Site configuration
├── astro.config.mjs         # Astro configuration
├── package.json             # Project dependencies
├── tailwind.config.js       # Tailwind configuration
└── tsconfig.json            # TypeScript configuration
```

## Local Development

If you'd like to run it locally:

```
git clone https://github.com/RyanFitzgerald/devportfolio.git
cd devportfolio
npm install
```

After that, start up the Astro dev server with:

```
npm run dev
```

## Deployment

The template can be deployed to any static hosting service easily (and in most cases, completely free). Here are some options:

- To deploy with Netlify, [click here](https://docs.astro.build/en/guides/deploy/netlify/).
- To deploy with Vercel, [click here](https://docs.astro.build/en/guides/deploy/vercel/).
- To deploy with GitHub Pages, [click here](https://docs.astro.build/en/guides/deploy/github/).
- To deploy with Cloudflare Pages, [click here](https://docs.astro.build/en/guides/deploy/cloudflare/).
- To deploy with Render, [click here](https://docs.astro.build/en/guides/deploy/render/).

Want to deploy somewhere else? Find more guides [here](https://docs.astro.build/en/guides/deploy/).

## Changelog

To view the changelog, see CHANGELOG.md.

## License

This project is fully and completely MIT. See LICENSE.md.

## Questions?

Feel free to reach out on [X (Twitter)](https://x.com/rfitzio) if you have any questions or need help.
