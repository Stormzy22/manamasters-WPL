# 🧙 ManaMasters — Magic: The Gathering Deck Builder

**ManaMasters** is a web application for discovering *Magic: The Gathering* cards, creating personalized decks, and testing card draws. Built as a team project with **Node.js**, **Express**, and **MongoDB**, it retrieves card information from the Magic: The Gathering API and lets signed-in users manage their own decks.

![ManaMasters application preview](https://github.com/HamzaChl/manamasters-WPL/assets/91462821/3c92550f-81dd-446a-8b26-fac9f54d49c8)

## 🛠️ Tech Stack

| Technology | Purpose |
| --- | --- |
| **Node.js** | Runs the application on the server |
| **Express** | Handles routes and HTTP requests |
| **MongoDB** | Stores user-specific deck information |
| **Magic: The Gathering API** | Provides card details and search results |

## ✨ Features

### 🔐 User Access & Navigation
- **Landing page** — Explore available projects with their names and images.
- **Authentication** — Sign in to access protected project details.
- **Project selection** — Select a project once authenticated.
- **Personal decks** — Each user can manage their own card collections and decks.

### 🔎 Card Search & Discovery
- **Card search** — Find cards by entering a search term.
- **Search results** — View the first 10 matches, with pagination for additional results where available.
- **Rarity indicators** — Different card borders for Common, Uncommon, Rare, and Mythic Rare cards.
- **Hover preview** — Enlarge a card by hovering over it.

### 🃏 Deck Management
- **Build decks** — Add cards from search results to your decks.
- **Edit decks** — Remove cards and adjust quantities.
- **Draw test** — Simulate drawing cards to experiment with a deck.

## 🚀 Getting Started

### Prerequisites
- **Node.js** and **npm**
- Access to a **MongoDB** database

### Installation

**1. Clone the repository**

```bash
git clone <repository-url>
cd <repository-folder>
```

**2. Install dependencies**

```bash
npm install
```

**3. Configure the database**

Make sure your MongoDB connection is configured as required by the project. Keep any credentials or secrets out of version control.

**4. Start the application**

```bash
npm start
```

**5. Open the app**

Visit **http://localhost:3000** if you are using the project's default port.

> **Note:** Replace the repository placeholders with your own GitHub URL and folder name. Depending on the project configuration, you may also need to set environment variables before running the app.

## 🎮 How to Use

1. **Explore** — Open the landing page and browse available projects.
2. **Sign in** — Log in to access project details and your personal decks.
3. **Find cards** — Search for *Magic: The Gathering* cards by name or keyword.
4. **Inspect cards** — Preview a card and see its rarity styling.
5. **Build a deck** — Add or remove cards and change quantities.
6. **Test your deck** — Use the draw test to simulate drawing cards.

## 📚 What We Practiced

- Building a web application with Node.js and Express
- Integrating an external API to retrieve card data
- Working with MongoDB to manage user-specific data
- Implementing authenticated user flows
- Creating an interactive deck-building experience
- Collaborating on a shared software project

## 👥 Contributors

Developed as a collaborative school project by **Charaf, Imran, and Hamza** under the team name **ManaMasters**.

## 🔗 API Reference

Card data is provided by the [Magic: The Gathering API](https://docs.magicthegathering.io/).

## 📄 License

This project is distributed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
