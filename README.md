# Restaurant-Finder-Yelp-Clone

![image](https://github.com/subashrai02468/Restaurant-Finder-Yelp-Clone/assets/154571406/b89158d1-007a-4fbd-ab3c-91d125c325c3)


```markdown
# Restaurant Finder - Yelp Clone

This project is a Yelp clone named "Restaurant Finder", built using the PERN stack (PostgreSQL, Express.js, React, and Node.js). It is designed to allow users to search for restaurants, view details, add reviews, and rate them, similar to the functionality found on Yelp.

## Features

- Browse Restaurants: Users can view a list of restaurants with basic details.
- Search Functionality: Includes a search feature to find restaurants by name or location.
- Restaurant Details: Click on a restaurant to see detailed information, including reviews and ratings.
- User Reviews: Users can add reviews and ratings for restaurants.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- npm or yarn
- PostgreSQL

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/subashrai02468/Restaurant-Finder-Yelp-Clone
```

2. **Set up the Database**

- Ensure PostgreSQL is installed and running on your machine.
- Create a new database for the project.
- Run the SQL scripts found in the `database` folder to set up the schema and populate it with initial data.

3. **Configure Environment Variables**

Copy the `.env.example` file to a new file named `.env`, and fill in your database credentials and other configurations.

4. **Install Dependencies**

For the server:

```bash
cd server
npm install
```

For the client:

```bash
cd client
npm install
```

5. **Start the Application**

Start the server:

```bash
cd server
npm start
```

In a new terminal, start the React client:

```bash
cd client
npm start
```

The React app should now be running on [http://localhost:3000](http://localhost:3000), and the server on [http://localhost:5000](http://localhost:5000).

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md] file for details.

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration from Yelp
- etc

```

