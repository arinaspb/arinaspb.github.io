# Arina.fyi Website

This is the source code for Arina Chernova's personal website, [Arina.fyi](https://arina.fyi).

## Getting Started

### Prerequisites

Make sure you have [pnpm](https://pnpm.io/installation) installed, e.g. using `brew install`.

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/arinaspb/arinaspb.github.io.git
   ```
2. Navigate to the project directory:
   ```sh
   cd arinaspb.github.io
   ```
3. Install the dependencies:
   ```sh
   pnpm install
   ```

### Running the Development Server

To start the local development server, run the following command in the folder of the project:
```sh
pnpm run dev
```
You can then access the website at `http://localhost:4321`.

## Building for Production

To build the website for production, run the following command:
```sh
pnpm run build
```
The production-ready files will be located in the `dist/` directory.

## Deployment

The site is automatically deployed to GitHub Pages whenever changes are pushed to the `main` branch.
