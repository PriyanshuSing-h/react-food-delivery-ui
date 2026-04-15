#  Food Delivery Frontend project inspired by swiggy

This is a frontend project I built to practice React and state management. Instead of using hardcoded dummy data, I integrated Swiggy's live API to fetch and display real restaurants and menus.

## Tech Stack
- React.js
- Redux (for cart management)
- CSS
- Parcel

## What I built and learned
- **Live API Data:** Hooked up the frontend to Swiggy's actual production API to render dynamic UI.
- **Handling CORS:** Ran into CORS errors when trying to fetch the live data locally, so I figured out how to use a proxy URL to bypass the restrictions.
- **State Management:** Used Redux to handle the cart logic so the cart data stays consistent when navigating between different restaurant menus.
- **Component Structure:** Broke down the UI into functional components like restaurant cards, header, and menu items to keep the code clean.



## Steps to run locally
1. Clone this repo:
   `git clone https://github.com/PriyanshuSing-h/swiggyClone.git`
2. Install the packages:
   `npm install`
3. Start the app:
   `npm start`
