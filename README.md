# Smart Cart

Smart Cart is a static frontend prototype for a smart shopping cart application. The project is built using HTML, CSS, and JavaScript, and it presents a mobile-style shopping experience with login, signup, QR scanning, order summary, and bottom navigation screens.

The application starts with a login and signup page where users can enter their email and password. The form includes simple email validation and allows users to switch between login and signup tabs. After login or signup, the user is redirected to the main scanner page.

The scanner page displays a QR code interface, which represents the smart cart scanning feature. It is designed like a mobile app screen and includes a bottom navigation bar with options such as You, Discover, Scan, Orders, and More.

The Orders page shows a sample list of products added to the cart, including items such as Chocolate, Apple, Lays, Coca-Cola, Grapes, and Containers. Each item is displayed with an image and price, and the page also shows the total amount for the order.

The project uses local image assets stored in the `Images` folder, including product images, logo, QR code, and header graphics. The pages inside the `Next_Page` folder handle the main app screens such as scan, orders, discover, profile, and more.

The main files in this project are `index.html` for login and signup, `Next_Page/next-page.html` for the scanner page, `Next_Page/orders.html` for the order summary page, and other navigation pages such as `you.html`, `discover.html`, and `more.html`.

To run this project, open `index.html` in a browser. Since this is a static frontend project, no backend server or database is required. The project can also be hosted easily using GitHub Pages, Netlify, or any static hosting platform.

This project can be improved further by adding real authentication, QR code scanning using the device camera, dynamic cart item management, payment integration, user profile details, product database support, and backend connectivity.

Developed by Mithun Ravi.
