# ShorteneR
This application is a URL shortener, like bit.ly, and in addition to the central shortening and redirection functionality, it includes link access statistics.  

What we have: Node.js, Express, EJS, Sequelize and SQLite.

## How-to
1. Install [NodeJS](https://nodejs.org/) and [Visual Studio Code](https://code.visualstudio.com)
   - Check if node is installed
   ```powershell
   $ node -v
   v18.14.2
   ```
  
2. Install express-generate globally
   ```powershell
   $ sudo npm install -g express-generator
   ```

   * Check if express is installed
   ```powershell
   $ express --version
   4.16.1
   ```

3. Create the application using the template
   ```powershell
   $ express -e --git shortener
   ```
  
   * Commands until starting the application and making it available at `http://localhost:3000`
   ```powershell
   $ cd shortener/
   $ npm install
   $ npm start
   ```

