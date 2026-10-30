Finance Landing Page
A static landing page for a financial application, built with HTML and CSS. The design combines bold typography, layered smartphone mockups, warm gradient accents, and promotional sections to introduce the product.
Overview
This project demonstrates a finance-focused website layout with a clear visual hierarchy and an emphasis on product presentation. It is suitable for showcasing frontend layout and styling work in a portfolio.
Page Sections
Section	Description
Navigation	Brand image, Home, About Us, Pricing, Features, and a Download button.
Hero	“Make The Best Financial Decisions” headline, supporting copy, and a call-to-action graphic.
Product showcase	Layered smartphone images and decorative elements.
Features	Image-based presentation of product features.
Testimonials	Dedicated testimonial artwork.
FAQ	Frequently asked questions presented as an image.
Download banner	Promotional artwork encouraging visitors to get started.
Footer	Image-based footer content.


Technologies
- HTML5 for page structure.
- CSS3 for styling, gradients, transforms, positioning, and hover effects.
- Flexbox for navigation and hero alignment.
- Media queries for navigation adjustments at 768px and 480px.
No JavaScript, external framework, package installation, or build step is required.
Project Structure
Keep the following items in the repository root:
Path	Purpose
index.html	Main landing page markup.
style.css	Page styles and media queries.
assets/	Logo, phone mockups, decorative graphics, and section artwork.
README.md	Project documentation.


The supplied markup references these image files inside assets/:
Grouplogo.png
Star 1star.png
Group 5button.png
Group 35924headImg.png
Frame 1container.png
iPhone-13-Pro-Front2nd.png
iPhone-13-Pro-Frontfirst.png
Group 1000002336features.png
Group 1000002334testimonials.png
Group 1000002355frequentlly.png
FramegetReady.png
Group 1000002347footer.png
Preserve the filenames and capitalization so the image references resolve correctly.
Run Locally
1. Clone this repository or download and extract its ZIP file.
2. Save the HTML as index.html and the CSS as style.css if they are not already separate files.
3. Place the required images in the assets/ directory.
4. Open the project with a local static server, such as the Live Server extension in Visual Studio Code.
Alternatively, if Python 3 is installed, run this command from the project root:
python3 -m http.server 8000
Then open http://localhost:8000.
Implementation Notes
- This is a visual frontend prototype. Navigation links currently use #, the Download button has no assigned action, and the Get Started control is an image.
- Features, testimonials, FAQ, download banner, and footer content are largely embedded in images rather than editable HTML.
- The navigation includes responsive rules. Other sections use fixed offsets and absolute positioning, so the full page requires further work for consistent mobile and tablet layouts.
- The HTML mixes /assets/ and ./assets/ paths. For hosting under a repository subpath, use relative paths such as ./assets/Grouplogo.png consistently.
