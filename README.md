# In this task we train how to :
start uour express project.

Follow the steps :
npm install --save express - to install expess ;
npm install --save-dev nodemon - to install nodemon (we use it for auto restart project after yours changes);
Then in D:\Progects\Back-end\trainToCreateNodeJsProject\package.json in "scrips" add new fild "start": "nodemon app.js" ;
Now create app.js file;
In app.js file import or require 'express', create constant appropriate express(), choose your PORT, at the end use app with method listen wich takes PORS (you can add some anonimus func wich write in console some massage instance: () => console.log(`localhost:${PORT} listeting...`))