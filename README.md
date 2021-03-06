![Cypress.io](https://miro.medium.com/max/7200/1*Jkb_tsMBOvL6wQ8bzldu8Q.png)
# watanimall



This repo will allow you to check if the functionallity of the Watanimall working without problems.

Also there some of the assertion to check the style like the hover

## Requirentments
- Node js
- Chrome browser

### Dependencies used
1. [Cypress](https://www.cypress.io/)
2. [Cypress real events](https://github.com/dmtrKovalenko/cypress-real-events)
  
### How to start using this script
```javascript
git clone project

// Once it finish open it using terminal and do
npm install
```

**To run the cypress runner**
```javascript
npx cypress open
```

to do update on the test file follow the path to find all of the test cases
```
cypress/integration/watanimall-addToCart.spec.js
```


### Cypress run test

<img width="561" alt="Screen Shot 2021-12-09 at 11 00 10 AM" src="https://user-images.githubusercontent.com/57403758/145365634-9d9d96ce-d7ed-440e-abb0-0ee01939caf5.png">


### Test cases covered by this app
- Navigate to Category page from the navigation bar
- Check the hover style on the Monitor card
- Click on the Monitor card and check the url
- Filter the result based on the Manufacture and the price
- Hover over the first product and check if the button are exsits
- Click on the add to cart from the hover effect and check the total price of the side cart
- Close the side cart
- Click on the second product card and check the redirect to detaild page
- Ckech the name of the product in the details page
- Increase the quantity using the buttons and add the product to cart
- check the cart in the header if had 3 items and then delete one item from the cart
- Dynamic assertion for the cart Quantity and the cart item as custom Command
- Get the first element by `data-id` insted of `nth-child` selector
- Check the changes on monitor size once Asus selected
- Check for the changes on the product list once the sort type changed
- Check home screen (page title, active style for current nav item)
- Change category row assertion to check for empty insted of length
- Go back to home page after removing an item from teh cart and check for the url and the active style
- Change the constant variable to fixture
- Get the product 107055 and store it into fixture then check it in the details page
- Check the pagination if it's exists or not when the product count more or less than 45 
- Check add to cart button hover effect
- Remove the item from the cart based on the ket id
- Check add to cart button style in product details page
- Check the slider inside the product page
- Check for category page Breadcrumb, url when filter, and the sort must be on default on page load
- Check for the name of the product that been added to the cart ??? (text unicode)
- Check for the breadcrumb in the product details page ??? (text unicode)
- Check manufacture in details page
- Check the name of the product name, price, and quantity been added to cart from details page
- Check the stock count and compare it with the max value of the quantity
- Check the price after delete an item from the cart ??? (Bug related)
### Cypress Tasks
1. setProductData(item, Value)
2. getProductData(item)


