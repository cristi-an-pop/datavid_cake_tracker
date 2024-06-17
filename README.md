# datavid_cake_tracker

## Installation Instructions
### Prerequisites
- Node.js and npm installed.
- PostegreSQL installed

### Installation

Clone the repository:

```bash
https://github.com/funnker/datavid_cake_tracker.git
```

#### Frontend

Install Dependencies

```bash
npm install
```

Configure Environment Variables

Configure Environment Variables
Create a .env file in the frontend directory with the following content:

```bash
VITE_REACT_APP_SERVER_URL=(server_path)
```

Start the Frontend

```bash
npm run dev
```

#### Backend

Install Dependencies

```bash
npm install
```

Configure Environment Variables

Configure Environment Variables
Create a .env file in the frontend directory with the following content:

```bash
DB_HOST=localhost
DB_PORT=5432
DB_USER=postgres
DB_PASSWORD=1234
DB_NAME=datavid
PORT=5000
ACCESS_TOKEN_SECRET=accessTokenSecret
REFRESH_TOKEN_SECRET=refreshTokenSecret
CLIENT_URL=(client_path)
```

Start the Backend

```bash
npm run dev
```

#### Database

Create a PostgreSQL database that would later be passed in the .env file of the backend
