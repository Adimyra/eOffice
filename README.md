# eOffice

eOffice is a custom Frappe application designed to streamline office workflows, including managing letters, recipients, and tasks. This app integrates modern UI design with Tailwind CSS for a seamless user experience.

## Features
- **Letter Management**: Create, track, and manage letters efficiently.
- **Recipient Management**: Maintain a database of recipients for streamlined communication.
- **Task Management**: Assign and track tasks within the office.
- **Tailwind CSS Integration**: Modern and responsive UI design.

## Installation
1. Clone the repository into your Frappe Bench apps directory:
   ```bash
   cd ~/frappe-bench/apps
   git clone <repository-url> eoffice
   ```
2. Install the app:
   ```bash
   bench install-app eoffice
   ```
3. Add the app to your site:
   ```bash
   bench --site <your-site-name> install-app eoffice
   ```

## Development
- Use `npm` to manage dependencies for Tailwind CSS:
  ```bash
  npm install
  ```
- Build Tailwind CSS:
  ```bash
  npx tailwindcss -i ./public/css/tailwind.css -o ./public/css/tailwind.min.css --watch
  ```

## License
This project is licensed under the MIT License.