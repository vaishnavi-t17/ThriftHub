# ThriftHub 🛍️

### A Marketplace for Pre-Loved Goods

ThriftHub is an online marketplace designed to connect people who want to buy and sell second-hand products. It provides a platform where users can create product listings, explore available items, connect with vendors, and manage their marketplace activities.

The goal is to make buying and selling pre-owned products easier, more accessible, and more sustainable.

---

## ✨ Features

- **User Authentication** – Register, sign in, and manage user accounts.
- **Product Listings** – Create, edit, and delete product listings.
- **Product Categories** – Organize products into relevant categories.
- **Image Uploads** – Add images to product listings.
- **Vendor Profiles** – Manage vendor information and activities.
- **Order Management** – Place orders and track order history.
- **Saved Listings** – Save products for future reference.
- **Product Search** – Search and filter available products.


## 🛠️ Technology Stack

| Component | Technologies |
|---|---|
| Frontend | React Native, TypeScript, Expo |
| Backend | Python, Django, Django REST Framework |
| Database | PostgreSQL |
| Package Management | Yarn |
| Version Control | Git, GitHub |

## 📁 Project Structure

```text
ThriftHub/
│
├── backend/              # Django backend
├── frontend/             # React Native frontend
├── .github/              # GitHub configuration
├── configureBackend.js  # Backend setup script
├── configurePath.js     # Environment path configuration
├── package.json          # Root project scripts
├── yarn.lock
├── README.md
└── LICENSE
```

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Git
- Node.js
- Yarn
- Python
- PostgreSQL

### 1. Clone the repository

```bash
git clone https://github.com/vaishnavi-t17/ThriftHub.git
cd ThriftHub
```

### 2. Install dependencies

```bash
yarn install
```

### 3. Configure the backend

```bash
yarn setup:backend
```

This runs the project's backend configuration scripts.

### 4. Start the application

To start both frontend and backend:

```bash
yarn dev
```

Alternatively, start them separately:

```bash
yarn start:backend
```

```bash
yarn start:frontend
```

*Make sure the required backend environment variables and database configuration are set before running the application.*

## 🔮 Future Improvements

Potential areas for further development include:

- Advanced product search and filtering.
- Product collections and bundle deals.
- Improved buyer–seller communication.
- Secure payment gateway integration.
- Enhanced user experience and responsive design.
- Production deployment and performance optimization.

## 🤝 Contributions

Contributions, suggestions, and feedback are welcome. Feel free to explore the project, report issues, or suggest improvements.

## 👨‍💻 Repository

**GitHub:** https://github.com/vaishnavi-t17/ThriftHub

## 📄 License

This project retains its original MIT license and associated copyright attribution. See the [LICENSE](LICENSE) file for details.

---

*ThriftHub — Give pre-loved products a new home.* ♻️
