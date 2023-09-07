Project Name:Car Showroom

This is a fullstack project built using python and javascript . A car showroom with complext features .
## Installation and Contribution
To work on this project locally, follow these steps:
1. **Clone the Repository:**

   ```bash
   git clone https://github.com/showroom/your-project.git

2. ** Navigate to the project directory **
      ```bash

   cd carshowroom 
3.Create a new branch

      ```bash

 git checkout -b new-branch-name


3. Create a virtual environment 
        ```bash

   python -m venv venv
      ```bash

  source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

4. Install all the dependencies
   ```bash

    pip install -r requirements.txt
5. apply data migrations 
   ```bash

   python manage.py makemigrations
6. setup react frontend
   ```bash
      cd reactapp
  ```bash
    npm install

      ```bash

   npm run build
6. Start the Development Server:

    ```bash

  python manage.py runserver   