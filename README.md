
# 🎧 Listen-Up Fullstack

Listen-Up is a full-stack audio streaming platform offering users seamless access to their favorite tunes, while also providing admin capabilities for managing content and users.

## 🚀 Features
- **Admin Interface**: Complete control over users, content, and media assets.
- **User App**: Stream, browse, and enjoy audio content with an intuitive UI.
- **Backend API**: Securely handles media streaming, and database operations.
- **Responsive Design**: Works on desktop, tablet, and mobile devices.

## 🛠️ Tech Stack
- **Frontend**: React, CSS, HTML
- **Backend**: Node.js, Express
- **Database**: MongoDB

## 📦 Installation

1. Clone the repository:
   `git clone https://github.com/chandan-bansal/Listen-Up-fullstack.git`

2. Install dependencies for each component (admin, app, backend):
   `npm install`

3. Set up your environment variables by creating a `.env` file in the root directory of the `listen-backend` folder:
   `MONGODB_URI=your-mongo-uri`
   `CLOUDINARY_NAME=your-cloudenary-name`
   `CLOUDINARY_API_KEY=your-cloudenary-api-key`
   `CLOUDINARY_SECRET_KEY=your-cloudenary-secret-key`

4. Run the backend:
   `cd listen-backend`
   `npm run server`

5. Start the admin and user apps in separate terminals:
   `cd listen-admin`
   `npm run dev`
   `cd listen-app`
   `npm run dev`

## 📖 Usage
Once the backend and frontend are running:
- Visit the **admin panel** to manage users and upload content.
- Use the **user app** to browse and stream audio files.

## Links
- **User App**: [Click Here](https://listen-up-fullstack-frontend.onrender.com) 
- **Admin**: [Click Here](https://listen-up-fullstack-admin.onrender.com)
## 🤝 Contributing
Contributions, issues, and feature requests are welcome!  
Please follow the standard GitHub fork/clone workflow for contributing:
1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.


## 👨‍💻 Maintainer
Created and maintained by [Chandan Bansal](https://github.com/chandan-bansal).

---

Happy coding! 🎉
