# 🌍 Wanderlust – Airbnb Clone

**Wanderlust** is a full-stack web application inspired by **Airbnb**, where users can explore travel listings, create their own listings, and review places.
It is built using **Node.js, Express.js, MongoDB, EJS, Bootstrap, and JavaScript**.

This project demonstrates **full-stack CRUD operations, authentication, session management, and RESTful routing**.

---

## 🚀 Features

* 🏠 Create, edit, and delete property listings
* 🔍 Browse and view available listings
* ⭐ Add and delete reviews for listings
* 👤 User authentication (Sign up / Login / Logout)
* 🔐 Secure authentication using Passport.js
* 💬 Flash messages for success and error notifications
* 📦 Session storage using MongoDB
* 🎨 Responsive UI using Bootstrap
* ⚠️ Error handling and custom error pages

---

## 🛠️ Tech Stack

**Frontend**

* EJS (Embedded JavaScript Templates)
* Bootstrap
* HTML5
* CSS3
* JavaScript

**Backend**

* Node.js
* Express.js

**Database**

* MongoDB
* Mongoose

**Authentication & Security**

* Passport.js
* Passport-Local
* Express Session
* Connect-Mongo

**Other Tools**

* Method Override
* Connect Flash
* Dotenv
* EJS-Mate (for layout templates)

---

## 📂 Project Structure

```
wanderlust/
│
├── models/
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── routes/
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── utils/
│   └── ExpressError.js
│
├── views/
│   ├── listings/
│   ├── users/
│   ├── layouts/
│   └── error.ejs
│
├── public/
│   ├── css/
│   ├── js/
│   └── images/
│
├── app.js
├── package.json
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/wanderlust.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd wanderlust
```

### 3️⃣ Install Dependencies

```bash
npm install
```

---

## 🔑 Environment Variables

Create a **`.env`** file in the root directory.

Example:

```
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret
```

---

## ▶️ Running the Application

Start the server:

```bash
node app.js
```

or

```bash
npm start
```

Server will run at:

```
http://localhost:8080
```

---

## 🔄 Application Workflow

1. Users can **sign up or log in** to the platform.
2. Authenticated users can:

   * Create new listings
   * Edit or delete their listings
3. Users can **view listings posted by others**.
4. Users can **add reviews and ratings** for listings.
5. Session data is stored in **MongoDB using connect-mongo**.

---

## 📸 Screenshots (Optional)

You can add screenshots here:

```
/screenshots/homepage.png
/screenshots/listing.png
/screenshots/add-listing.png
```

Example:

```
![Homepage](screenshots/homepage.png)
```

---

## 🔮 Future Improvements

* 🌍 Map integration (Mapbox / Google Maps)
* 📷 Image upload with Cloudinary
* 🔎 Search and filtering
* ❤️ Wishlist / Favorites feature
* 📊 Review ratings analytics
* 📱 Improved mobile responsiveness

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```
git checkout -b feature-name
```

3. Commit your changes

```
git commit -m "Added new feature"
```

4. Push to the branch

```
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

Developed by **Your Name**

If you like this project, consider giving it a ⭐ on GitHub!
