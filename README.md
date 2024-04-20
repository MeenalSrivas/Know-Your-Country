                                                                                 KNOW-YOUR-WORLD


//This is a challenge file that is availbale on Front-end mentor.Can get the statring file of this project there - 
https://www.frontendmentor.io/challenges/rest-countries-api-with-color-theme-switcher-5cacc469fec04111f7b848ca

HOW TO RUN "KNOW-YOUR-WORLD" application in your system:
1. Clone the repository from the code button using the SSH key url.
2. On the VSCODE terminal( bash as a default shell) run git clone git@github.com:MeenalSrivas/Know-Your-Country.git.
3.  Once you clone the repo, install the required npm packages for this i.e - [npm install]
4.  Then start the Angular application by [ ng serve]

API Used in this  application - Rest-Countries-api 
link - https://restcountries.com/#api-endpoints-using-this-project

HOW DID I INTEGRATE REST-Countries-Api in the project:
1. First of all, I have installed HTTPClient Module in my angular porject.
2. Created a service to handle HTTP requests to the Rest-Sountries-Api.
3. The implement the service. Modify the country.component.ts file. this service contains a method "getCountries" to the Rest-County-Api endpoint.
4. Inject CountryService into a component where u want to fetch the country information.
5. Use the fetched data in your component template(home.component.html).
    
