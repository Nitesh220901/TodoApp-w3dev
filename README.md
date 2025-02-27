# Basic Todolist using with MERN + Tailwind + Docker

**W3DEV Pvt Ltd. Javascript Development Internship Assignment** 

**To run application follow these steps**

**Frontend - React**

1. Make sure you must be installed **NodeJS**,**Git** and **Git Bash** if not download it here [Git] (https://git-scm.com/downloads) [Node] (https://nodejs.org/en), then Open Git bash terminal and choose any directory **Local Disk C or D**.

2. Then inside directory, run command **`git clone https://github.com/Nitesh220901/TodoApp-w3dev.git`**.

3. If you cloned the repo, create **`.env`** file inside the **`client`** folder and create these variable **`VITE_BASE_URL='http://localhost:5000/api/v1'`** you can replace **5000** any other PORT NO. as per your choice.

4. Now, you have to run command **`npm install`** or **`npm i`** in the terminal.

5. After installation of all dependencies, you have to run last command **`npm run dev`**

6. Now your React App will run successfully.
  
**Backend - NodeJS + Express**

Similary as above frontend, follow all steps as above except **STEP 3**

**Addtional steps**
1. After created the **`.env`** file inside the **`api`** folder create these variables 
**`SERVER_PORT=5000
SALT=10
DB_URI="************************************"`** this URI is confidential, so that you have to create your own URI inside **`

2. Now, you follow steps **STEP 4 and 5** as above

**Backend - Docker**

1. Make sure you must be installed **Docker**, if not download it here (https://www.docker.com/products/docker-desktop/)

2. Open new terminal or command prompt, go to inside the directory **`todolist/api/`**..

3. Run the command **`docker compose up`** and then it will run your API container. 


**Screen Recorded Link**
(https://www.loom.com/share/42b25dec48cc4a71878cfaf0a23e9e70?sid=70430981-6665-44f7-81b3-3e5b478f7d1f)



