<div align="center">

# Flutter E-Commerce Virtual Try-On

A Flutter graduation project that combines a modern e-commerce experience with a Virtual Try-On feature.

</div>

---

## About the Project

This project is developed by a team of **5 members** as part of our Flutter graduation project.

The application provides a complete e-commerce experience where users can browse products, search and filter items, manage their wishlist and cart, complete orders, and use a **Virtual Try-On feature** to preview supported products before purchasing.

The main goal is to create a more interactive and personalized online shopping experience using Flutter and modern mobile development concepts.

---

## Main Features

- User authentication
- Home screen
- Product categories
- Product listing
- Product details
- Product search
- Filtering and sorting
- Wishlist
- Shopping cart
- Checkout
- Order history
- User profile
- Virtual Try-On
- Camera and gallery integration
- REST API integration

---

## Virtual Try-On

The Virtual Try-On feature allows users to preview supported products before making a purchase.

Basic flow:

```text
Select Product
      |
Virtual Try-On
      |
Upload Image / Camera
      |
Image Processing
      |
Preview Result
      |
Add to Cart
```

---

## Tech Stack

| Technology | Usage |
|---|---|
| Flutter | Mobile application development |
| Dart | Programming language |
| REST API | Backend communication |
| Dio / HTTP | API requests |
| State Management | Application state handling |
| Local Storage | Store local app data |
| Image Picker / Camera | Image selection and capture |
| AI / Image Processing API | Virtual Try-On functionality |
| Git | Version control |
| GitHub | Team collaboration |

---

## Project Structure

```text
lib/
|
|-- core/
|   |-- constants/
|   |-- network/
|   |-- routes/
|   |-- theme/
|   `-- utils/
|
|-- features/
|   |-- auth/
|   |-- home/
|   |-- categories/
|   |-- products/
|   |-- search/
|   |-- wishlist/
|   |-- cart/
|   |-- checkout/
|   |-- orders/
|   |-- profile/
|   `-- virtual_try_on/
|
|-- shared/
|   |-- models/
|   |-- widgets/
|   `-- services/
|
`-- main.dart
```

---

## Main Modules

| Module | Description |
|---|---|
| Authentication | Login, registration, and account management |
| Home | Main shopping experience |
| Products | Product listing and product details |
| Categories | Browse products by category |
| Search | Search, filter, and sort products |
| Wishlist | Manage favorite products |
| Cart | Manage selected products |
| Checkout | Complete the purchasing process |
| Orders | View previous orders |
| Profile | Manage user information |
| Virtual Try-On | Preview supported products virtually |

---

## Team

This project is developed by a team of **5 members**.

| Member | Role |
|---|---|
| Donia Alhosin | Flutter Developer |
| Emad  Hani | Flutter Developer |
| Mohey | Flutter Developer |
| Saga | Flutter Developer |
| Member 5 | Flutter Developer |
---

## Getting Started

Clone the repository:

```bash
git clone <repository-url>
```

Open the project:

```bash
cd flutter-ecommerce-virtual-tryon
```

Install dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

---

## Requirements

- Flutter SDK
- Dart SDK
- Android Studio or Visual Studio Code
- Android Emulator or physical device
- Git

Check your Flutter environment:

```bash
flutter doctor
```

---

## Repository

```text
flutter-ecommerce-virtual-tryon
```

---

## Project Status

Currently under development.

---

## License

This project is created for educational and graduation purposes.
