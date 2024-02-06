# Next.js Tailwind TypeScript MongoDB Docker Starter

![Starter Banner](banner.png)

Kickstart your Next.js project with Tailwind CSS, TypeScript, MongoDB, Docker, and NextAuth.js v5 for authentication!

## Features

- **Next.js**: React framework for server-rendered applications.
- **Tailwind CSS**: Utility-first CSS framework.
- **TypeScript**: Typed JavaScript for enhanced development.
- **MongoDB**: NoSQL database for flexible data storage.
- **Docker**: Containerization for easy deployment and scaling.
- **NextAuth.js v5**: Authentication library for Next.js applications.

## Getting Started

Follow these steps to get your project up and running:

1. Clone this repository.
2. Install dependencies with `npm install` or `yarn install`.
3. Configure environment variables in `.env.local`.
4. Run the development server with `npm run dev` or `yarn dev`.
5. Visit `http://localhost:3000` to view your application.

## Environment Variables

Make sure to set up the following environment variables:

- `MONGODB_URI`: MongoDB connection URI.
- `SECRET`: Secret key for session storage.
- Add any additional configuration variables as needed.

## Folder Structure

- `pages/`: Next.js pages.
- `components/`: React components.
- `styles/`: Global styles and Tailwind configurations.
- `utils/`: Utility functions.
- Add more directories as your project grows.

## Docker

To run the project with Docker:

1. Build the Docker image: `docker build -t your-image-name .`
2. Run the Docker container: `docker run -d -p 3000:3000 your-image-name`

## Contributions

Contributions are welcome! Feel free to submit issues and pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy coding! 🚀✨
