# VD Motors

Welcome to the VD Motors website repository! This project is aimed at creating a premium platform for bike enthusiasts to explore and purchase high-end motorbikes. The website leverages modern web technologies to provide a sleek, efficient, and responsive user experience.

## Technologies Used

- **Next.js**: A React framework for production that makes it easy to build fast and user-friendly web applications.
- **Tailwind CSS**: A utility-first CSS framework for rapidly building custom designs.
- **Prisma**: An open-source database toolkit for modern databases, offering a data model-centric approach.
- **Shadcn**: A collection of unstyled components designed to work seamlessly with your design system and styling choices.

## Project Structure

- `pages/` - Contains the Next.js pages.
- `components/` - Contains the reusable React components.
- `styles/` - Contains the global and component-specific styles.
- `prisma/` - Contains the Prisma schema and migration files.
- `public/` - Contains static files such as images and icons.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (>= 14.x)
- npm or yarn
- PostgreSQL (or any other supported database)

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/VyomOp2/vd-motors.git
    cd vd-motors
    ```

2. **Install dependencies**:

    ```bash
    npm install
    # or
    yarn install
    ```

3. **Set up the database**:

    Update the `DATABASE_URL` in your `.env` file with your database connection string.

    ```bash
    cp .env.example .env
    ```

    Run the Prisma migrations:

    ```bash
    npx prisma migrate dev
    ```

4. **Run the development server**:

    ```bash
    npm run dev
    # or
    yarn dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Documentation

For more detailed information on the technologies used, refer to their official documentation:

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Prisma Documentation](https://www.prisma.io/docs)
- [Shadcn Documentation](https://shadcn.dev/docs)

This project is licensed under the MIT License. See the `LICENSE` file for more information.

---

Happy coding! 🚀

