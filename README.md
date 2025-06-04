# 🧠 Nutrient-IQ

**Nutrient-IQ** is a simple Rails-based food logging app that helps users track meals and monitor nutritional intake with ease. Built using **Ruby on Rails** and styled with the sleek, responsive **Bulma CSS framework**, this app focuses on simplicity, speed, and a clean user experience.

---

## 🛠️ Tech Stack

- **Backend**: Ruby (3.3.1) on Rails (8.0.2)
- **Frontend**: Bulma CSS Framework
- **Database**: PostgreSQL

---

## 📦 Features

- Log meals with name, category, calories, and timestamp
- View daily and weekly meal summaries
- Categorize meals (breakfast, lunch, dinner, snacks)
- Edit or delete entries
- Clean, mobile-friendly UI using Bulma
- Optional user authentication for multiple users

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ulricscott/nutrient-iq.git
cd nutrient-iq
````

### 2. Install Dependencies

Ensure you have Ruby, Bundler, Yarn, and PostgreSQL installed.

```bash
bundle install
yarn install
```

### 3. Set Up the Database

```bash
rails db:create db:migrate db:seed
```

### 4. Start the Server

```bash
rails server
```

Visit `http://localhost:3000` to use the app.

---

## 🎨 Styling with Bulma

Nutrient-IQ uses **Bulma**, a lightweight CSS framework with a modern design language.

You can modify styles in `app/assets/stylesheets/application.scss`:

```scss
@import "bulma";

body {
  background-color: #f5f5f5;
}
```

Bulma utility classes are used directly in the views (e.g., `.container`, `.box`, `.button`, `.notification`).

---

## 🧪 Running Tests

```bash
bundle exec rspec
```

Test coverage can include models, controllers, and views.

---

## 🚧 Roadmap

* API for nutrition label scanning or search
* Charts and visualizations for macro tracking
* Personalized goals and tracking streaks
* Mobile-first enhancements with Turbo

---

## 🤝 Contributing

Pull requests are welcome! If you’d like to contribute:

1. Fork the repo
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes
4. Push and open a pull request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

Built with 🍜 by [@ulricscott](https://github.com/ulricscott)