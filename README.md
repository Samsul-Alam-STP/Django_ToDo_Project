# Django ToDo Project

This is a Django-based ToDo project that allows users to create and manage their tasks.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/django-todo.git
   ```

2. Navigate to the project directory:

   ```shell
   cd django-todo
   ```

3. Create a virtual environment:

   ```shell
   python3 -m venv env
   ```

4. Activate the virtual environment:

   - On macOS and Linux:
     ```shell
     source env/bin/activate
     ```

   - On Windows:
     ```shell
     .\env\Scripts\activate
     ```

5. Install the project dependencies:

   ```shell
   pip install -r requirements.txt
   ```

6. Run database migrations:

   ```shell
   python manage.py migrate
   ```

7. Start the development server:

   ```shell
   python manage.py runserver
   ```

8. Open your web browser and visit `http://localhost:8000` to access the application.

## Usage

- To create a new task, click on the "Add Task" button and fill in the details.
- To mark a task as completed, click on the checkbox next to the task.
- To edit or delete a task, click on the respective buttons available for each task.
- You can filter tasks based on their completion status using the provided options.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```shell
   git checkout -b feature/new-feature
   ```
3. Make your changes and commit them:
   ```shell
   git commit -m "Add new feature"
   ```
4. Push the changes to your forked repository:
   ```shell
   git push origin feature/new-feature
   ```
5. Open a pull request in this repository, describing your changes.

