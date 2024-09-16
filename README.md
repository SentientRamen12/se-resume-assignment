# se-resume-assignment
Django Project with Resume

## Setup Instructions

1. Clone the repository:
   ```
   git clone https://github.com/your-username/se-resume-assignment.git
   cd se-resume-assignment
   ```

2. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ``` 

3. Create a virtual environment:
    ```
    python -m venv venv
    ```

4. Activate the virtual environment:
    - On Windows:
    ```
    venv\Scripts\activate
    ```
    - On macOS and Linux:
    ```
    source venv/bin/activate
    ```

5. Apply database migrations:
    ```
    python manage.py migrate
    ```


## Running the Django Server

1. Start the Django development server:
   ```
   python manage.py runserver
   ```

2. Open a web browser and navigate to:
   ```
   http://127.0.0.1:8000/resume/
   ```