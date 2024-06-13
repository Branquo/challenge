## Instructions

- Create a virtual environment:
    ```bash
    python -m venv venv
    .\venv\Scripts\activate
    ```

- Install dependencies
    ```bash
    pip install -r requirements.txt
    ```

- Run the backend
    ```bash
    uvicorn main:app --reload
    ```