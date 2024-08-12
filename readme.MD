
## Backend

### Installation

1. Navigate to the `backend` directory:
    ```sh
    cd backend
    ```

2. Create a virtual environment:
    ```sh
    python -m venv venv
    ```

3. Activate the virtual environment:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```

4. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

### Running the Backend

1. Start the FastAPI server:
    ```sh
    uvicorn main:app --reload
    ```

2. The backend server will be running at `http://localhost:8000`.

### File Structure

- `main.py`: Main entry point of the FastAPI application.
- `src/models.py`: Contains the neural style transfer model.
- `src/utils.py`: Utility functions for image handling.
- `src/criterion.py`: Criterion for calculating the loss during training.
- `requirements.txt`: List of Python dependencies.

### Example Code

#### `main.py`
