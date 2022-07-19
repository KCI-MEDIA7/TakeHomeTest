# Take Home Test (Job Page)


Welcome candidate and thank you for taking the time to complete the take-home challenge for our web developer position.

This should take around 4-6 hours. Once you have completed your solution, please reply with a link to a github repository and the website where your application has been deployed. In case the repository is private, please grant access by adding the github user pd-recruiting-frontend as a collaborator.

The goal of this challenge is to rebuild the jobs page for our company. Please clone this repository and submit it once you are finished.

Here are the rules of this challenge... you must:

    Build an application that displays a list of open job positions - grouped by teams (Product engineering, Go-to-market, etc).
    Display a loading state while the data is being fetched. You can use the CircularProgress component.
    Add select fields for location, teams and work type and store the active values by using the React useState hook. The dropdown options should be populated dynamically based on the available jobs. Once the user selects one or multiple options, the visible job postings should be filtered accordingly.
    Add a banner component to the top of the page. You can access the image here src/images/banner.jpeg.
    Make the layout fully responsive.

Important: You don't need to develop the jobs single page in this challenge. Instead, let the apply button link directly to the Lever page (e.g. Frontend Engineer). Furthermore, you can ignore fonts, footer and the header menu.
What we want to see

    Demonstrate use of React hooks and data management
    Demonstrate knowledge of component modularization
    Utilize CSS to create the layout of the page
    Create components as you feel is best suited for your solution

# Bonus points

Apply a new design to the jobs page 🙌
Styling Guidelines

We're using the Material UI design library behind the scenes to speed up the development process. You can apply global style overrides via the theme file src/theme/mui or use the sx property for individual components.

If you are more familiar with other styling methods such as CSS-in-JS libraries (emotion is installed) or CSS/SCSS stylesheets, it's totally fine to use those instead.

# Available Scripts

In the project directory, you can run:
npm start

Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.
npm build

Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!
