# APO - Appointments Only | Matrix Terminal Interface

A responsive mobile-first website layout for a private "Appointments Only" menu interface with a full retro-futuristic matrix-style aesthetic, inspired by CRT terminals and PlayStation 2 debug UIs.

## Implementation Summary

### Core Features Completed

#### 🎨 Visual Style Implementation
- **Background**: Deep black (`#000000`) with optional terminal green (`#001100`) theme toggle
- **Animated Scanlines**: CSS keyframe animation creating horizontal scanlines across the entire viewport
- **Typography**: Neon green glowing text (`#00FF99`, `#00FF00`) with "Share Tech Mono" font
- **Grid Overlay**: Subtle matrix-style grid pattern across the background
- **Corner Brackets**: Interface-style corner decorations on key sections

#### 📱 Mobile UX Features
- **Sticky Header**: Logo with pulsing glow animation that stays at top
- **Accordion Sections**: Expandable menu categories (Cannabis, Edibles, Concentrates)
- **Terminal Animations**: Text typing effects and blinking cursor
- **Theme Toggle**: Switch between pure black and terminal green backgrounds
- **Responsive Design**: Mobile-first approach, adapts to all screen sizes

#### 💻 Technical Implementation
- **HTML5 + Tailwind CSS**: Modern responsive framework
- **CSS Keyframes**: Custom animations for scanlines, glow effects, typing, and flicker
- **Interactive JavaScript**: Accordion functionality, sound effects, system simulation
- **Performance Optimized**: No external font dependencies beyond Google Fonts

#### 📋 Website Sections
- **Header**: "APO | APPOINTMENTS ONLY" with glowing animation
- **System Notice**: Terminal-style status messages with typing effect
- **Menu Categories**: Collapsible sections for different product types
- **Deals Section**: Highlighted special offers with flicker animation
- **Footer**: Faux debug information with system logs and uptime

#### 🧪 Bonus Features Implemented
- **Blinking Terminal Cursor**: Animated cursor near command prompt
- **System Logs**: Simulated terminal messages in footer
- **Sound Effects Toggle**: UI blip feedback for interactions
- **Dynamic System Info**: Real-time uptime counter and access time
- **Hover Effects**: Glowing interactions on all interactive elements

## File Structure

```
APO'/
├── index.html          # Main application file
├── package.json        # Node.js project configuration
├── vercel.json         # Vercel deployment configuration
├── .gitignore          # Git ignore rules
└── README.md          # This documentation
```

## Live Deployment

🚀 **Live Site**: https://apo-appointments-only-ietwhk7rg.vercel.app

The website is now deployed and accessible online via Vercel's global CDN.

## How to Use

### Online Access
1. **Visit Live Site**: https://apo-appointments-only-ietwhk7rg.vercel.app
2. **Mobile Optimized**: Best experience on mobile devices but fully responsive

### Local Development
1. **Open Locally**: Open `index.html` in any modern web browser
2. **Run Dev Server**: `npm run dev` (requires `npm install` first)

### Navigation
3. **Browse Menu**: Click on menu categories to expand product listings
4. **Sound Effects**: Toggle "SFX" button to enable/disable UI sounds
5. **Theme Switch**: Use "THEME" button to switch between pure black and terminal green

## Deployment Information

- **Platform**: Vercel
- **Domain**: https://apo-appointments-only-ietwhk7rg.vercel.app
- **Auto-Deploy**: Connected to Git repository for automatic deployments
- **Global CDN**: Fast loading worldwide via Vercel's edge network

## Technical Details

### Animations
- **Scanlines**: Continuous vertical movement creating CRT effect
- **Glow Pulse**: Breathing effect on main logo
- **Typing Effect**: Terminal-style text reveal
- **Flicker**: Subtle effect on special deals section

### Color Scheme
- Primary: `#00FF99` (Matrix Green)
- Secondary: `#00FF00` (Bright Green)
- Background: `#000000` (Black) / `#001100` (Terminal Green)
- Accent: `rgba(0, 255, 153, 0.1)` (Transparent Green)

### Responsive Breakpoints
- Mobile: < 768px (default design)
- Tablet: 768px - 1024px
- Desktop: > 1024px

## Browser Compatibility

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Performance Notes

- Lightweight CSS animations
- Minimal JavaScript for interactions
- Google Fonts loaded asynchronously
- Optimized for mobile networks

---

**Status**: ✅ Complete - All requirements implemented
**Last Updated**: March 2024
**Version**: 1.0.0
