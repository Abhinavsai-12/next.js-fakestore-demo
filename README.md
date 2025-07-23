🛒 Next.js FakeStore API E-Commerce Demo
This is a simple e-commerce demo built with Next.js using the FakeStore API. It demonstrates how to implement file-based routing, fetch data using getStaticProps/getStaticPaths, and build pages for:

All Products
Single Product Details



Pages Overview
/products
Fetches all products from FakeStore API.
Displays product cards with title, image, and price.
Each product links to its detailed view.


/products/[id]
Dynamic route to display single product details.
Fetches individual product using product id (e.g. /products/1)
Shows detailed info: title, price, image, description, category, etc.




How to Run Locally
#1. Clone the repo
git clone https://github.com/Abhinavsai-12/next.js-fakestore-demo.git

#2. Navigate into project directory
cd nextjs-fakestore-demo

#3. Install dependencies
npm install

#4. Run the development server
npm run dev



Open http://localhost:3000/products to view it in the browser.




