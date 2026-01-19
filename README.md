# CMPS 302 - Week 4: Introduction to CSS
## Alps Tourism Website with CSS Styling

A comprehensive tourism website about the Alps mountain range with professional CSS styling, demonstrating external stylesheets, color schemes, typography, layout techniques, and responsive design principles.

---

## Live Demo

**GitHub Pages:** https://DatariusAl.github.io/cmps302_week4_css_introduction/

---

## Repository Structure
```
cmps302_week4_css_introduction/
├── index.html                    # Home page with geography, ecology, and fauna
├── tourism.html                  # Tourism information, resorts, and winter sports
├── gallery.html                  # Photo gallery with responsive grid layout
├── multimedia.html               # Multimedia content page
│
├── css/
│   ├── style.css                # Main stylesheet with CSS specifications
│   └── gallery.css              # Gallery-specific grid layout styles
│
├── Pictures/                     # Images used within page content
│   ├── Alps.jpg                 # Header background image
│   ├── Map.jpg                  # Geographic map (float left)
│   ├── ibex.jpg                 # Alpine Ibex (float right)
│   ├── France.jpg               # French resort (float right)
│   ├── Switzerland.jpg          # Swiss resort (float right)
│   ├── Austria.jpg              # Austrian resort (float right)
│   └── Bavaria.jpg              # Bavarian resort (float right)
│
├── Gallery/                      # Images displayed in gallery.html
│   ├── AlpsMap.jpg              # Geographic map of Alps region
│   ├── Austria.jpg              # Austria landscape
│   ├── France.jpg               # French Alps scenery
│   ├── Germany.jpg              # German Alps region
│   ├── Italy.jpg                # Italian Alps landscape
│   ├── liechtenstein.jpg        # Liechtenstein scenery
│   ├── Monaco.jpg               # Monaco landscape
│   ├── Slovenia.jpg             # Slovenian Alps
│   └── Switzerland.jpg          # Swiss Alps
│
└── README.md                     # Project documentation (this file)
```

---

## Project Overview

**Assignment:** Week 4 - Introduction to CSS
**Objective:** Apply CSS styling to HTML pages created in Week 3, demonstrating proper use of external stylesheets, color schemes, typography, layout techniques including floats, and CSS-based formatting.

**Repository:** https://github.com/DatariusAl/cmps302_week4_css_introduction
**Live Demo:** https://DatariusAl.github.io/cmps302_week4_css_introduction/

---

## CSS Specifications Implementation

### Color Scheme

The website uses a professional purple-themed color palette:

