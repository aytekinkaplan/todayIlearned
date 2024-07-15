# Today I Learned 📚

Welcome to the **Today I Learned** project! This application is built with React and Supabase, designed to share and explore interesting facts from various categories.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/aytekinkaplan/todayIlearned-react.git
   cd todayIlearned-react
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Set up Supabase:**

   - Sign up for a [Supabase account](https://supabase.io/).
   - Create a new project and get your Supabase URL and Key.
   - Replace the placeholders in `supabase.js` with your Supabase credentials:
     ```js
     const supabaseUrl = "your_supabase_url";
     const supabaseKey = "your_supabase_key";
     ```

4. **Start the development server:**
   ```sh
   npm start
   ```

## Usage

- The application allows users to view and share interesting facts.
- Users can filter facts by category.
- A form is available to submit new facts with a source and category.

## Features

- **Fact Submission:** Users can submit new facts with a trustworthy source.
- **Category Filter:** Facts can be filtered by various categories such as technology, science, finance, etc.
- **Voting System:** Users can vote facts as interesting, mindblowing, or false.

## Technologies Used

- **React:** Frontend framework
- **Supabase:** Backend as a Service (BaaS)
- **CSS:** Styling

## Project Structure

```
todayIlearned-react/
├── public/
│   ├── index.html
│   └── logo.png
├── src/
│   ├── App.js
│   ├── index.js
│   ├── style.css
│   └── supabase.js
├── .gitignore
├── package-lock.json
├── package.json
└── README.md
```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any features, bug fixes, or improvements.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
