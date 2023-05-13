# TicketR

[![Build Status](https://img.shields.io/travis/user/repo.svg)](https://travis-ci.org/user/repo)
[![Coverage Status](https://coveralls.io/repos/github/user/repo/badge.svg?branch=master)](https://coveralls.io/github/user/repo?branch=master)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## About

A platform for organizing and selling event tickets. The system allows customers to create an account, search for events, book tickets, and view event details. Organizers can create an account, list their events, and sell their tickets. The admin panel allows the admin to manage user records, generate invoices, and approve or remove events and venues.

## Requirements

### Functional

- Allow customers to create an account, sign up, and log in to the system.
- Enable customers to search and find events by applying several filters such as date, price, name, venue, artist, team, and etc.
- Allow customers to view the availability of the event by selecting a particular date from the calendar available on their screen.
- Allow customers to choose the reservation type (General, Premium, VIP) to book the seat they prefer.
- Allow customers to view tickets by pricing (highest to lowest).
- Allow customers to confirm and pay for the booking.
- Allow customers to cancel their ticket before a certain period.
- Allow organizers to create an account, sign up, and log in to the system.
- Allow organizers to list their events on the site and sell their tickets.
- Allow organizers to update their event details.
- Allow the admin to generate invoices for the events.
- Allow the admin to cancel bookings.
- Allow the admin to register and remove organizers.
- Allow the admin to add and delete user records.
- Store all the information of the users, events, and libraries in a database that is accessible by the website.

### Non-Functional

- Operate on the Windows environment and Google Chrome.
- Only require an internet connection to use.
- Minimum hardware requirements of Core i5 8th Generation, 16GB RAM, and less than 500MB of disk space for the project and its dependencies.
- Error-free and user-friendly.
- Record and store any update regarding the events from the organizers to the database, and the data entered should be correct.
- Admin should have a proper understanding of the product.
- Login interface that allows users to register and create their accounts, and log in to the system. If the user enters either their username or password incorrectly, then an error message appears.
- Categories-view that allows customers to find their event by different categories by applying several filters such as nearby city, venue, name, etc.
- Calendar incorporated that allows the customer to find their event by selecting a particular date from the calendar available on their screen.
- Admin panel that allows the admin to add/remove users, add, approve, or remove an event or a venue.

## Technologies Used

- IDEs: Visual Studio Code
- Tools: HTML, CSS, ReactJs, NodeJs, ExpressJs, PHPMySQL, Browser, Jest, Nodemon, Body-parser
- Programming Languages: JavaScript

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository
git clone https://github.com/user/repo.git

2. Install dependencies
npm install

3. Start the server
npm start


## Usage

- Visit the website and sign up or log in
- Search for an event by applying filters or selecting a date from the calendar
- Choose the reservation type and book the seat you prefer
- Confirm and pay for your booking
- View your tickets and cancel them if necessary
- For organizers, sign up and log in to list and sell your events
- For admins, log in to manage user records, events, and invoices

## Contributing

Contributions are welcome! Here are the steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make changes and commit them (`git commit -am 'Add your message here'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Create a new pull request

Please make sure your code follows the existing style and conventions. Also, make sure to test your changes thoroughly.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
