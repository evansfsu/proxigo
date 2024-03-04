
node@v16.4.2 or higher
npm@7.18.1 or higher
git@2.30.1 or higher

# Clone the repository
$ git clone https://github.com/evansfsu/proxigo

# Move into the repository
$ cd simplefolio

# Remove the current origin repository
$ git remote remove origin

# Fix Dependencies
$ npm audit fix
$ npm i @parcel/transformer-sass

# Install dependencies
$ npm install

# Start the development server
$ npm start

If your run into issues installing the dependencies with NPM, use this below command:


# Install dependencies with all permissions
$ sudo npm install --unsafe-perm=true --allow-root



I highly recommend to use [Netlify](https://netlify.com) because it is super easy.


