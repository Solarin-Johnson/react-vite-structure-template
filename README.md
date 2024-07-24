# React Vite Structure Template

A template for React projects using Vite.

## Features

- React
- Vite

## Getting Started

1. **Create a repository from this template on GitHub.**
2. **Clone the new repository:**

   ```bash
   git clone https://github.com/yourusername/react-vite-structure-template.git
   cd react-vite-structure-template
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Run the development server:**

   ```bash
   npm run dev
   ```

## Pushing to Multiple Repositories

1. **Add a secondary remote:**

   ```bash
   git remote add secondary <url_of_second_repository>
   ```

2. **Push to both repositories:**

   ```bash
   git push origin main
   git push secondary main
   ```

   Or set up a Git alias:

   ```bash
   git config --global alias.pushall '!git push origin main && git push secondary main'
   git pushall
   ```

## License

MIT

```
This `README.md` now focuses solely on the project setup and handling multiple repositories.
```
