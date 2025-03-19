# EcoSearch Landing Page 🌱  

A modern landing page for **EcoSearch** - the world's first **Green AI search engine** with waitlist functionality.  

## Features 🚀  

- **Waitlist System**: Automated position tracking and email notifications  
- **Modern UI**: Clean, responsive design with smooth animations  
- **Email Integration**: Using EmailJS for seamless email delivery  
- **Form Validation**: Real-time email validation with error handling  
- **Success Notifications**: Beautiful popup notifications for user feedback  

## Tech Stack 💻  

- **HTML5**  
- **CSS3** (Flexbox & Grid)  
- **Vanilla JavaScript**  
- **EmailJS**  

## Configuration ⚙️  

### EmailJS Setup  

```js
// Public Key  
emailjs.init("2ARbQ1pqcJ5UGFNc3");  
// Service ID  
const serviceId = "service_9qyqicm";  
// Template ID  
const templateId = "template_cidm9qm";
```

### Waitlist Configuration

```js
// Waitlist Base URL
const baseUrl = 'https://getwaitlist.com/waitlist/26454';
```

## Styling Guide 🎨

### Colors
```css
:root {
    --primary-color: #90B794;
    --text-color: #000;
    --background-color: #FDF8F7;
}
```

### Responsive Design 📱
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## Key Components 📦

### 1. Hero Section
- Main heading with Green AI emphasis
- Email signup form
- Join waitlist button

### 2. Features Grid
- **Climate Driven**: Environmental investment initiatives
- **Optimized Search**: Energy-efficient search results
- **Privacy First**: No data collection policy
- **Minimal Design**: Reduced carbon footprint UI

### 3. Notification System
- Success confirmations
- Error messages
- Position updates
- Email notifications

## How to Use 📝

1. **Setup**
   - Clone the repository
   - Configure EmailJS credentials
   - Open index.html

2. **User Flow**
   - Enter email address
   - Receive confirmation
   - Get waitlist position
   - Share referral link