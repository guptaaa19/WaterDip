<<<<<<< HEAD
<<<<<<< HEAD
# Hotel Booking Dashboard
=======
# Hotel Booking Dashboard Assignment
>>>>>>> 34cc3806127aa459d34f92a0776bfb5eebf8f676

This project is a hotel booking dashboard developed using React.js alongside TypeScript and incorporating Tailwind CSS. The dashboard’s focus is displaying booking information in charts and it allows users to manipulate the data retained by therefore selecting certain dates. For the purpose of this project, data from a CSV file, provided by the customer has been used with the help of **PapaParse** in order to obtain usable data.

## Features

- Charts: 
  - Time Series Chart: This presents a graph that shows the number of visitors (Adulst & children plus babies) over the period of one day.
  - Column Chart: A visitors column chart depicting a number of visitors from different countries.
  - Sparkline Charts: In these charts, children and adult visitors’ sparklines are shown separately.

- Date Range Filter: In addition to this, users are allowed to specify a date range and accordingly all the charts present on the dashboard change to the given dates.

## Requirements

- Frontend: React.js (with TypeScript)
- Styling: Tailwind CSS
- Charts: ApexCharts
- Data Parsing: PapaParse (for parsing CSV data)
- CSV Data: Static CSV file (`hotel_bookings_1000.csv`) kept in the `public` directory.

## Directory Structure

/src ├── /components │ ├── Dashboard.tsx │ ├── TimeSeriesChart.tsx │ ├── ColumnChart.tsx │ ├── SparklineChart.tsx ├── App.tsx ├── index.tsx └── index.css (Tailwind CSS)

/public ├── hotel_bookings_1000.csv └── index.html


### Prerequisites

- Node.js (version >= 14)
- npm or yarn

### Installation

1. Clone the repository:

<<<<<<< HEAD
   ```bash
=======
bash
>>>>>>> 34cc3806127aa459d34f92a0776bfb5eebf8f676
   git clone <repository-url>
2. Go to the address of the project's root folder:


cd hotel-booking-dashboard
3. Install required packages:


npm install
Running the Project
<<<<<<< HEAD
=======
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
>>>>>>> 275bf55 (Initialize project using Create React App)
=======
>>>>>>> 34cc3806127aa459d34f92a0776bfb5eebf8f676
