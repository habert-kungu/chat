# Welcome to jatte a simpleminimalistic chat app

## How to run Chat

Clone the repository:

```
git clone https://github.com/habert-kungu/chat.git
```

Go to cargo directory

```
cd chat
```

Install the requirements

```bash
pip install -r requirements.txt
```

Install the tailwind configuration

```bash
npm install
```

run tailwind

```bash
npx tailwindcss   -i ./static/css/main.css -o ./static/css/main.css  --watch
```

## How to run since it is being developed run it by

```
python manage.py runserver
```

!! Make sure you have Django installed with you package manager

Certainly! Below is the installation guide for Django

### Installing Django on Different Operating Systems

#### 1. Windows:

1. **Install Python**: If Python is not installed, download and install it from the [official Python website](https://www.python.org/downloads/).

2. **Open Command Prompt**: Open Command Prompt as an administrator.

3. **Install Django**: Use pip to install Django:
   ```
   pip install django
   ```

#### 2. macOS:

1. **Install Homebrew**: If Homebrew is not installed, you can install it by running the following command in Terminal:

   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. **Install Python**: Use Homebrew to install Python:

   ```bash
   brew install python
   ```

3. **Install Django**: Use pip to install Django:
   ```bash
   pip install django
   ```

#### 3. Linux (Ubuntu/Debian):

1. **Update Package Index**: Update the package index:

   ```bash
   sudo apt update
   ```

2. **Install Python and pip**: Install Python and pip:

   ```bash
   sudo apt install python3 python3-pip
   ```

3. **Install Django**: Use pip to install Django:
   ```bash
   pip install django
   ```

#### 4. Linux (Red Hat/CentOS):

1. **Install Python and pip**: Install Python and pip:

   ```bash
   sudo yum install python3 python3-pip
   ```

2. **Install Django**: Use pip to install Django:
   ```bash
   pip install django
   ```

#### 5. Any OS (Using Virtual Environment):

1. **Install virtualenv** (if not already installed):

   ```bash
   pip install virtualenv
   ```

2. **Create a Virtual Environment**:

   ```bash
   python -m venv myenv
   ```

   Replace `myenv` with your preferred name for the virtual environment.

3. **Activate the Virtual Environment**:
   - Windows:
     ```bash
     myenv\Scripts\activate
     ```
   - macOS/Linux:
     ```bash
     source myenv/bin/activate
     ```
4. **Use Anaconda Virtual Environment**
   ```bash
   conda activate name
   ```
5. **Install Django**:
   ```bash
   pip install django
   ```

These are general steps, and you might encounter specific issues or requirements depending on your system configuration. Always refer to the [official Django documentation](https://docs.djangoproject.com/en/stable/intro/install/) for the latest installation instructions and best practices.
