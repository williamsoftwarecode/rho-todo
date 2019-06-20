
# MEAN Stack Template

This is a Issue Tracker created based on the following websites: 

https://medium.com/codingthesmartway-com-blog/angular-6-mean-stack-crash-course-part-1-front-end-project-setup-and-routing-89bec8332cea

https://medium.com/codingthesmartway-com-blog/angular-6-mean-stack-crash-course-part-2-implementing-the-back-end-642567e16bb9

https://medium.com/codingthesmartway-com-blog/angular-6-mean-stack-crash-course-part-3-connecting-front-end-to-back-end-760e26e2c74d

https://medium.com/codingthesmartway-com-blog/angular-6-mean-stack-crash-course-part-4-completing-the-user-interface-94f2d4da3490


https://medium.com/@hellotunmbi/how-to-deploy-angular-application-to-heroku-1d56e09c5147

It is ready for deployment on Heroku through Git. 

## Configuration

The following files need to be configured before use: 
1. server.js (Database) - This app assumes MongoDB will be used as the default database. Configure the connection URI to the selected database. 
2. server.js (Routing) - Configure routes by specifying dist directory where Angular app will be built. 
3. issue.service.ts - Configure the URI to point to the website. 
4. package.json - Rename "name" accordingly.
