# **Hash - Unique Slice of Time and Space**

## **Overview**

**Hash** is a React application that allows users to generate a unique digital hash representing a slice of time, space, and custom information. Users can upload images, include timestamps, geolocation, and even custom strings to generate a unique hash that captures a moment or memory. The hash result can be easily copied by clicking on it.

---

## **Getting Started**

### **Prerequisites**

To run this project, ensure you have the following installed on your machine:
- **Node.js**: Download and install from [https://nodejs.org/](https://nodejs.org/)
- **npm**: It comes bundled with Node.js. Run `npm -v` to check if it's installed.

### **Installation**

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/image-hasher.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd image-hasher
   ```

3. **Install the dependencies**:

   ```bash
   npm install
   ```

### **Running the App**

After the dependencies have been installed, you can start the app by running:

```bash
npm start
```

This will start the development server and open the app in your default browser. The app should be accessible at [http://localhost:3000](http://localhost:3000).

---

## **Usage**

visit the website and you will find out by yourself. Quite straight forward.

---

## **Folder Structure**

```
├── public
│   ├── index.html         # Main HTML file
├── src
│   ├── ImageHasher.js     # Main React component
│   ├── App.js             # App entry component
│   ├── App.css            # Custom CSS styles
│   └── index.js           # Main JavaScript entry point
├── package.json           # Project dependencies and scripts
├── README.md              # This README file
```

---

## **Customization**

### **Changing the Font**

To customize the font, you can either:
1. Use a Google Font by importing it in the `App.css` or `index.html`.
2. Use a locally hosted font by including it in the `/src/fonts/` directory and referencing it in your CSS.

### **CSS Modifications**

If you want to change the look and feel of the app, you can modify the `App.css` file. The default theme is a dark mode, but you can customize the colors, typography, and layouts as needed.

---

## **Built With**

- **React**: A JavaScript library for building user interfaces. Learn more at [React](https://reactjs.org/).
- **CryptoJS**: A library for generating the SHA-256 hash. Learn more at [CryptoJS](https://cryptojs.gitbook.io/docs/).
- **browser-image-compression**: A library for image compression in the browser. Learn more at [browser-image-compression](https://www.npmjs.com/package/browser-image-compression).

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
