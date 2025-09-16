# GrainLoop - Farmer-Customer Marketplace

GrainLoop is a web application that connects farmers directly with customers, providing a platform for agricultural product sales, communication, and market information.

## Features

- **Farmer Product Upload**: Farmers can upload products with images, prices, and details
- **Customer Browsing & Cart**: Customers can browse products and add them to cart
- **Direct Messaging**: Real-time chat between farmers and customers
- **Order Placement**: Simple order placing with confirmation
- **Dynamic Pricing**: Local mandi prices display
- **Crop Calendar**: Planting and harvesting reminders for farmers
- **Offline Mode**: Basic offline functionality

## Tech Stack

- React.js
- Material-UI
- Firebase (Realtime Database, Storage, Authentication)
- React Router

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/grainloop.git
cd grainloop
```

2. Install dependencies:
```bash
npm install
```

3. Create a Firebase project and add your configuration:
   - Go to [Firebase Console](https://console.firebase.google.com/)
   - Create a new project
   - Enable Authentication, Firestore Database, and Storage
   - Copy your Firebase configuration
   - Replace the configuration in `src/firebase.js`

4. Start the development server:
```bash
npm start
```

5. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Project Structure

```
src/
  ├── components/     # Reusable UI components
  ├── pages/         # Page components
  ├── firebase.js    # Firebase configuration
  ├── App.js         # Main application component
  └── index.js       # Entry point
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
