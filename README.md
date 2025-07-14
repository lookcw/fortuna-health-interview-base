## Getting started

##### Remember AI tool's are encouraged and we're just looking for a working product. Good luck!


1. Run the server-side FastAPI app in one terminal window:

    ```sh
    $ cd backend
    $ python3.13 -m venv env
    $ source env/bin/activate
    (env)$ pip install -r requirements.txt
    (env)$ python main.py
    ```

    Navigate to [http://localhost:8000](http://localhost:8000)

1. **Alternative: Run the Node.js backend server** (instead of FastAPI):

    ```sh
    $ cd backend-node
    $ npm install
    $ npm start
    # or for development with auto-restart:
    $ npm run dev
    ```

    Navigate to [http://localhost:8000](http://localhost:8000)

1. Run the client-side React app in a different terminal window:

    ```sh
    $ cd frontend
    $ npm install
    $ npm run dev
    ```

    Navigate to [http://localhost:5173](http://localhost:5173)
