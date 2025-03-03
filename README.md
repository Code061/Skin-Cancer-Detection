# Skin Cancer Detection

This project aims to detect skin cancer from images using a deep learning model. The project includes training the model, making predictions, and evaluating the model's performance.

## Project Structure

- `models/`: Directory containing the trained model.
- `src/`: Directory containing the training script.
- `app.py`: Streamlit application for skin cancer detection.
- `main.py`: Script to train the model.
- `predict.py`: Script to make predictions and evaluate the model.

## Setup

1. **Clone the repository**:
    ```sh
    git clone <repository-url>
    cd Mini-project_code
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    ```

3. **Activate the virtual environment**:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```

4. **Install the dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

## Training the Model

To train the model, run the [main.py](http://_vscodecontentref_/3) script:

```sh
python main.py
```


## Making Predictions

To make predictions using the trained model, run the predict.py script:

```sh
python predict.py
```

## Running the Streamlit App

To run the Streamlit app, use the following command:

```sh
streamlit run app.py
```

This will start the Streamlit server, and you can view the app in your web browser at the URL provided in the terminal output (usually http://localhost:8501).

## Dependencies

- streamlit
- tensorflow
- numpy
- scikit-learn

These dependencies are listed in the **requirements.txt** file and can be installed using **pip install -r requirements.txt.**

## License

This project is licensed under the MIT License
