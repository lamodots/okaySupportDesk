# Support Desk MERN App

okaySupportTicket App is a web-based application that enables users to submit and track support tickets for any issues they encounter, streamlining support request management. Built with the MERN stack (MongoDB, Express, React, Node.js), the app offers a smooth and responsive user

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Description

The Support Desk MERN App is a web application that allows users to submit support tickets for issues they encounter. It helps in managing and tracking support requests efficiently. The app is built using the MERN stack, providing a smooth and seamless user experience.

## Features

- User authentication and authorization
- Create, view, and manage support tickets
- Assign tickets to team members
- Real-time updates on ticket status
- User-friendly interface
- Mobile-responsive design

## Installation

To run the application locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/lamodots/okaySupportDesk.git
```

2. Navigate to the project directory:

```bash
cd support-desk-react
```

3. Install the dependencies for both the server and the client:

```bash
# Install server dependencies
npm install

# Install client dependencies
cd ./client
npm install
```

4. Set up the environment variables:

   - Rename `.env.example` to `.env` in both the `server` and `client` directories.
   - Fill in the required environment variables in the `.env` files.

```bash
JWT_SECRET = something
MONGO_URI = mongo db cluster connection link
```

5. Start the development server(from root directory):

```bash
# Start development application
npm run dev

# Start the server only
npm run server

# Start the client only
npm run client
```

The app will be available at [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

- Register or login to access the support ticket dashboard.
- Click on "Create Ticket" to submit a new support ticket.
- View and manage existing tickets from the dashboard.
- Assign tickets to team members for resolution.
- Receive real-time updates on ticket status changes.

## Technologies Used

- (M)ongoDB
- (E)xpress.js
- (R)eact
- (N)ode.js

## Contributing

Contributions to this project are welcome! If you find any issues or want to add new features, please submit a pull request.

## Live Demo

Check out the live demo of the application [here](https://lamodots-okaysupportdesk.onrender.com/).
