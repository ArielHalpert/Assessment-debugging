## Setup and Run

1. Install Python

```bash
sudo apt update
sudo apt install python3
sudo apt intall python3-pip
```
2. Setup Virtual Machine

```bash
python3 -m venv venv
source .venv/bin/activate
```

3. Install Dependencies

```bash
pip install -e .
```
4. Run the Application

```bash
python main.py
```

5. Access the Application

The application is available at `http://127.0.0.1:10030`, which you can reach by putting the URL in a web browser of your choice.