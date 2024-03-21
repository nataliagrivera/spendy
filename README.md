
![spendy](https://github.com/nataliagrivera/spendy/assets/132513851/9313e480-2bc0-4478-bb75-bebb1fae83e5)


# Spendy

Spendy is a budget analyzer that aims to make itself accessible to users of varying financial knowledge, bolstered by a receipt scanning OpenAI GPT and a reward system that incentives repeat use of the web app.

This project was born out of me and my partner’s background in finance. We are currently employed by Banco Popular de Puerto Rico and it is thanks to them that we have partaken in the foundations program at Holberton Coding School. As a result of various meetings and talks, the budget analyzer idea was born due to an interest in bolstering this functionality inside Popular’s own MiBanco system. Due to time constraints, the project currently stands on its own, independent of the bank’s systems but serves as a template of what they would like to implement for their online services refresh.

Regarding Spendy, we have so far implemented a database with Firebase, where the expenses and income for each user are saved, all behind log-in implementation using the user’s Google account. Currently, we are in the process of implementing the receipt scanner by way of a GPT and the API to provide a reward/achievement system. 

Looking ahead, we're considering adding a receipt scanner to our project in the future. While creating and implementing a custom parser with OpenAI's GPT posed some significant challenges and limitations, prompting us to switch gears and work with Botpress for hosting our bot and leveraging OpenAI for assistance, we still see the potential in integrating the GPT down the line.

Regarding the minimum viable product (MVP), we're leaning towards leaving it as it is for now, serving as a temporary solution. Later on, we can circle back and focus on implementing the OpenAI GPT.

It's worth noting that this project is built on React JS, which brings its own set of challenges, particularly with elements of HTML being incorporated directly into JavaScript files instead of separate HTML files.

# Developers

Gabriel Castro- Full Stack engineer on Spendy, delving into learning how to leverage Firebase and React to create the spending analyzer. During my tenure at Holberton I've acquired knowledge in C, Python and JavaScript, among many other things. This has given me the foundation to be able to embark in attempting to develop this web app. Previous to Holberton, I studied Game Design, with a focus on C# development and environmental design by way of Blender, Unity and Unreal Engine. Going forward I hope to join a game development team or partake in web development. 

Natalia Rivera- Full Stack engineer and Project Manager on Spendy. Leveraging my skills in Reactjs to make a user friendly expense tracker. Graduated from Holberton Coding School’s project-based program. Learning Javascript, Html, CSS and API integration I was equipped with the skill set for this and future endeavors in Saas and Automation. 

# Technologies Used

React JS, CSS, Firebase, Botpress, OpenAI

# Mockups

![Spendy_expense tracker](https://github.com/nataliagrivera/spendy/assets/132513851/18882ce7-d7df-49d8-b437-acd188e6d189)

![receipts and achievements](https://github.com/nataliagrivera/spendy/assets/132513851/a3d0d190-3940-452a-ab11-99f9bde6ea4a)

![Chat bot examples](https://github.com/nataliagrivera/spendy/assets/132513851/378f2cc3-5be8-467a-9fe8-1138d1545b64)


# Risks

Technical Risks:

The primary technical risks involve potential issues with image recognition accuracy while scanning receipts, leading to incorrect data input. This could impact the accuracy of expense tracking and budgeting. To mitigate this, constant refinement and testing of the image recognition system are planned. Additionally, users will have the option to manually edit and verify scanned information to ensure accuracy.

Non-Technical Risks:

Non-technical risks include data security breaches that could compromise users' financial information. Safeguards include robust encryption protocols, regular security audits, and compliance with industry standards to ensure data protection. Moreover, user education on best practices for secure account management will be emphasized to prevent phishing or unauthorized access.
Additionally, potential market changes affecting spending habits might impact the app's effectiveness. Continuous user feedback and adapting to evolving financial trends will be essential strategies to counter such risks and ensure the app remains relevant and beneficial to users.

# Future Features

-Receipt scanner

-Spending alerts

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)



