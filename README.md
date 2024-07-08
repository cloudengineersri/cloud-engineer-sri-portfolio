# cloud-engineer-sri-portfolio
## [Video Series Link](https://www.youtube.com/watch?v=pGZvI6GCr2g&list=PLN0Th-4WgKrUVQlqa14mUDeymTW1luznW)
# [Creating an Angular Portfolio Website 01: Course Introduction](https://www.youtube.com/watch?v=pGZvI6GCr2g&list=PLN0Th-4WgKrUVQlqa14mUDeymTW1luznW&index=2)
this is based on the web series created by Software Engineering Skills for building Portfolio
### Home Page
<hr/>
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/1b1effae-9dc4-42c5-8877-ac4073aceb06">
<br/>
<hr/>

### Sample Projects
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/36b05380-0eb6-46ac-a099-b43a7d6f028f">
<br/>
<hr/>

### Filter Projects by Skills
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/cb3d45b0-5f1d-4b12-8273-56a35fa243ed">
<br/>
<hr/>

### Resume Download
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/c8ca88c4-f987-42f1-ac67-44f54e0cfa33">
<br/>
<hr/>

### Certification Section
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/a1a7733e-213a-4935-a536-55844c7e5b02">
<br/>
<hr/>

### Contact Page
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/6095d474-d0ef-4429-be3c-f44352651ff8">

# [Creating an Angular Portfolio Website 02: Setting up the Environment](https://www.youtube.com/watch?v=HQRIw2kdzOY&list=PLN0Th-4WgKrUVQlqa14mUDeymTW1luznW&index=3)
## VSCode

## Angular Extensions

### Angular Language Service
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/aa38ad96-2e70-428a-9809-9492e5d8cf75">

### Angular Snippets Version 13
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/5b81ac1d-c481-4653-9eb5-77a761a76004">

### Material Icon Theme
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/a211a9e6-9412-4af4-946b-3e2fa82e0e80">

#### Settings for Material Settings
   VSCode Settings ->  Seach String "Bracket" -> CheckMark "Editor - Bracket Pair Colorization"
                                              -> CheckMark "Editor - Guides: Bracket Pairs"
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/1892a101-eef3-48b9-ad73-8e90d43dc973">

#### Installation of Node Version & Angular CLI
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/7e65cf06-296a-4f24-b93c-e367b97e9aaa">

#### Verify Angular Version | using Angular 15
<img width="1616" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/eb11f2e2-010c-4fd2-9e2c-7a4e51470fd7">


# [Creating an Angular Portfolio Website 03: Creating the Project](https://www.youtube.com/watch?v=PSI4T8SHb0g&list=PLN0Th-4WgKrUVQlqa14mUDeymTW1luznW&index=3)

Verifying ng --version
<img width="1680" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/58443ab3-4e17-4d99-be1a-918745ae7e19">

Angular 15.2.4 & Nide 18.10.0
<img width="1680" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/5ea87be7-6078-455a-8552-ead6a95debdc">
Folder Webapps
Project Name: AngularPortfolioWebSite

command to create the project
```
npm install -g @angular/cli@15
ng new AngularPortfolioWebSite
```
output
![image](https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/4160e522-91a1-4c12-84b3-23230468ef54)

Angular Project will be created in WebApp/AngularPortfolioWebSite as shown in the screenshot.
Expand the project src/index.html
![image](https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/9f2bf861-0435-4bba-b3d1-dd011ac4327e)

 <app-root></app-root>
 "<app-root/>" is the entry point of the angular application.
 <img width="958" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/d4356606-74b4-46e6-aeb1-2199b5d6a8ae">

 To Start the angular application
 with in the folder type the command ng serve
 ```
ng serve
 ```
<img width="958" alt="image" src="https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/2f32a274-1bc4-4957-be7f-ecbab77819af">

look and feel of the angular app
![image](https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/d8c4a164-0b65-4661-9983-b91c10c9b450)

Commonly used commands
1. Generate New Angular Component
   
   ```
   ng generate component xyz
   ```
   
![image](https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/12a9f715-412e-4195-93c7-8cb735f613e1)

<hr/>
2. Add Material

```
ng add @angular/material
```
![image](https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/832d916e-3222-47f1-9462-2bc2255932e7)

<hr/>
3. Add PWA support
   
```
ng add @angular/pwa
```

![image](https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/6615196a-4def-4c33-8cd9-59f0af1cda92)
<hr/>

4.Add Dependency

```
ng add _____
```
![image](https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/2fe8ef71-50f1-4472-8d48-9349e8d1f67e)

5. Run and Watch Tests
```
ng test
```

![image](https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/7c867460-b164-4479-94b4-fb0257394a3a)
<hr/>
6. Build Production

```
ng build
```
![image](https://github.com/cloudengineersri/cloud-engineer-sri-portfolio/assets/174270053/1f4bea54-6dc4-4602-a16b-d32e83a65abd)
<hr/>
 





   
    











