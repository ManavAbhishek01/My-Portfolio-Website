# Manav Abhishek - Portfolio Website

A modern, responsive portfolio website showcasing skills, experience, and projects in Cyber Security, AI Development, and Web Development.

## 🎨 Features

- **Modern Design**: Blue and white color scheme with Tailwind CSS
- **Fully Responsive**: Mobile-first design that works on all devices
- **Smooth Animations**: Elegant transitions and hover effects
- **Profile Showcase**: Enlarged profile picture and comprehensive information
- **Project Portfolio**: Detailed showcase of AI, Web, and Mobile projects
- **Automated Deployment**: GitHub Actions workflow for Vercel deployment

## 🚀 Tech Stack

- **HTML5** - Structure
- **Tailwind CSS** - Styling (via CDN)
- **JavaScript** - Interactivity
- **Vercel** - Hosting & Deployment
- **GitHub Actions** - CI/CD

## 📋 Sections

1. **Hero Section** - Introduction with enlarged profile picture
2. **About** - Professional profile and background
3. **Education** - Academic qualifications
4. **Experience** - Work experience and internships
5. **Skills** - Technical and soft skills
6. **Projects** - Featured projects with technologies
7. **Languages** - Language proficiency
8. **Contact** - Contact information and social links

## 🛠️ Setup & Installation

### Local Development

1. Clone the repository:
```bash
git clone <your-repo-url>
cd "My Portfolio"
```

2. Install dependencies (optional, for local server):
```bash
npm install
```

3. Run local server:
```bash
npm run dev
```

4. Open in browser:
```
http://localhost:3000
```

## 📦 Deployment

### Vercel Deployment

This project is configured for automatic deployment to Vercel via GitHub Actions.

#### Setup Steps:

1. **Create Vercel Account**
   - Go to [vercel.com](https://vercel.com)
   - Sign up with your GitHub account

2. **Get Vercel Token**
   - Go to Vercel Dashboard → Settings → Tokens
   - Create a new token
   - Copy the token

3. **Add GitHub Secret**
   - Go to your GitHub repository
   - Navigate to Settings → Secrets and variables → Actions
   - Add a new secret named `VERCEL_TOKEN` with your Vercel token

4. **Push to GitHub**
   - Push your code to the `main` or `master` branch
   - GitHub Actions will automatically deploy to Vercel

#### Manual Vercel Deployment:

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

## 🎯 Customization

### Update Profile Picture

Replace the placeholder image in `index.html`:
```html
<img src="path/to/your/profile-picture.jpg" alt="Manav Abhishek" />
```

### Update Colors

Modify the Tailwind config in `index.html`:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                'primary-blue': '#1e40af',
                'secondary-blue': '#3b82f6',
                'card-blue': '#e0f2fe',
            }
        }
    }
}
```

### Add Projects

Edit the Projects section in `index.html` to add or modify project cards.

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔗 Links

- **Live Site**: [Your Vercel URL]
- **LinkedIn**: [https://www.linkedin.com/in/manav-abhishek-103794329](https://www.linkedin.com/in/manav-abhishek-103794329)
- **Email**: manavabhishek54@gmail.com

## 📄 License

MIT License - feel free to use this template for your own portfolio!

## 👤 Author

**Manav Abhishek**
- Email: manavabhishek54@gmail.com
- Phone: +91 8228854903
- Location: Patna, Bihar

---

Made with ❤️ using Tailwind CSS

