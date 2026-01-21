### AgungDevX Profile Website

A minimalist and professional portfolio website built with modern web technologies. Features a clean, responsive design with dark/light mode support.

### Features

- **Minimalist Design**: Clean interface with outlined card components  
- **Dark/Light Mode**: Automatic theme detection with manual override  
- **Responsive Layout**: Fully responsive across all device sizes  
- **GitHub Integration**: Real-time GitHub stats via API  
- **Interactive Elements**: Smooth animations and hover effects  
- **Guestbook**: Integrated chat/guestbook functionality  
- **Spotify Integration**: Embedded music playlist player

### Technologies Used

- **HTML5** - Semantic markup  
- **Tailwind CSS** - Utility-first CSS framework  
- **JavaScript (Vanilla)** - No external dependencies  
- **GitHub API** - Dynamic user and repository data  
- **Inter Font** - Modern typography

### Project Structure

```
/
├── index.html              # Main HTML file
├── README.md              # This documentation
└── (assets loaded via CDN)
```


### Key Sections

1. **Profile Header** - Personal information and social links  
2. **Quick Links** - Important external resources  
3. **Spotify Player** - Embedded music playlist  
4. **Guestbook** - Interactive chat/comment section  
5. **GitHub Stats** - Dynamic repository and user statistics  
6. **Footer** - Copyright and credits

### Setup & Deployment

This is a static website that can be deployed anywhere:

##### Option 1: GitHub Pages
1. Fork this repository  
2. Go to repository Settings → Pages  
3. Select branch and save

##### Option 2: Netlify/Vercel
- Drag and drop the folder or connect your Git repository  
- No build process needed

##### Option 3: Traditional Hosting
- Upload all files to any web server  
- Ensure proper MIME types

### Configuration

##### Customization Points:

1. **Profile Information** - Update in HTML meta tags and profile section  
2. **Social Links** - Modify URLs in the social links section  
3. **GitHub Integration** - Update username in JavaScript API calls  
4. **Colors & Themes** - Modify Tailwind config in `<script>` tag  
5. **Analytics** - Replace Google Analytics tracking ID

##### API Integrations:

- **GitHub API**: Fetches user stats and repository information  
- **Spotify API**: Embeds playlist player  
- **Cbox API**: Powers guestbook functionality

### Browser Support

- Chrome 60+  
- Firefox 55+  
- Safari 12+  
- Edge 79+

### Performance

- **Loading**: ~800ms simulated loading screen  
- **Assets**: All loaded via CDN with preconnect hints  
- **Images**: Lazy loading with fallback SVG  
- **JavaScript**: Minified inline scripts

### SEO Features

- Semantic HTML5 markup  
- JSON-LD structured data  
- Open Graph and Twitter Card meta tags  
- Canonical URL support  
- Mobile-friendly viewport settings

### License

© 2025 AgungDevX. All rights reserved.

### Contact

- Website: [agungdevx.my.id](https://agungdevx.my.id)  
- GitHub: [@agungdevx](https://github.com/agungdevx)  
- Email: contact@agungdevx.my.id

---

Built with simplicity and performance in mind.
