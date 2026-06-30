# Image Slider (Swiper.js)

A modern, responsive image slider built using **HTML**, **CSS**, and **Swiper.js**.  
It features autoplay, smooth fade transitions, navigation arrows, and pagination.

## Features

- Responsive image slider
- Autoplay slideshow
- Smooth fade transition effect
- Clickable pagination dots
- Navigation arrows (prev/next)
- Infinite loop support

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Swiper.js (CDN)

---

## Project Structure

```

## Swiper Configuration

The slider uses the following Swiper setup:

```javascript
const swiper = new Swiper(".swiper", {
  loop: true,

  effect: "fade",
  fadeEffect: {
    crossFade: true,
  },

  autoplay: {
    delay: 3000,
    disableOnInteraction: false,
  },

  pagination: {
    el: ".swiper-pagination",
    clickable: true,
  },

  navigation: {
    nextEl: ".swiper-button-next",
    prevEl: ".swiper-button-prev",
  },
});
```

## How It Works

### Fade Effect
- Slides do not move left or right
- Instead, images smoothly fade in and out

### Cross Fade
- Both images overlap during transition
- Creates a smooth cinematic effect

### Autoplay
- Slides change every 3 seconds automatically
- Continues even after user interaction

## Getting Started

1. Clone the repository

```bash
git clone https://github.com/your-username/image-slider.git
```

2. Open the project folder

```bash
cd image-slider
```

3. Open `index.html` in your browser

No build tools required.

## Future Improvements

- Pause on hover
- Keyboard navigation
- Mobile swipe optimization
- Captions for images
- Lazy loading images

## License

This project is open-source and free to use.
