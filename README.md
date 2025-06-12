# All-In-One Internal Skill-based Role Portal (SPM_G5_T2)
<img width="949" alt="image" src="https://github.com/lyw142/SPM_G5_T2/assets/111484155/47978018-2322-4d4d-8e94-35887db63791">

This application serves as a comprehensive internal platform that allows employees to explore and apply for roles within the company based on their skills and qualifications. It also supports HR personnel and hiring managers in evaluating candidates more effectively, streamlining the internal recruitment process, and aligning talent with organizational needs.

## Features
- User Authentication & Role-Based Access: Secure login system with role-based access control. Employees and employers (e.g., HR staff and managers) are presented with different user interfaces and features based on their access levels
- Job Listing Management (Employers): Create, edit, and manage internal job listings to match organizational needs
- Job Application Portal (Employees): Browse available internal opportunities and apply for roles that align with their skill sets

## Recommended IDE Setup

To work on this project, we recommend using the following VS Code extensions:

[VSCode](https://code.visualstudio.com/) + [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Installation

1. Install project dependencies using pip and the provided `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```

## Dependencies

- Flask 2.3.2
- Flask-Cors 4.0.0
- Flask-SQLAlchemy 3.0.5
- Flask-Testing 0.8.1
- mysql-connector-python 8.1.0
- SQLAlchemy 2.0.19
- requests 2.26.0

These are the project's main dependencies.

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Cookie Installation

```sh
npm install js-cookie
```

### Usage
To run this project, follow these steps:

1. Create database named 'spm' on your local phpMyAdmin.

2. Import the SQL(spm.sql) file to the database. 

2. Next, you'll need to configure the database settings in the 'config.py' file. Open the 'config.py' file which is located at backend and update the database connection details to match your local setup.

3. After configuring the database settings, you can run the backend of the project. Open a terminal, navigate to the 'backend' directory, and execute 'appserver.py':
   ```sh
   cd backend
   python appserver.py
    ```

4. After running the backend, open another terminal and navigate to the 'frontend' directory:
   ```sh
   cd frontend
   ```

5. Run the frontend of the project by typing the following:

   ```sh
   npm run dev
   ```

These steps will allow you to run the application and connect it to your local database.
