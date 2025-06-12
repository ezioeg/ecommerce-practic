## 🛍️ Ecommerce Practic  
Technical test project developed with React Native CLI under a 5-day time limit. The goal is to build a navigation system between multiple screens and create a functional ecommerce clothing store design.

### Features  
- **Home Screen**  
  - Input fields for search or filters.  
  - Banner with active dots for featured promotions.  
  - Scrollable category section.  
  - Sale timer displaying limited-time offers.  
  - Scrollable subcategory section.  
  - Product listings with images and brief info.  
  - Floating tab bar for easy navigation.

- **Product Detail Screen**  
  - Header with main image and floating action buttons.  
  - Image carousel within the header allowing users to select the main header image.  
  - Detailed product information and description.  
  - Star-based product rating.  
  - Scrollable list of available sizes.  
  - Dropdown menu for selecting product colors.  
  - Floating bottom tab bar showing product price and purchase button.

<details>
  <summary>📱 Android screenshots</summary>

  <p>
    <img src="https://github.com/user-attachments/assets/be5a0fc9-474b-4386-aaff-1f71827f80fd" alt="Android Screenshot 2" width="400"/>
    <img src="https://github.com/user-attachments/assets/4acf7241-923a-44e9-8129-921a11f14479" alt="Android Screenshot 2" width="400"/>
  </p>

</details>

<details>
  <summary>📱 iOS screenshots</summary>

  <p>
    <img src="https://github.com/user-attachments/assets/07c2b044-06ef-40bb-878b-f88408e1f15c" alt="iOS Screenshot 1" width="400"/>
    <img src="https://github.com/user-attachments/assets/268dacc3-7620-4d17-9a4b-b5163c545b35" alt="iOS Screenshot 2" width="400"/>
  </p>

</details>


## Technologies Used

### Core

- [React Native](https://reactnative.dev/) `v0.79.2`
- [React](https://reactjs.org/) `v19.0.0`

### UI/Styling

- [Lucide Icons](https://github.com/lucide-icons/lucide-react-native) `v0.475.0`
- [SVG Icons](https://github.com/react-native-svg/react-native-svg) `v15.11.1`
- [Dropdown](https://github.com/react-native-picker/picker) `v2.11.0`

## Setup

Install dependencies:

> ⚠️ **Warning:** in this case, React 19.0.0 is used, which may cause peer dependency warnings with some libraries

```bash
npm install --force
```

## Run
Start metro:
```sh
# Using npm
npm start

# OR using Yarn
yarn start
```

### Build and run for Android

```sh
# Using npm
npm run android

# OR using Yarn
yarn android
```

### Build and run for iOS
Before running on iOS for the first time, make sure to install CocoaPods dependencies:
```bash
cd ios
pod install
cd ..
```

Then:
```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

## Contributions

Contributions are welcome. If you wish to improve the project, please fork it and submit a pull request.

## Contact

For questions or suggestions, you can contact me at [ezioeg@gmail.com].
