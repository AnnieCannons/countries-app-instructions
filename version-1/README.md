# Countries App — Version 1 - Instructions

## 👋 Welcome!

Your challenge is to build a website with React.js that pulls country data from the [REST Countries API](https://restcountries.com) and displays it like the [Figma designs](https://www.figma.com/design/YuEMNteoQic0h6RRiYprpV/Countries-API-Project?node-id=0-1).

## 🎯 Requirements for Version 1

In Version 1, you'll build a mobile-responsive React app that:

- Displays country data from the [REST Countries API](https://restcountries.com), or from `localData.js` file as a backup when the API is down
- Is styled according to provided [Figma designs](https://www.figma.com/design/YuEMNteoQic0h6RRiYprpV/Countries-API-Project?node-id=0-1)
- Uses `react-router` to navigate between Home, SavedCountries, and CountryDetail pages
- Deployed to a Netlify URL
- As a user, when I view the Home page, I can see all countries with API data displayed about each country
- As a user, when I view the Guestbook page, I can submit a form with my profile information

## 💎 Demo

Here's what the finished Version 1 will look like in the browser: https://countries-app-version-1.netlify.app/

![Example of what Version 1 of Countries App should look like](https://github.com/user-attachments/assets/79094b58-6856-4491-8fa5-0a394f85f0b9)


## 🔗 Resources

- **Designs:** You will need to use this [Figma file](https://www.figma.com/design/YuEMNteoQic0h6RRiYprpV/Countries-API-Project?node-id=0-1) for the designs
- **Style Guide:** Refer to the `style-guide.md` file for info about the color palette, fonts, and design.
- **API:** You will use the [REST Countries API](https://restcountries.com) to get the country data and flag images
- **Local Countries Data:** You will use the `localData.js` file to get the country data and flag images as backup when the API isn't working
- **Feeling stuck with React?** A solid grasp of the core concepts is key to building this project. If you need to brush up, try working through the [React Tic-Tac-Toe tutorial](https://react.dev/learn/tutorial-tic-tac-toe).

## 📖 Pages & Routes 

You will use `react-router` to set up the Routes for 3 pages: 
- Home page
- Guestbook

Refer to [this react-router guide](https://docs.google.com/document/d/18jxCUA0bebCyYaIHy8aaKMgOQH4w5-b-iCGDWpV4K4M/edit?tab=t.hbxxe6vmm0fq#heading=h.snu4ai1ffrgi) to help you set up your pages, Routes, and Links. 

In addition, your App.jsx file should render a header with two links: 

![Header of Countries App](https://github.com/user-attachments/assets/2a6311a4-70a1-48a5-8f9a-3b44bbad6a3e)

- When the user clicks on "Where in the World?", they should be routed to the Home page
- When the user clicks on "Guestbook", they should be routed to the Guestbook page

## ⚙️ Components 

Your Version 0 should have the following component: CountryCard. 

### CountryCard 

This component displays data for a single country 

![CountryCard component which displays data for a single country](https://github.com/user-attachments/assets/78528aa5-655c-4b2c-add7-319bfde63143)


## 🚀 Roadmap: Step-by-step guide to building your project
Make sure you've finished Version 0 before moving on with the following steps.

### ⚙️ Fork & Clone the Github repo 
1. Fork the [countries-app repo](https://github.com/ac-backend/countries-app/tree/main). Use this [fork and clone guide](https://docs.google.com/document/d/18jxCUA0bebCyYaIHy8aaKMgOQH4w5-b-iCGDWpV4K4M/edit?tab=t.55gk3qetux2a#heading=h.wbbot8ebr58a) to help you.
2. Open up the Terminal on your computer.
3. Clone your forked `countries-app` Github repo into your `dev` folder. 
4. Your newly cloned `countries-app` folder contains a `version-1` folder. Open that folder in VS Code.

### ⚙️ Review your `version-1` starter files 

Your version-1 folder is a **blank React project** that’s been lightly customized for you. It’s basically what you’d get from creating a new React project with Vite — but we’ve cleaned up the boilerplate and added one extra file: `localData.js`.

Before writing any code, take a few minutes to explore what’s already there. Knowing your starting point will help you feel confident as you build. Pay special attention to these files:
1. `localData.js` — Contains the array of country objects you’ll display on the Home page
3. `README.md` – Contains the link to the `version-0` instructions
4. `package.json` – Lists your dependencies (the tools your app needs) and project info
7. `.gitignore` – Tells Git which files and folders _not_ to track (to keep certain data private) 
13. 📂 `src` – The heart of your app — this is where all your React code will live!

🧠 If you’re curious about what each of these files does (and why they matter), check out the [Demystifying Vite & React Folder Structure guide](https://docs.google.com/document/d/18jxCUA0bebCyYaIHy8aaKMgOQH4w5-b-iCGDWpV4K4M/edit?tab=t.v30xhdl91zel). 

### ⚙️ Run your code for the first time 

To see how your project looks in the browser, let's run your code! 

1. In the terminal on VS Code, make sure you're in the `version-1` folder. Use `pwd`, `ls`, and `cd` commands to navigate into the `version-1` folder.
2. In the `version-1` folder, in the terminal, run `npm install`. This will install all the libraries and dependencies needed to run your project, such as React.
3. Then run `npm run dev`. You will see a URL in the terminal output that looks something like `http://localhost:5173/`. Visit that URL in the browser to see how your project currently looks!

### ⚙️ Set up files & folder structure in VS Code 
1. In the `version-1/src` folder, create a `pages` folder and a `components` folder
2. In the `pages` folder, set up each page by making these 3 files: 
   - `Home.jsx`
   - `Guestbook.jsx`
4. In the `components` folder, make a file called `CountryCard.jsx`
5. Add, commit, and push your code to Github. 
6. By now, your project's folder structure should look like this. Double check to make sure you have all the right files and folders before moving on:
   
![image](https://github.com/user-attachments/assets/19d923f4-1861-404d-9d1b-819951f99d06)

### ⚙️ Set up Routes with `react-router`
Refer to this [react-router guide](https://docs.google.com/document/d/18jxCUA0bebCyYaIHy8aaKMgOQH4w5-b-iCGDWpV4K4M/edit?tab=t.hbxxe6vmm0fq#heading=h.snu4ai1ffrgi) as you do the following steps:
1. In the terminal, in your `version-0` folder, install the `react-router` package using the command `npm install react-router`. 
2. In App.jsx file, set up Routes for 3 pages: 
      - Home page
      - Guestbook page
  
### ⚙️ Render a header in `App.jsx`
3. In App.jsx, render a header that contains two links:
     - "Where in the world?" should link to the Home page
     - "Guestbook" should link to the Guestbook page
4. In App.css, style the header 
5. Add, commit, and push your code to Github.

### ⚙️ In the Home page, display localData from `localData.js` file as CountryCard components
1. In `App.jsx`, import the `localData.js` file. This file contains an array of country objects. It's located in the `version-0` folder. 
2. In `App.jsx`, pass the data to the `Home` component using a prop called `countriesData`. 
   ```
   <Home countriesData={dataFromLocalFile} />
   ```
3. In `Home.jsx`, use the `countriesData` prop to render a list of `CountryCard` components — one for each country.
      - **Note:** When rendering the country name, please always use the _common_ name instead of the official name.
4. In `App.css`, style the `Home` and `CountryCard` components to match the Figma designs.
5. Add, commit, and push your code to Github. 

### 🎯 Milestone: Build Form on the SavedCountries Page
1. In `SavedCountries.jsx`, create the Form so that the user can submit their profile information (name, email, country, and bio). 
2. Style the Form according to the Figma designs
3. Push your code to Github!
4. Submit your Github repo link and Netlify link to the Canvas milestone. 

### 🎯 Milestone: Fetch and Display API Data
The goal of this milestone is to fetch the countries data from the API in your `App` component, pass the data down as a prop to your `Home` component, and render the data on the Home page as `CountryCard` components. 

1. In `App.jsx`, write a function that fetches countries data from the [REST Countries API](https://restcountries.com) and saves the data in a state variable. 
    - Use this API URL to fetch the data: 
      https://restcountries.com/v3.1/all?fields=name,flags,population,capital,region,cca3,borders 
2. Call the function on page load using the `useEffect` hook.
3. Pass the countries API data down as a prop from the App component into the 3 pages: Home, SavedCountries, and CountryDetail
4. Display countries data from API call on the Home page, instead of displaying data from `localData.js`
5. Push your code to Github!
6. Submit your Github repo link and Netlify link to the Canvas milestone. 

### ⚙️ Deploy project to Netlify
1. Deploy your `version-1` folder to [Netlify](https://www.netlify.com/) via your Github repo. In your Netlify Deploy settings, you will need to specify which version you want to deploy. Check out [this deployment guide to help you](https://docs.google.com/document/d/18jxCUA0bebCyYaIHy8aaKMgOQH4w5-b-iCGDWpV4K4M/edit?tab=t.jnwta4jrhylr#heading=h.scmsi7a6s9yz).

### ⚙️ Clean and Comment your code 
1. Clean up your code by renaming confusing variables, removing unused code, and organizing your logic. Your code should read like a newspaper: clear, easy to follow, and understandable at a glance.
2. Comment your code and explain what your code is doing. Future You will thank you.
3. Push your code to Github!

### ⚙️ Submit to Canvas
1. Push your code to Github
2. Submit the Github repo link and Netlify deployment link to Canvas.

### Stretch Goals (optional — only do these if you have completed _all_ of the above steps)

Finished all the above steps? Fantastic! 

Here are a few next-level challenges to tackle:
1. 🏆 Sort the countries on the Home page in alphabetical order
2. 🏆 Create the search bar on the Home page
3. 🏆 Filter countries by region on the Home page
4. 🏆 Show Bordering countries on Country Detail page
5. 🏆 Light & Dark Mode on all pages

You can find the [designs for all of these Stretch Goals in the Figma file.](https://www.figma.com/design/YuEMNteoQic0h6RRiYprpV/Countries-API-Project?node-id=1032-2&p=f&t=63CpCVNtkWIFmrAK-0) 
