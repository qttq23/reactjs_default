1. create react

#create react app with typescript:
npx create-react-app <app_name> --template typescript
cd <app_name>
npm start

https://reactjs.org/docs/static-type-checking.html#typescript


#create react app:
npx create-react-app <app_name>
cd <app_name>
npm start

https://reactjs.org/docs/create-a-new-react-app.html#create-react-app


#add typescript to existing react app:
https://create-react-app.dev/docs/adding-typescript/#installation


2. add bootstrap UI
cd <app_name>
npm install react-bootstrap bootstrap

add stylesheet before using components:
at file index.tsx or index.js, add:
import 'bootstrap/dist/css/bootstrap.min.css';

https://react-bootstrap.github.io/getting-started/introduction/#css

using components:
https://react-bootstrap.github.io/getting-started/introduction/#importing-components


https://react-bootstrap.github.io/getting-started/introduction/#installation

3. production build
cd <app_name>
npm run build

https://reactjs.org/docs/optimizing-performance.html#create-react-app


4. optional, test production build
npm install --global http-server

cd <app_name>
http-server ./build --port 5000
