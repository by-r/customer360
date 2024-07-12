# Summary

Simple Django CRM using Function Based Views

## Features
- Display customer record
- Display interaction History in the last 30 days
- Provide customer management

## Disclaimer

Project was developed as part of the IBM Django Module

## How to run and install 

1. Use a virtual environment

   ```bash
   python -m venv venv
   ```

   ```bash
   source venv/Scripts/activate
   ```

   note : depends on the OS you are using

2. install the requirements
   
   ```
   pip install -r requirements.txt
   ```

3. Make migrations and spin up the local server
   
   ```
   python manage.py makemigrations
   python manage.py migrate
   python manage.py runserver
   ```
