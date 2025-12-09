# Educational-Website-Main

Educational-Website-Main is a responsive web application built with React that showcases a modern educational portal. The site highlights courses, company information, testimonials, and more. It is structured into modular and reusable components for clear organization and scalability.

## Features

- **Modern UI/UX:** Built using React and Bootstrap for a professional look.
- **Homepage Sections:**
  - Header and Footer for navigation and site info.
  - Hero Section for impressive landing visuals.
  - Company Section showcasing partner info or stats.
  - About Us for organizational background.
  - Courses and Free Course sections to display educational offerings.
  - Choose Us and Features emphasize unique selling points.
  - Testimonials boost trust for visitors.
  - Newsletter signup for user engagement.
- **Responsive Design:** Works across desktop, tablet, and mobile devices.
- **Carousel, Icons, and Animations:** Slick carousel for sliders, Remix icons for graphics.

## Technology Stack

- **Frontend:** [React](https://reactjs.org/)
- **UI Components:** [Bootstrap](https://getbootstrap.com/) and [Remix Icon](https://remixicon.com/)
- **Slider/Carousel:** [Slick Carousel](https://react-slick.neostack.com/)
- **CSS:** Custom (index.css), Bootstrap, Slick Carousel styles

## Getting Started

### Prerequisites

- Node.js (v12+ recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yogeshjvcsolutions/Educational-Website-Main.git
   cd Educational-Website-Main
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

To start the development server:

```bash
npm start
```
Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
src/
├── components/
│   ├── About-us/
│   ├── Choose-us/
│   ├── Company-section/
│   ├── Courses-section/
│   ├── Feature-section/
│   ├── Footer/
│   ├── Free-course-section/
│   ├── Header/
│   ├── Hero-Section/
│   ├── Newsletter/
│   ├── Testimonial/
├── pages/
│   └── Home.js        # Main homepage layout
├── App.js
├── index.js
├── index.css
```

- **components/**: Contains all UI and layout components.
- **pages/Home.js**: Assembles components to create the homepage.
- **App.js**: Root App component.
- **index.js**: Entry point; renders App inside React’s StrictMode.

## Customization

- To add or update Courses, modify the relevant courses component.
- Branding, text, and images can be customized in sections like AboutUs, HeroSection, Footer, etc.
- You can add more pages by creating new files inside the **pages/** directory and updating `App.js` and routing logic as needed.

## License

This project is [MIT Licensed](LICENSE).