| Color Swatch | Hex Code | Name | Usage |
|--------------|----------|------|-------|
| ![#D6DDE3](https://via.placeholder.com/20/D6DDE3/D6DDE3.png) | #D6DDE3 | Ice Blue | Body background, table background, navigation link color |
| ![#5E1740](https://via.placeholder.com/20/5E1740/5E1740.png) | #5E1740 | Plum (Dark Purple) | H2/H3 color, navigation background, borders |
| ![#A52486](https://via.placeholder.com/20/A52486/A52486.png) | #A52486 | Purple | H1 color, highlighted table cells |

### Typography

**Font Families:**
- Body text: Georgia, serif
- Headings (h1, h2, h3): Andalus, sans-serif

**Font Sizing:**
- h1: 34pt
- Body: Default with 150% line-height (1.5 line spacing)

**Font Colors:**
- h1: Purple (#A52486)
- h2, h3: Plum (#5E1740)
- Navigation links: Ice Blue (#D6DDE3)

### Layout Techniques

**1. DIV Structure:**
- `#header` - Contains h1 with Alps.jpg as background image
- `#main` - Wraps main content, max-width 1100px, centered
- `#footer` - Centered text with small font size

**2. Navigation:**
- Width: 60% of viewport
- Centered using margin: auto
- Background: Plum (#5E1740)
- Links: Bold, Ice Blue, no underline

**3. Floating Elements:**
- Map image: float left with right margin
- Ibex figure: float right with left margin
- Resort images (4): all float right

**4. Borders and Padding:**
- h2: Left border (5px) and bottom border (3px) in Plum color
- h2: Padding 10px with 20px left padding
- h2: Fixed width of 280px

**5. Text Alignment:**
- Paragraphs: Justified
- Figure captions: Centered
- Footer: Centered

### Table Styling

**Border Specifications:**
- Table outer border: 4px solid Plum (#5E1740)
- Cell borders (th, td): 2px solid Plum (#5E1740)
- Border-collapse: collapse

**Cell Formatting:**
- Header (th): Plum background, white text
- Table background: Ice Blue (#D6DDE3)

**Highlighted Cells:**
- "Mont Blanc - 4810 m"
- "Monte Rosa - 4634 m"
- Style: Bold, italic, Purple color (#A52486)

### List Styling

**Data Description List (dl):**
- dt elements: Bold and underlined

**Ordered List:**
- Top-level items: Bold
- Nested unordered list items: Normal weight

**Unordered List:**
- Standard bullet points
- 8px bottom margin per item

---

## Page Descriptions

### 1. index.html - Home Page

**Sections:**
- Alpine Countries (8 countries with data description list)
- Geography (with floating map image)
- Ecology
  - Flora (plant species information)
  - Fauna (with floating Ibex image)
- Four-Thousanders (styled table with 11 major peaks)

**CSS Features:**
- Background image in header
- Floating images (map left, ibex right)
- Styled table with highlighted cells
- Bold/underlined data terms

### 2. tourism.html - Tourism Page

**Sections:**
- Tourism History
- Popular Resorts (with 4 floating images)
- Top 4 Destinations (bold ordered list with nested details)
- Winter Sports (ordered list with Roman numerals)
- Mountain Passes (unordered list)

**CSS Features:**
- 4 floating resort images (all float right)
- Bold ordered list items
- Centered figure captions
- H3 underlined styling

### 3. gallery.html - Photo Gallery

**Content:**
- 9 country/region images in responsive grid
- CSS Grid layout (auto-fit)
- Hover effects with transform and shadow

**CSS Features:**
- 3-column grid (desktop)
- 2-column grid (tablet)
- 1-column grid (mobile)
- Purple-themed borders and captions

### 4. multimedia.html - Multimedia Page

**Content:**
- Placeholder sections for future content
- Featured Videos
- Interactive Maps
- Virtual Tours

**CSS Features:**
- Consistent styling with other pages
- H2 and H3 formatting
- Standard layout structure

---

## CSS File Breakdown

### style.css - Main Stylesheet

**Sections:**
1. Base Styles (body, fonts, line-height)
2. Header Styling (#header with background image)
3. Typography (h1, h2, h3 with specific colors and borders)
4. Navigation (centered, 60% width, Ice Blue links)
5. Main Content (#main wrapper)
6. Paragraph Styling (justified text)
7. List Styling (dl, ol, ul with specifications)
8. Table Styling (borders, highlighted cells)
9. Float Classes (floatLeft, floatRight)
10. Figure/Figcaption (centered captions)
11. Footer Styling (centered, small text)

### gallery.css - Gallery Stylesheet

**Sections:**
1. Grid Layout (CSS Grid with auto-fit)
2. Gallery Item Cards (borders, shadows, hover effects)
3. Image Sizing (fixed height with object-fit)
4. Caption Styling (purple theme)
5. Responsive Media Queries (3/2/1 column layout)

---

## Development Methodology

### Step 1: HTML Structure Enhancement
- Added three DIV wrappers to each page:
  - `<div id="header">` - Wraps h1
  - `<div id="main">` - Wraps main content
  - `<div id="footer">` - Wraps footer elements
- Added class attributes for styling:
  - `.floatLeft` for map image
  - `.floatRight` for ibex and resort images
  - `.highlight` for specific table cells

### Step 2: CSS File Creation
- Created `css/style.css` with all specifications
- Implemented color scheme (#D6DDE3, #5E1740, #A52486)
- Applied Georgia and Andalus fonts
- Set 150% line-height for body

### Step 3: Header Styling
- Used `background-image` property for Alps.jpg
- Implemented `background-size: cover` for full coverage
- Used flexbox for h1 centering
- Applied 34pt font size and Purple color to h1

### Step 4: Navigation Styling
- Reduced nav width to 60%
- Centered using `margin: auto`
- Applied Plum background color
- Styled links: Ice Blue, bold, no underline

### Step 5: Typography Implementation
- Applied Andalus font to h1, h2, h3
- Added borders and padding to h2 (left 5px, bottom 3px)
- Set h2 width to 280px
- Applied underline to h3

### Step 6: Layout Techniques
- Implemented float left for map image
- Implemented float right for ibex and resort images
- Set paragraph text-align to justify
- Centered figure captions

### Step 7: Table Styling
- Applied 4px solid Plum border to table
- Applied 2px solid Plum borders to cells
- Styled header row with Plum background
- Added `.highlight` class for Mont Blanc and Monte Rosa cells
- Styled highlighted cells: bold, italic, Purple color

### Step 8: List Formatting
- Made dt elements bold and underlined
- Made ordered list items bold
- Kept nested list items normal weight

### Step 9: Footer Styling
- Centered text alignment
- Applied small font size
- Styled links with Plum color

### Step 10: Gallery Enhancement
- Created separate `gallery.css` file
- Implemented CSS Grid layout
- Added responsive breakpoints
- Applied purple-themed styling

### Step 11: Testing and Validation
- Tested all float behaviors
- Verified color accuracy
- Checked font rendering
- Validated responsive behavior
- Tested navigation functionality

---

## CSS Techniques Demonstrated

### 1. External Stylesheets
- Proper linking with `<link rel="stylesheet" href="css/style.css">`
- Separation of content (HTML) and presentation (CSS)
- Reusable styles across multiple pages

### 2. ID Selectors
- `#header` - Unique header styling
- `#main` - Main content container
- `#footer` - Footer area styling

### 3. Class Selectors
- `.floatLeft` - Left-floating images
- `.floatRight` - Right-floating images
- `.highlight` - Special table cells
- `.gallery-grid` - Grid container
- `.gallery-item` - Individual gallery cards

### 4. Element Selectors
- Typography: h1, h2, h3, p
- Lists: dl, dt, dd, ol, ul, li
- Tables: table, th, td
- Figures: figure, figcaption

### 5. Descendant Selectors
- `nav a` - Links within navigation
- `ol > li` - Direct children of ordered list
- `ol > li ul li` - Nested list items
- `#footer a` - Links in footer

### 6. Background Properties
- `background-image` - Alps.jpg in header
- `background-size: cover` - Full coverage
- `background-position: center` - Centered image

### 7. Border Properties
- Solid borders with specific widths
- Border colors matching theme
- `border-collapse` for tables
- Selective borders (left, bottom for h2)

### 8. Float and Clear
- `float: left` for map
- `float: right` for ibex and resorts
- Proper margin spacing around floats

### 9. Text Formatting
- `text-align: justify` for paragraphs
- `text-align: center` for captions and footer
- `text-decoration: underline` for h3 and dt
- `text-decoration: none` for navigation links

### 10. Box Model
- Padding for spacing inside elements
- Margins for spacing between elements
- Width constraints (h2: 280px, nav: 60%, main: 1100px max)

### 11. CSS Grid Layout
- `display: grid` for gallery
- `grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))`
- `gap` for spacing between items

### 12. Hover Effects
- Navigation link background change
- Gallery item transform and shadow
- Footer link underline

### 13. Responsive Design
- Media queries for different screen sizes
- Flexible grid columns (3/2/1)
- Percentage-based widths

---

## Assignment Requirements Met

### HTML Structure
- Added DIV with id="header" wrapping h1
- Added DIV with id="main" wrapping main content
- Added DIV with id="footer" wrapping footer elements
- Added class/id assignments for styling
- No inline styles used

### Color Implementation
- Ice Blue (#D6DDE3): Body background, navigation links, table background
- Plum (#5E1740): H2/H3, navigation background, borders, footer links
- Purple (#A52486): H1, highlighted table cells, navigation hover

### Font Specifications
- Georgia font for body text
- Andalus font for h1, h2, h3
- H1 font size: 34pt
- H1 color: Purple
- H2/H3 color: Plum

### Line Spacing
- Body line-height: 150% (1.5 line)

### Header DIV
- Alps.jpg as background image
- Proper background-size and position
- Contains centered h1

### H2 Elements
- Left border: 5px solid Plum
- Bottom border: 3px solid Plum
- Padding: 10px with 20px left
- Width: 280px

### H3 Elements
- Text-decoration: underline

### Navigation
- Centered within body
- Width: 60% of viewport
- Margin left and right: auto
- Links: Bold, Ice Blue, no underline

### Paragraphs
- Text-align: justify

### Data Terms (dt)
- Font-weight: bold
- Text-decoration: underline

### Ordered List Items
- Font-weight: bold

### Footer
- Text-align: center
- Font-size: small

### Table Styling
- Cell borders: 2px solid Plum (#5E1740)
- Table outer border: 4px solid Plum
- Border-collapse: collapse
- Mont Blanc and Monte Rosa cells: Bold, italic, Purple

### Floating Images
- Map: float left
- Ibex: float right
- Resort images (4): all float right

### Figure Captions
- Text-align: center

---

## Learning Outcomes

Through this project, I gained practical experience in:

**CSS Fundamentals:**
- External stylesheet creation and linking
- CSS selectors (element, class, ID, descendant)
- Color implementation with hex codes
- Font family and sizing properties

**Layout Techniques:**
- Float-based layouts
- DIV-based page structure
- Width and margin centering
- Box model (padding, borders, margins)

**Typography:**
- Font family specifications
- Font sizing and colors
- Text decoration and alignment
- Line-height for readability

**Visual Design:**
- Color scheme implementation
- Border styling and positioning
- Background image techniques
- Hover effects for interactivity

**Table Formatting:**
- Border collapse and styling
- Cell padding and alignment
- Row and column styling
- Selective cell highlighting

**Responsive Techniques:**
- CSS Grid for gallery layout
- Media queries for breakpoints
- Flexible width percentages
- Auto-fit grid columns

**Best Practices:**
- Separation of content and presentation
- Reusable CSS classes
- Consistent naming conventions
- Code organization and comments

---

## Comparison: Week 3 vs Week 4

### Week 3 (HTML Only)
- Plain HTML structure
- No visual styling
- Default browser fonts and colors
- No layout control
- Simple table appearance
- Basic navigation links

### Week 4 (HTML + CSS)
- Professional visual design
- Custom color scheme (Purple theme)
- Specific typography (Georgia and Andalus)
- Controlled layout with floats and positioning
- Styled table with borders and highlighted cells
- Styled navigation with centered bar

**Key Improvements:**
- Visual hierarchy with color and typography
- Professional appearance matching design specifications
- Improved readability with justified text and line-spacing
- Enhanced user experience with hover effects
- Consistent styling across all pages
- Responsive gallery with CSS Grid

---

## Technical Highlights

### 1. Header Background Image
```css
#header {
    background-image: url('../Pictures/Alps.jpg');
    background-size: cover;
    background-position: center;
    height: 200px;
}
```

### 2. Centered Navigation
```css
nav {
    width: 60%;
    margin-left: auto;
    margin-right: auto;
    background-color: #5E1740;
}
```

### 3. H2 Custom Borders
```css
h2 {
    border-left: 5px solid #5E1740;
    border-bottom: 3px solid #5E1740;
    padding: 10px;
    padding-left: 20px;
    width: 280px;
}
```

### 4. Table Cell Highlighting
```css
td.highlight {
    font-weight: bold;
    font-style: italic;
    color: #A52486;
}
```

### 5. Float Positioning
```css
.floatLeft {
    float: left;
    margin-right: 20px;
}

.floatRight {
    float: right;
    margin-left: 15px;
}
```

### 6. Responsive Gallery Grid
```css
.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}
```

---

## Browser Compatibility

**Tested and verified on:**
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Microsoft Edge (latest)
- Safari (latest)

**CSS Features Used:**
- CSS3 Grid Layout
- Background properties
- Border properties
- Float and clear
- Hover pseudo-class
- Media queries

---

## Future Enhancements

Potential improvements for future iterations:
- Add CSS transitions for smooth animations
- Implement CSS Flexbox for alternative layouts
- Add print stylesheet for printer-friendly pages
- Enhance accessibility with ARIA labels
- Add dark mode theme option
- Implement CSS variables for easier theme management
- Add mobile-first responsive design
- Enhance gallery with lightbox functionality

---

## Resources and References

**Content Source:**
- Wikipedia: https://en.wikipedia.org/wiki/Alps

**CSS Documentation:**
- MDN Web Docs: https://developer.mozilla.org/en-US/docs/Web/CSS
- W3Schools CSS Tutorial: https://www.w3schools.com/css/

**Color Tools:**
- Hex Color Codes: https://www.color-hex.com/

**Font References:**
- Georgia: System font
- Andalus: System font

---

## Getting Started

### View Online
Visit the live site: https://DatariusAl.github.io/cmps302_week4_css_introduction/

### Run Locally

1. Clone the repository:
```bash
   git clone https://github.com/DatariusAl/cmps302_week4_css_introduction.git
```

2. Navigate to the project directory:
```bash
   cd cmps302_week4_css_introduction
```

3. Open index.html in your browser or simply double-click index.html in your file explorer.

### File Requirements
- All HTML files must be in root directory
- CSS files must be in `css/` folder (lowercase)
- Content images in `Pictures/` folder
- Gallery images in `Gallery/` folder

---

## Project Submission

**Deliverables:**
1. Four HTML files (index, tourism, gallery, multimedia)
2. Two CSS files (style.css, gallery.css)
3. Pictures folder with 7 images
4. Gallery folder with 9 images
5. README.md documentation
6. Live GitHub Pages deployment

**Submission Format:**
- ZIP file: `YourUserName_Week4_CSS.zip`
- GitHub repository link
- Live demo URL

---

## Course Information

- **Course:** CMPS 302 - Web Development
- **Assignment:** Week 4 - Introduction to CSS
- **Student:** DatariusAl
- **Institution:** American University of Beirut (AUB)
- **Focus:** External CSS, layout techniques, typography, color schemes

---

## Author

**DatariusAl**
- GitHub: https://github.com/DatariusAl
- Repository: https://github.com/DatariusAl/cmps302_week4_css_introduction

---

## License

This project is created for educational purposes as part of CMPS 302 coursework at the American University of Beirut.

---

## Acknowledgments

- Course instructor for CSS specifications and guidelines
- Wikipedia for Alps content and information
- AUB CMPS 302 course materials and resources

---

**Last Updated:** January 2026

**Assignment Status:** Complete - All CSS specifications implemented and tested
