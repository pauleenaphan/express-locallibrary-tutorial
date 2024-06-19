# Library express tutorial
This is a [MDN Express Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Tutorial_local_library_website)
of how to set up a library using the framework express.

[Live site, uploaded using glitch](https://harmless-flying-blade.glitch.me) 


## Setup Instructions

1. Clone the repository.
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   cd yourrepository
   ```

2. Install dependencies.
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory of the project, based on the `.env.example` file.
   ```bash
   cp .env.example .env
   ```

4. Edit the `.env` file and add your MongoDB URL.
   ```plaintext
   DEV_DB_URL=your_mongodb_url_here
   ```

5. Start the application.
   ```bash
   npm start
   ```
