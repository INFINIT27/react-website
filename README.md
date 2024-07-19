# react-website
A website using React and Vite

To run the code, first you will need to install the following dependencies:

- react-router-dom
- react-icon
- axios
- jwt-decode

To install a dependency, you can use the command *npm install <dependency_name>*

To create a new build, run the command *npm run build* and a new folder named *dist* should appear in your project. From there, you can export it as a folder and use the *index.html* file as the index of your deployment. For example, you can then deploy it to an AWS S3 bucket using the command 

*aws s3 sync dist/ s3://bucket-name* 

after you have set up the aws command in your CLI.