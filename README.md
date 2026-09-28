# Product list with cart

A Frontend Mentor "Product list with cart" solution in React + Vite.

## Features

- Product grid of 9 desserts loaded from `src/data.json`, showing category, name and price
- "Add to Cart" button on each product card
- Quantity controls on the card after an item is added: increment and decrement buttons with the current count (decrementing to zero clears the item's quantity)
- Selected products get a highlighted border on their image
- Cart panel with an empty state ("Your added items will appear here") and a list of added items with their prices
- Item count and order total in the cart
- Responsive layout (breakpoints at 768px and 480px), with mobile, tablet or desktop product images picked through `react-responsive`

## Tech stack

- React 18
- Vite 6
- JavaScript (JSX)
- CSS with media queries
- react-responsive
- ESLint

## Run locally

Requires Node.js and npm.

```bash
npm install
npm run dev      # start the Vite dev server
npm run build    # production build in dist/
npm run preview  # serve the production build locally
npm run lint     # run ESLint
```

## Next steps

- Connect the cart's remove button and "Confirm Order" button to the cart state (the `Cart` component doesn't get `setCartItems` yet)
- Group repeated items in the cart into one line with a quantity
- Add the order confirmation modal and "Start New Order" reset from the challenge design

## Credits

Challenge by [Frontend Mentor](https://www.frontendmentor.io): [Product list with cart](https://www.frontendmentor.io/challenges/product-list-with-cart-5MmqLVAp_d). Design, product data and images come from the challenge.
