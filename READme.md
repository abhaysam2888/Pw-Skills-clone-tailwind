
# Pw Skills clone using Tailwind CSS

Tailwind CSS refers to the utilization of the framework's more intricate features and techniques to create highly customized and complex user interfaces. Some key aspects of advanced Tailwind CSS include:

- Customization:

- Component Styling:

- Responsive Design:

- Extended Utility Classes:

Creating a PW Skills clone using Tailwind CSS and HTML is a project that involves replicating the design of the PW Skills website. Utilizing HTML, you would structure the layout and content of the clone, ensuring proper semantic markup. By leveraging Tailwind CSS's utility classes, you can easily style the clone and closely match the visual appearance of the original website. Responsive design can be achieved using Tailwind CSS's responsive utility classes to ensure a seamless experience across different screen sizes. By closely referencing the original PW Skills website and incorporating custom CSS if needed, you can create a clone that emulates the look and feel of the original site using these technologies.



## Tech Stack

- HTML, Taliwind CSS


## Features
- Fully Resposive
- 100% made with Tailwind CSS
- Attractive design 
## Installation

Install Tailwind CSS

```bash
    Step 1:- open Terminal and run (npx tailwindcss init).
```
```bash
    Step 2:- Add folder dist and under a folder a file #output.css and code file name ex-index.html
```
```bash
   step 3:- Add another folder src and under a folder a file #inputput.css
```
```bash
  step 4:- Add codes in input.css file

@tailwind base;
@tailwind components;
@tailwind utilities;
```
```bash
  step 5:- write .dist/*.html in config.js file

module.exports = {
  content: [".dist/*.html"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
```bash
  step 6:- All done jus run a code in terminal 

npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```
```bash
  step 7:- Add <link rel="stylesheet" href="output.css"> in html file
```
```bash
   Note:- You must install node js to run this programm
```


    
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/abhaysam2888?tab=repositories)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhay-verma-821699274/)


