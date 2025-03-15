# Family Travel Tracker

A web application to track the countries visited by family members.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/family-travel-tracker.git
   cd family-travel-tracker
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Create a `.env` file in the root directory and add your PostgreSQL database credentials:

   ```env
   PG_USER=yourusername
   PG_HOST=yourhost
   PG_DATABASE=yourdatabase
   PG_PASSWORD=yourpassword
   PG_PORT=yourport
   ```

4. Start the server:

   ```sh
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000`

## Usage

- To add a new user, click on the "Add New User" button and fill in the details.
- To add a visited country, enter the country name in the input field and click "Add".
- To switch between users, select a user from the dropdown and click "Switch User".

## Demo

![Demo](./demo.gif)

## License

This project is licensed under the MIT License.
