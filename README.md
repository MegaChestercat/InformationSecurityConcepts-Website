# **Information Security Concepts Landing Page**
### *By Mario Sánchez, Ángel Moreno, & Andrés Cabral*

## **Content**
- [Introduction](#intorduction)
- [Requirements](#requirements)
- [Steps](#steps)
- [Project Structure](#project-structure)

## **Introduction**
This project has the objective of providing a digital platform where any user (from the common one to professionals or companies) can get to learn and gather all the most important concepts of cybersecurity so they can get to identify what kind of issues or threats are dealing with or could pass through and generate actions as a rection or prevention.

Because this project was made by making use of Nuxt Framework, it is necessary to follow the following requirements and steps.

## **Requirements**
- NodeJS ([Download it here](https://nodejs.org/en))
- Visual Studio Code ([Download it here](https://code.visualstudio.com/))
- Vue - Official extension ([Find it here](https://marketplace.visualstudio.com/items?itemName=Vue.volar))
- Vue VSCode Snippets extension ([Find it it here](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets))

> **Note:** If you are using VSCode integrated terminal it could possibly be needed to set the correct execution policy so certain commands can be used, if the terminal gets to throw an error about permissions. Check the following links to know more about retrieving and setting the execution policies of your device: [Execution Policy](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.4), [Set Execution Policy](https://learn.microsoft.com/es-es/powershell/module/microsoft.powershell.security/set-executionpolicy?view=powershell-7.4), [Get Execution Policy](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.security/get-executionpolicy?view=powershell-7.4)

## **Steps**

1. Clone or download the repository onto a computer/laptop
2. Open the root folder and use the cd command as it will be set:

```bash
cd website
```

> **Alternative:** Open directly the folder "website"

3. In the terminal it will be necessary to execute the following command so all packages used and also the ones any project made by using Node needs:

```bash
npm install
```

4. Finally, in order to run the website locally it is important to execute the following command, that will allow the website execution in *developer mode*.

```bash
npm run dev
```

## **Project Structure**
When you open the project you will see multiple folders with files in it, but the one where you can find the content of the website is the folder called "pages" where there is located all the view files that conform the pages of the website. A view made in Nuxt or View has normally the following main tags:

- template. It contains the HTML of your view. Because the project is using Vuetify framework too, besides HTML tags it is possible to make use of the tags/component Vuetify offers, including the way components can be customized.
- script (*optional*). It contains the possible JavaScript content of your view.
- style scoped (*optional*).  It contains the CSS of the view and by using the *scoped* argument, it means it will only be seen in that exact page, while for others you will need to set you own CSS.

The other element that can be useful when working with this project is the layouts folder where there are contain the view or view that could be used in most of the pages of your website. When the file has the name *default.vue*, then it means Nuxt will apply it to your website in all the pages, unless it is specified another one or none manually inside of that particular page or group of pages files.

The *assets* folder contains all the images that were used on the webiste, unless they were retrieved from another website, through a link.


With this information you have all what it is needed to understand about how to set up and run this project, in addition about the main structure of this Nuxt project and where the actual content and visual elements are located. For any doubt about its use you can contact any of the developers involved in this project.

- [Mario Sánchez](https://github.com/MegaChestercat)
- [Ángel Moreno](https://github.com/Engel02)
- [Andrés Cabral](https://github.com/AndresCabralTB)




