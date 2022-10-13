# Cart-App  [![Template Project](https://img.shields.io/badge/Web-App-red)](http://www.gnu.org/licenses/agpl-3.0) [![Template Project](https://img.shields.io/badge/Technologies%20-HTML%2FCSS%2FJS-brightgreen)](http://www.gnu.org/licenses/agpl-3.0)

This is basically a ecommerce web app in which we can select the quatity of items send it to our cart and many more !! Totally made in html, css, js. Made the folder structure kind of similar to the a react or angular project. Also for the prodcuts i have used an api. and we can filter through the products

## 🛠 Technologies Used
  - HTML - Hyper Text Markup Language
  - CSS - Cascadeing Spread Sheet
  - JS - Java Script
  - DOM - Document Object Model
  
## 📂 File Structure
This is made in vanialla JS so the file structure is not too complex basically have 3 folders namely
- 👩‍💻 src - Contains all project src code (dynamic Content)
    - 🛒 Cart - Contains js files related to cart
        - addToCartDOM.js - Logic to add products to the cart
        - setUpCart.js - Intialize Cart or display products
        - toggleCart.js - File contains logic for the hamburger kind of menu
    - 🔍 Filters - Contains all the logic for filter (price low to high), (high to low), (search) etc.
        - Companies.js - contains logic for setting up the product companies
        - price.js - Contains Logic for filtering via price
        - search.js - Contains Logic for filtering the via search
    - 📃 Pages - Fetches dynamic content from api and puts in `product.html` and `products.html`
        - Product.js - Fetches dynamic content from API and places it in `product.html`
        - Products.js - Fetches dynamic content from API and place it in the `products.html`
    - 👉 displayProducts.js - Displays content in the home Page
    - 🐶 fetchProducts.js - Fetches data from API
    - 🏪 Store.js - Setups the store and ataches all the filters
    - 🔧 Utils.js - Contains all utility Functions
    - 🍔 toggleSidebar.js - Toggles the slideBar
- 🎨 styles.css - containing all styling stuff
- 👉 👈 about.html - containing html content for about page
- 🤵 app.js - Attaches all the js files
- 📔 product.html - Contains html for product page
- 📚 products.html - contains html for products page
- 🏡 index.html - Contains html for home page

## 🚩 Demo In Laptop Screen

https://user-images.githubusercontent.com/108281031/195496889-301d3447-e93c-4c36-a1d7-0b495a182d07.mp4

## 🏃‍♂️ Run Locally

📽 Clone the project

```bash
  git clone https://github.com/Srinivasan-Akash/Cart-App.git
```

Go to the project directory 📁

```bash
  cd Cart-App
```
## ✍️ Author and 📞 Contact
- [Akash Srinivasan](https://www.github.com/octokatherine)
    - [Coder Community](https://web.codercommunity.io/user/62d568cb998d86c8883a2766?tab=posts)
    - [![facebook](https://img.shields.io/badge/Facebook-0A66C2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/profile.php?id=100083429257499)
    - [![instagram](https://img.shields.io/badge/Instagram-0A66C2?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/akash_prashanthi/)
    - [![youtube](https://img.shields.io/badge/YouTube-ff0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCAv1QdzDgV6MjA60CRtfkIg)

## 📝 Features

- Beautifull UI/UX design
- Clean Code and Nice Folder Structure
- Capable of
    - Fetching and displaying products from the API
    - Add to cart || Remove from cart || Check out || Icrease or decrease Quantity of item
    - Multiple pages are present
        - About page
        - Home Page
            - landing page
            - featured Section
        - Cart page
        - Product and Products Page        
    - Can Do Payment Via Paypal or debit Cart
    - Reuseable Code
    - Can Filter through Products (Search || Price || Company Name)
    - Shows Number of items in cart
- Light Themed Website
- Hosted on Netlify and set up in production

## 😌 Honest Time to finish the project
I had took about 3hr 18min to complete this project. Pretty Easy One but needed some reaserch on conversion or rgb or hexadecimal. Had a lot of fun and learnt that we can make our code very clean as in react or any other js frameworks or library. Learmt best practises of Folder Sturctures

## 👀 Feedback
If you have any feedback, please reach out to us at qa.sixsigma@gmail.com
