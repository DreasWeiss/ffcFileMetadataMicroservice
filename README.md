# File Metadata Microservice
## [link to task](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/file-metadata-microservice)

### Task
Build a full stack JavaScript app that is functionally similar to this: https://file-metadata-microservice.freecodecamp.rocks. Working on this project will involve you writing your code using one of the following methods:

Clone this GitHub repo and complete your project locally.
Use our Replit starter project to complete your project.
Use a site builder of your choice to complete the project. Be sure to incorporate all the files from our GitHub repo.
If you use Replit, follow these steps to set up the project:

Start by importing the project on Replit.
Next, you will see a .replit window.
Select Use run command and click the Done button.
When you are done, make sure a working demo of your project is hosted somewhere public. Then submit the URL to it in the Solution Link field. Optionally, also submit a link to your project's source code in the GitHub Link field.
HINT: You can use the multer npm package to handle file uploading.

'api/fileanalyse'
```
{
  "name": "file 2023-03-27 in 21.05.52.png",
  "type": "image/png",
  "size": 115932
}
```

### Tests
- [x] You should provide your own project, not the example URL.
- [x] You can submit a form that includes a file upload.
- [x] The form file input field has the name attribute set to upfile.
- [x] When you submit a file, you receive the file name, type, and size in bytes within the JSON response.

#### Install Dependencies
```
git clone https://github.com/DreasWeiss/ffcFileMetadataMicroservice.git
cd fccFileMetadataMicroservice
npm i
touch .env
```
in .env file:
```
PORT=
```
You should input your data without spaces (ex. PORT=1234)
PORT - is the Preferred Port for Working Application

```
nodemon index.js
```
![final](./readmeImg/final.png)
![final](./readmeImg/cert.png)