## Configure the project

1. Rename the `oauth_settings.yml.example` file to `oauth_settings.yml`.
1. Edit the `oauth_settings.yml` file and make the following changes.
    1. Replace `YOUR_APP_ID_HERE` with the **Application Id** you got from the App Registration Portal.
    1. Replace `YOUR_APP_PASSWORD_HERE` with the password you got from the App Registration Portal.
1. In your command-line interface (CLI), navigate to this directory and run the following command to install requirements.

    ```Shell
    pip install -r requirements.txt
    ```

1. In your CLI, run the following command to initialize the app's database.

    ```Shell
    python manage.py migrate
    ```

## Run the project

1. Run the following command in your CLI to start the application.

    ```Shell
    python manage.py runserver
    ```

1. Open a browser and browse to `http://localhost:8000`.
