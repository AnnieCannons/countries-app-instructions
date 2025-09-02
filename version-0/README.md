# Countries App — Version 0 - Instructions

## 👋 Welcome!

Your challenge is to build a website with React.js that pulls country data from the `localData.js` file and displays it like the [Figma designs](https://www.figma.com/design/YuEMNteoQic0h6RRiYprpV/Countries-API-Project?node-id=1045-2&p=f&t=T2oSD2lU7TuxaG13-0).

## 🎯 Requirements for Version 0

In Version 0, you'll build a mobile-responsive React app that:

- Shows all countries on the Home page using a reusable CountryCard component
- Displays country data from the `localData.js` file 
- Is styled according to provided [Figma designs](https://www.figma.com/design/YuEMNteoQic0h6RRiYprpV/Countries-API-Project?node-id=1045-2&p=f&t=T2oSD2lU7TuxaG13-0)
- *Note: Deployment to Netlify is NOT required.

## 💎 Demo

Here's what the finished Version 0 will look like in the browser: https://countries-app-version-0.netlify.app

![Example of Version 0 project](https://github.com/user-attachments/assets/79094b58-6856-4491-8fa5-0a394f85f0b9)

## 🔗 Resources

- **Designs:** You will need to use this [Figma file](https://www.figma.com/design/YuEMNteoQic0h6RRiYprpV/Countries-API-Project?node-id=1045-2&p=f&t=T2oSD2lU7TuxaG13-0) for the designs
- **Style Guide:** Refer to the `style-guide.md` file for info about the color palette, fonts, and design.
- **Local Countries Data:** You will use the `localData.js` file to get the country data and flag images
- **Feeling stuck with React?** A solid grasp of the core concepts is key to building this project. If you need to brush up, try working through the [React Tic-Tac-Toe tutorial](https://react.dev/learn/tutorial-tic-tac-toe).

## 📖 Pages & Routes 

You will use `react-router` to set up the Routes for 3 pages: 
- Home page
- SavedCountries page
- CountryDetail page

Refer to [this react-router guide](https://docs.google.com/document/d/18jxCUA0bebCyYaIHy8aaKMgOQH4w5-b-iCGDWpV4K4M/edit?tab=t.hbxxe6vmm0fq#heading=h.snu4ai1ffrgi) to help you set up your pages, Routes, and Links. 

Even though you are setting up the Routes for all 3 pages, you only need to fully build out the Home page so that it displays the country data. You won't need to build out the SavedCountries page and the CountryDetail page until the Backend class starts. 

In addition, your App.jsx file should render a header with two links: 

![Header of Countries API Project](https://github.com/user-attachments/assets/2a6311a4-70a1-48a5-8f9a-3b44bbad6a3e)

- When the user clicks on "Where in the World?", they should be routed to the Home page
- When the user clicks on "Saved Countries", they should be routed to the SavedCountries page

## ⚙️ Components 

Your Version 0 should have the following component: CountryCard. 

### CountryCard 

This component displays data for a single country 

![CountryCard component which displays data for a single country](https://github.com/user-attachments/assets/78528aa5-655c-4b2c-add7-319bfde63143)


## 🚀 Roadmap: Step-by-step guide to building your project

### ⚙️ Fork & Clone the Github repo 
1. Fork the [countries-app-fall-2025 repo](https://github.com/AnnieCannons/countries-app-fall-2025/tree/main). Use this [fork and clone guide](https://docs.google.com/document/d/18jxCUA0bebCyYaIHy8aaKMgOQH4w5-b-iCGDWpV4K4M/edit?tab=t.55gk3qetux2a#heading=h.wbbot8ebr58a) to help you.
2. Open up the Terminal on your computer.
3. Clone your forked `countries-app-fall-2025` Github repo into your `dev` folder. 
4. Your newly cloned `countries-app-fall-2025` folder contains a `version-0` folder. Open up the `version-0` folder in VS Code.

---

### ⚙️ Review your `version-0` starter files 

Your version-0 folder is a **blank React project** that’s been lightly customized for you. It’s basically what you’d get from creating a new React project with Vite — but we’ve cleaned up the boilerplate and added one extra file: localData.js.

Before writing any code, take a few minutes to explore what’s already there. Knowing your starting point will help you feel confident as you build. Pay special attention to these files:
1. `localData.js` — Contains the array of country objects you’ll display on the Home page
3. `README.md` – Contains the link to the `version-0` instructions
4. `package.json` – Lists your dependencies (the tools your app needs) and project info
7. `.gitignore` – Tells Git which files and folders _not_ to track (to keep certain data private) 
13. 📂 `src` – The heart of your app — this is where all your React code will live!

🧠 If you’re curious about what each of these files does (and why they matter), check out the [Demystifying Vite & React Folder Structure guide](https://docs.google.com/document/d/18jxCUA0bebCyYaIHy8aaKMgOQH4w5-b-iCGDWpV4K4M/edit?tab=t.v30xhdl91zel). 

---

### ⚙️ Run your code for the first time 

To see how your project looks in the browser, let's run your code! 

1. In the terminal on VS Code, make sure you're in the `version-0` folder. Use `pwd`, `ls`, and `cd` commands to navigate into the `version-0` folder.
2. In the `version-0` folder, run `npm install`. This will install all the libraries and dependencies needed to run your project, such as React.
3. Then run `npm run dev`. You will see a URL in the terminal output that looks something like `http://localhost:5173/`. Visit that URL in the browser to see how your project currently looks! 

---

### ⚙️ Set up files & folder structure in VS Code 
1. In the `src` folder, create a `pages` folder and a `components` folder
2. In the `pages` folder, set up each page by making these 3 files: 
   - `Home.jsx`
   - `SavedCountries.jsx`
   - `CountryDetail.jsx`
4. In the `components` folder, make a file called `CountryCard.jsx`
5. Add, commit, and push your code to Github. 
6. By now, your project's folder structure should look like this. Double check to make sure you have all the right files and folders before moving on:
   
![image](https://github.com/user-attachments/assets/19d923f4-1861-404d-9d1b-819951f99d06)

---

### ⚙️ Set up Routes with `react-router`
Refer to this [react-router guide](https://docs.google.com/document/d/18jxCUA0bebCyYaIHy8aaKMgOQH4w5-b-iCGDWpV4K4M/edit?tab=t.hbxxe6vmm0fq#heading=h.snu4ai1ffrgi) as you do the following steps:
1. In the terminal, in your `version-0` folder, install the `react-router` package using the command `npm install react-router`. 
2. In App.jsx file, set up Routes for 3 pages: Home page, SavedCountries page, and CountryDetail page.
3. In App.jsx, render a header that contains two links:
     - "Where in the world?" should link to the Home page
     - "Saved Countries" should link to the SavedCountries page
4. In App.css, style the header 
5. Add, commit, and push your code to Github.

---

### ⚙️ In the Home page, display localData from `localData.js` file as CountryCard components
1. In `App.jsx`, import the `localData.js` file. This file contains an array of country objects. It's located in the `version-0` folder. 
2. In `App.jsx`, pass the data to the `Home` component using a prop called `countriesData`. 
   ```
   <Home countriesData={dataFromLocalFile} />
   ```
3. In `Home.jsx`, use the `countriesData` prop to render a list of `CountryCard` components — one for each country.
4. In `App.css`, style the `Home` and `CountryCard` components to match the Figma designs.
5. Add, commit, and push your code to Github. 

---

### ⚙️ Clean and Comment your code
1. Clean up your code by renaming confusing variables, removing unused code, and organizing your logic. Your code should read like a newspaper: clear, easy to follow, and understandable at a glance.
2. Comment your code generously — Future You will thank you. You’ll be building on top of this project over the next 3 months, so help yourself out by writing clear, helpful comments that explain what your code is doing. Trust us, it will save you time and confusion later.
3. Add, commit, and push your code to Github. 

---

### ⚙️ Submit to Canvas, and prepare for your demo 
1. Submit the Github repo link to Canvas.
2. Be ready to demo what you've got on Day 1 of Backend — complete or not. We want to see your thinking and progress! 💡 

---

### 🌟 Stretch Goals (optional — only do these if you have completed _all_ of the above steps)

Finished all the steps above? Amazing!   
Get a head start your Version 1 by tackling these next challenges:
1. 🏆 Create the form on the SavedCountries page based on this [Figma Design for the Form](https://www.figma.com/design/YuEMNteoQic0h6RRiYprpV/Countries-API-Project?node-id=1-329&t=eKfO5eJcdQC03CrI-4)
2. 🏆 Sort the countries on the Home page in alphabetical order
3. 🏆 Deploy your version-0 folder to Netlify via your Github repo. In your Netlify Deploy settings, you will need to specify the folder that you want to deploy. Check out [this guide to help you](https://docs.google.com/document/d/18jxCUA0bebCyYaIHy8aaKMgOQH4w5-b-iCGDWpV4K4M/edit?tab=t.jnwta4jrhylr#heading=h.scmsi7a6s9yz).
