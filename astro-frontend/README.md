# Astro project bootstraped using create astro

```sh
pnpm dlx create astro@latest -- --template basics
```

## 🚀 Project Structure

Inside our Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where i like to put any Astro/React components.

Any static assets, like images, can be placed in the `public/` directory.

## 🚀 Getting Started

### 1. Clone the Repository

First, you'll need to clone the repository to your local machine. Open your terminal and run the following command:

```bash
git clone https://github.com/username/repo.git
```

### 2. Navigate to the Project Directory

Change your directory to the project folder:

```bash
cd repo
```

### 3. Install Dependencies

Make sure you have all the necessary dependencies installed. You can use the following command:

For **pnpm**:

```bash
pnpm install
```

### 4. Run the Project

Now, you can run the project. Use the following command:

For **pnpm**:

```bash
pnpm dev
```

## ⚙️ Technologies Used

This project utilizes the following technologies:

- **Package Manager**: `pnpm`
- **Framework**: `Astro`
- **Styling**: `Tailwind CSS`
- **Formatter**: `Prettier`

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                    | Action                                           |
| :------------------------- | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm run dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm run build`           | Build your production site to `./dist/`          |
| `pnpm run preview`         | Preview your build locally, before deploying     |
| `pnpm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [astro documentation](https://docs.astro.build)
