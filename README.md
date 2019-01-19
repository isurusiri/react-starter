# This is React Starter ⚛️  

<div align="center">
  <a href="https://github.com/webpack/webpack">
    <img  width="100" height="100" src="https://arcweb.co/wp-content/uploads/2016/10/react-logo-1000-transparent.png" />
    <img width="100" height="100" src="https://prettier.io/icon.png" />
    <img widht="100" height="100" src="https://eslint.org/img/logo.svg" />
    <img widht="100" height="100" src="http://pluspng.com/img-png/airbnb-logo-png-png-ico-512.png" />
    <img widht="100" height="100" src="https://visual-regresion-testing.firebaseapp.com/parceljs.c11a4bd0.png" />
    <img widht="100" height="100" src="https://avatars3.githubusercontent.com/u/22247014?s=400&v=4" />
    <img widht="100" height="100" src="https://github.com/webpack/media/blob/master/logo/icon.png" /?
  </a>
</div>

And it contains the minimal boilerplate code that you want to jump start any react project.  

##### What's included?  
- [ReactJS](https://reactjs.org/)  
- [React DOM](https://reactjs.org/docs/react-dom.html)  
- [Prettier](https://prettier.io/)
- [Eslint](https://eslint.org/)    
- [AriBnB styling guide](https://github.com/airbnb/javascript)
- [jsx A11y](https://github.com/evcohen/eslint-plugin-jsx-a11y)  
- [Parcel](https://parceljs.org/)  
- [Yarn](https://yarnpkg.com/en/)  
- [Webpack](https://webpack.js.org/)

##### How to get started:
1. Clone this repo using `https://github.com/isurusiri/react-starter.git` and `cd react-starter`.  
2. Choose between Parcel and Webpack by refering below [>>](https://github.com/isurusiri/react-starter/tree/build-with-webpack#choose-between-parcel-and-webpack)
3. Install dependencies using `yarn`.  
4. Make changes inside `/src` directory.  
5. Additionally enable format on save in VS Code using, 
```javascript
{
  "prettier.requireConfig": true,
  "editor.formatOnSave": true
}
```  

##### Choose between Parcel and Webpack  
If you are just starting up the project or it doesn't require any custome build steps, then Parcel is enough. If you want to take control over your application's build process then the Webpack is what you are looking for.   

###### Checkout parcel
```
$ git fetch
$ git checkout build-with-parcel
```  
###### Checkout parcel
```
$ git fetch
$ git checkout build-with-webpack
```  

##### Included scripts:
- `dev`: example, `yarn dev` make a dev build of the application and run it. App will be available at `http://localhost:1234/`.  
- `prod`: example, `yarn prod` make a dev build of the application and it will be available in '/dist' directory.  
- `format`: example, `yarn format` formats the code using prettier and save all changes.  
- `lint`: example, `yarn lint` executes eslint against both `.js` and `.jsx` files in `/src` directory.  
- `lint:debug`: example, `yarn lint:debug` executes eslint against both `.js` and `.jsx` files in `/src` directory in debug mode.


