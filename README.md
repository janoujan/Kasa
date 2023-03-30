![alt text](https://user.oc-static.com/upload/2022/06/24/16560899769906_FR_811_P8_Banner-Kasa%20%281%29.png)

### Openclassroom Web Developer training: project 7: Kasa
### Create a real estate rental web application with React

## languages and tools

#### HTML5 / CSS3 / JS / React / React router / Styled-components     
     
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).     
     
I used [Styled-components](https://styled-components.com/docs) to keep styles in components for the ease to maintain and shareability         
   
I also used [react-router](https://reactrouter.com/en/main)    

## Scenario and requirements

Kasa is recruiting you as a freelance front-end developer to develop its new web platform.    
Kasa has been in the business of renting apartments between individuals for almost 10 years now.    
With more than 500 advertisements posted every day, Kasa is one of the leaders in the rental of apartments between individuals in France.    
    
The perfect opportunity for you to add a nice reference to your freelance portfolio!    
     
The Kasa site was coded more than 10 years ago in ASP.NET with significant legacy code.    
Laura, the CTO, therefore launched a total overhaul to move to a full stack in JavaScript with NodeJS on the back-end side, and React on the front-end side.    
Kasa also took the opportunity to order new models from its usual designer, who is freelancing.   
A big project for this year!    

A meeting is planned with the CTO later in the week, but so that you can familiarize yourself with the challenges of your mission, you will find the following summary in your mailbox:  

--------------------------------------------------------------------------------------------------------------------------------------

      Subject: Kasa site redesign brief   
      From: Laura    
      To: me    

      Hello,    
      Welcome to your first day!   
      We are really happy to have you among us!    
      You will be able to help us bring life to a site we have been working on for several months.   
      I prefer to put you in writing a few elements of context that will help you project yourself into your mission before our point on Thursday.    

      Your goal: Start the React project and develop the whole application, the React components, the React Router routes, following the Figma mockups (responsive!) and all the info I give you below.     
      And this with a quality code!    
           
      Back-end / data: The recruitment of the person in charge of the back-end has not been completed and will take longer than expected.    
      So, you will have to do without for the moment.     
      I have extracted the last 20 housing advertisements from the JSON file attached for you, so that you can build the corresponding Front.    
    
      Technical constraints: You will find Kasa's coding guidelines attached.         
     
      Well, I hope this little summary will have given you enough leads to calmly approach your first days with us.    
    
      Very good day to you!     

      Laura    

----------------------------------------------------------------------------------------------------------------------------------
 

Later that day, you receive an email from Paul, the designer, giving you more information about the design and functionality of the site:    

 
-------------------------------------------------------------------------------------------------------------------------------------
      Subject: Functionality and design   
      From: Paul    
      To: me    
    
      Hi,    
      Welcome among us !    
      Laura told me to brief you on the design of the new version of the site, so here is the key info.     

      Design    
      
      Here are the mockups on Figma for interface design.      
      I'm used to working with component logic on Figma; Sandra told me that it would make your work on React easier.       
      You will find all the resources you need directly in the model (logo, icons for components, etc.).       
      To do this, simply click on the desired resource and "Export" in the desired format.      
     
      Functional constraints      
     
      A few details on the features of the site:     
     
      For scrolling photos in the gallery (Gallery component):   
      If the user is at the first image and clicks on "Previous image", the gallery displays the last image.     
      Conversely, when the image displayed is the last in the gallery, if the user clicks on "Next image", the gallery displays the first image.     
      If there is only one image, the "Next" and "Previous" buttons do not appear.      
      The gallery must always remain the same height, that indicated on the Figma model.     
      The images will therefore be cropped and centered within the image frame.     

      Collapse: By default, Collapses are closed on page initialization.     
      If the Collapse is open, the user's click closes it.      
      Conversely, if the Collapse is closed, a click opens it.    
     
      Good luck with the development, I can't wait to see what it will give!    
     
      Paul     
---------------------------------------------------------------------------------------------------------------------------------

That's it, you have all the necessary information, you can start your development!       
## Coding Guidelines     

[coding guidelines](/Coding%2Bguidelines%2BKasa%2BFR.pdf)   

## Mocked Datas   
[Json file](/public/logements.json)   
## Model on Figma    
[model](https://www.figma.com/file/bAnXDNqRKCRRP8mY2gcb5p/UI-Design-Kasa-FR?node-id=3%3A0)
## What I learned

Initialize an app with Create React App     
Configure app page navigation with React Router    
Develop website interface elements using React components     




## Available Scripts

In the project directory, you can run:

### `yarn run start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `yarn run build`

complete "homepage": "[url to deploy]" in package.json if you don't deploy on root folder.    

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

### `yarn run deploy`

if you can't deploy on root folder don't forget to adapt    
"homepage": "[url to deploy]" in package.json    
added gh-pages package (https://www.npmjs.com/package/gh-pages) to ease deploiement on Github

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### `yarn run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
