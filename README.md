## Flask Application Design for Indian Snacks Delivery App

### HTML Files

- **index.html**: This is the main landing page of the app. It should include a visually appealing presentation of the app, highlighting its convenience, variety, and freshness. The page should feature a call-to-action to encourage users to download the app and start their culinary adventure.
- **menu.html**: This page should present the menu of available snacks, categorized by type and dietary preferences. It should provide clear and detailed descriptions of each snack, making the selection process easier for users.
- **cart.html**: This page should display the items added to the user's cart, allowing them to review their order, make changes if necessary, and proceed to checkout.
- **checkout.html**: This page should handle the checkout process, including secure payment options and an order confirmation mechanism.
- **profile.html**: This page should allow users to manage their account, including updating their personal information, reviewing past orders, and managing subscriptions.

### Routes

- `/index`: This route serves the index.html file, which is the main landing page of the app.
- `/menu`: This route serves the menu.html file, presenting the selection of available snacks.
- `/cart`: This route serves the cart.html file, where users can view and manage their orders.
- `/checkout`: This route serves the checkout.html file, handling the checkout process.
- `/profile`: This route serves the profile.html file, allowing users to manage their account.
- `/order`: This route handles the placement of an order, receiving the user's cart items and payment information.
- `/payment`: This route processes the payment and returns a confirmation or error message.
- `/update-profile`: This route handles updates to the user's profile information.
- `/order-history`: This route provides a list of the user's past orders.