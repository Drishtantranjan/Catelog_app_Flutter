
# Catelog App (Flutter)

This is an Ecommerce application built with **Flutter**, utilizing the **Velocity X** state management library. The app provides a user-friendly interface for browsing and purchasing various products online.

![Alt text](file:///home/drishtant/Downloads/Graphic%20Design.png)


## Features

- **Product Listing:** Browse through a wide range of products with detailed descriptions and prices.
- **Product Search:** Easily search for specific products using keywords or filters.
- **Product Categories:** Explore products organized into different categories for convenient browsing.
- **Product Details:** View in-depth information about a specific product, including images, reviews, and specifications.
- **Shopping Cart:** Add products to the shopping cart for easy checkout.
- **User Authentication:** Register an account or log in to an existing account for personalized shopping experience.
- **Order Management:** Track and manage your orders, including order history and status updates.


## Themes

![Graphic Design](https://user-images.githubusercontent.com/84273332/178148646-9e53aa71-c03e-438f-9b79-c46fafab8107.png)
![Graphic Design (1)](https://user-images.githubusercontent.com/84273332/178148667-0eee1188-c68a-4141-8640-9058dd6daa35.png)


## Dependencies

The following dependencies are used in this project:

- flutter
- velocity_x
- http
- cached_network_image
- shared_preferences

All dependencies and their versions can be found in the **pubspec.yaml** file.
## Folder Structure

## lib

* [core/](./lib/core)
  * [store.dart](./lib/core/store.dart)
* [models/](./lib/models)
  * [cart.dart](./lib/models/cart.dart)
  * [catelog.dart](./lib/models/catelog.dart)
* [pages/](./lib/pages)
  * [cart_page.dart](./lib/pages/cart_page.dart)
  * [home_detail_page.dart](./lib/pages/home_detail_page.dart)
  * [homepage.dart](./lib/pages/homepage.dart)
  * [login_page.dart](./lib/pages/login_page.dart)
* [utils/](./lib/utils)
  * [routes.dart](./lib/utils/routes.dart)
* [widgets/](./lib/widgets)
  * [home_widgets/](./lib/widgets/home_widgets)
    * [add_to_cart.dart](./lib/widgets/home_widgets/add_to_cart.dart)
    * [catelog_header.dart](./lib/widgets/home_widgets/catelog_header.dart)
    * [catelog_image.dart](./lib/widgets/home_widgets/catelog_image.dart)
    * [catelog_list.dart](./lib/widgets/home_widgets/catelog_list.dart)
  * [drawer.dart](./lib/widgets/drawer.dart)
  * [item_widget.dart](./lib/widgets/item_widget.dart)
  * [themes.dart](./lib/widgets/themes.dart)
* [main.dart](./lib/main.dart)

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue.


## Acknowledgements

- Flutter
- Velocity X
- Firebase
