### 🚀 How to Run the Project

Clone the repository and navigate into it from the command line:

```bash
git clone https://github.com/wabisabicode/kittygram_final.git
```

```bash
cd backend
```

Create and activate a virtual environment:

```bash
python3 -m venv env
```

* If you're on **Linux/macOS**:

```bash
source env/bin/activate
```

* If you're on **Windows**:

```bash
source env/scripts/activate
```

Upgrade `pip`:

```bash
python3 -m pip install --upgrade pip
```

Install dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
```

Apply database migrations:

```bash
python3 manage.py migrate
```

Start the development server:

```bash
python3 manage.py runserver
```
