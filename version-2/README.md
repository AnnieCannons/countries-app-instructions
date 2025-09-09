# Countries App - Version 2 — Instructions

## 👋 Welcome!

Version 2 builds on the Version 1 of the Countries API app by saving data in the browser using Local Storage. Your application will now remember:
- Form data: a user's profile information when they submit the form 
- Saved Countries data: which countries the user has saved
- Country Count data: How many times each country has been viewed

By storing persistent data, your app will become more personal, dynamic, and interactive!

## 🎯 Requirements for Version 2

Add functionality to store the following data in Local Storage: 

1. **Form data**
    - As a user, when I submit the form, my data should be stored in Local Storage.
    - As a user, if I have already submitted the form, I should see "Welcome, [user name]!" above the Form on the Saved Countries page. 
2. **Saved Countries data**
    - As a user, on my Saved Countries page, I should be able to see all of the Saved Countries.
    - As a user, when I click the Save button in an individual country's page, I should be able to see that country's card in my Saved Countries page
    - A country cannot be saved twice. If I try to save a country that has already been saved, then nothing will happen. 
3. **View Count data** 
    - As a user, when I open a country's page, I should be able to see how many times the user has viewed this country.
    - Every time I view a country's page, its view count should go up by 1.
  
## 💎 Demo

Here's what the finished Version 2 will look like in the browser: https://countries-app-version-2.netlify.app/

<img width="790" height="531" alt="image" src="https://github.com/user-attachments/assets/7dea0cdf-2654-4571-a895-51ec3efbf489" />


## 🔗 Resources

- **Figma Designs:** Check out the [Figma designs](https://www.figma.com/design/YuEMNteoQic0h6RRiYprpV/Countries-API-Project?node-id=1404-20) to see how data should be rendered to the page. 
- **Local Storage guide on freeCodeCamp:** Learn how to use Local Storage via [this tutorial on freeCodeCamp](https://www.freecodecamp.org/news/use-local-storage-in-modern-applications/)
- **Local Storage demo on Youtube:** [This video](https://www.youtube.com/watch?v=AUOzvFzdIk4) gives a quick example of using Local Storage in Javascript
- **API:** You will use the [REST Countries API](https://restcountries.com) to get the country data and flag images

## 🚀 Roadmap: Step-by-step guide to building Version 2
Make sure you've finished Version 1 before moving on with the following steps.

### Project Setup: Copy your files over 
1. Duplicate your `version-1` folder
2. Rename the duplicated folder as your `version-2` folder
3. Push your code to Github! You will use your `version-1` code as the starting point for your `version-2`.

### 🎯 Milestone: Pseudo-Code
1. In your `version-2` folder, create a `pseudo-code.txt` file. Copy over the contents of [this template](https://github.com/AnnieCannons/countries-app-instructions/blob/main/version-2/pseudo-code.txt) into your empty file. 
2. Answer all of the questions in your `pseudo-code.txt` file to plan out how you will tackle storing and retrieving the 3 pieces of data to Local Storage.
3. Push your code to Github
4. Submit the link to your `pseudo-code.txt` file to the Canvas milestone assignment. 

### Deploy project to Netlify
1. Deploy your `version-2` folder to [Netlify](https://www.netlify.com/) via your Github repo. In your Netlify Deploy settings, you will need to specify which version you want to deploy. Check out [this deployment guide to help you](https://docs.google.com/document/d/18jxCUA0bebCyYaIHy8aaKMgOQH4w5-b-iCGDWpV4K4M/edit?tab=t.jnwta4jrhylr#heading=h.scmsi7a6s9yz).

### 🎯 Milestone: Form data
1. Review your pseudo-code for storing & retrieving this piece of data. 
2. Work on storing Form data in Local Storage. When the user submits the form, the form data should be stored in Local Storage.
3. Work on retrieving Form data from Local Storage. If the user has already submitted the Form, display "Welcome, {user}!" instead of the Form.
4. Comment the code you wrote so that Future You can understand it later.
5. Push your code to Github!
6. Submit your Github repo link and Netlify link to the Canvas milestone.

### 🎯 Milestone: Saved Countries data
1. Review your pseudo-code for storing & retrieving this piece of data. 
2. Work on saving a country in Local Storage. When the user saves a country, store the country's data in Local Storage.
3. Make sure that a country cannot be saved twice. If you try to save a country that's already been saved, nothing should happen. 
4. Work on retrieving the saved countries data from Local Storage, so that they show on the Saved Countries page. 
5. Don’t forget to comment your logic as you go!
6. Push your code to Github!
7. Submit your Github repo link and Netlify link to the Canvas milestone.

### 🎯 Milestone: Country Counts data 
1. Review your pseudo-code for storing & retrieving this piece of data. 
2. When the user views a country's CountryDetail page, that country's view count should go up by 1, and that view count should be rendered on the page. 
3. If you notice your view count is going up by 2 instead of 1, try this trick:  Update your main.jsx file by removing the `StrictMode` component that's wrapping your app. It was included by default in Vite’s setup to help catch bugs, but it causes React to render components twice in development, which is why your view count goes up by 2 instead of 1. Simply removing `StrictMode` from `main.jsx` will make your your view count increment correctly.
4. Don’t forget to comment your logic as you go!
5. Push your code to Github!
6. Submit your Github repo link and Netlify link to the Canvas milestone.

### Test everything
1. Test that all 3 pieces of data are being stored and retrieved properly. Make sure everything is working. Double check that you completed all of the project requirements (listed above). 

### Clean and Comment your code 
1. Clean up your code by renaming confusing variables, removing unused code, and organizing your logic. Your code should read like a newspaper: clear, easy to follow, and understandable at a glance.
2. Comment your code generously — Future You will thank you. You’ll be building on top of this project over the next 3 months, so help yourself out by writing clear, helpful comments that explain what your code is doing. Trust us, it will save you time and confusion later.
3. Push your code to Github!

### ⚙️ You're done with Version 2! 
1. Push your code to Github
2. Submit the Github repo link and Netlify deployment link to Canvas.

### Stretch Goals (optional — only do these if you have completed _all_ of the above steps)

Finished all the above steps? Fantastic! 🎉

Here are a few next-level challenges to tackle:
1. 🏆 On the Saved Countries page, add an “Unsave” button so the user can remove a country from their saved list.
2. 🏆 Turn the Save button into a red heart ❤️ when the country has been saved, or a grey heart 🩶 when the country has not been saved. 
3. 🏆 Add a “Submit again” button to the Form so the user can re-submit if they’d like to.






