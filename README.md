## React, Typescript and Parcel Bundler Boilerplate

React, Typescript and Parcel Bundler is a simple boilerplate that will get you going in seconds.

### Getting Started

    $ npm install
    $ npm run start
    
### Commands 

**Start**

This starts the parcel bundler and will create a local server ready for use.
	
	
    $ npm run start

**Build**

This build's using the parcel bundler and will output your compiled app to the output directory specified in the `package.json`. You can modify this to what ever you need. The default is set to `./dist`

    $ npm run build


### Warning!

**Environment Variables**

If you're using `.env` files within your app then you will need to delete the cache directory when changing these values as Parcel sometimes does not update these.