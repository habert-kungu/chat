
# Welcome to jatte: a simple, minimalistic chat app
Connect, chat, and create memories with Jatte. Dive into a seamless chat experience that keeps you engaged and connected with your friends and loved ones.
## Screenshots 
### User Site

![Jatte](https://github.com/habert-kungu/chat/blob/main/screenshots/front%20jatte.png)

![Jatte](https://github.com/habert-kungu/chat/blob/main/screenshots/below%20jatte.png)

### Admin site 
![Jtte](https://github.com/habert-kungu/chat/blob/main/screenshots/admin%20jatte.png)

## **Warning** Make sure you have Django and Node installed with you package manager 
## How to run Chat

Clone the repository:

```
git clone https://github.com/habert-kungu/chat.git
```

Go to chat directory

```
cd chat
```

Install the requirements

```bash
pip install -r requirements.txt
```

Go to jatte/jatte_app  directory

```
cd jatte/jatte_app 
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
## Installing Node.js on Your System

Node.js is a JavaScript runtime environment that allows you to run JavaScript code outside of a web browser. This guide will walk you through installing Node.js on your system.

**Prerequisites:**

* An internet connection
* Administrator privileges (recommended)

**Choose Your Operating System:**

**Windows:**

* Download the latest LTS (Long-Term Support) version of Node.js from the official website: [https://nodejs.org/en/download/package-manager](https://nodejs.org/en/download/package-manager)
* Double-click the downloaded installer and follow the on-screen instructions.
* **Recommended:** During installation, check the box to "Add Node.js to PATH". This will allow you to run Node.js commands from any directory in your command prompt.

**macOS:**

* Open a Terminal window (Applications > Utilities > Terminal).
* Install Node.js and npm (Node Package Manager) using a package manager like Homebrew:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install node
```

* Alternatively, you can download an installer from the official website: [https://nodejs.org/en/download/package-manager](https://nodejs.org/en/download/package-manager)

**Linux:**

* The installation process varies depending on your Linux distribution. Here are some common methods:
    * **Using a package manager:**
        * Search for `nodejs` or `npm` in your distribution's package manager. 
        * For example, on Ubuntu/Debian:
        ```bash
        sudo apt update
        sudo apt install nodejs
        ```
    * **Using a version manager:**
        * Consider using a version manager like `nvm` (Node Version Manager) to manage multiple Node.js versions on your system. You can find installation instructions for `nvm` here: [https://github.com/nvm-sh](https://github.com/nvm-sh)
    * **From source:**
        * Download the source code from the official website: [https://nodejs.org/en/download/package-manager](https://nodejs.org/en/download/package-manager)
        * Follow the build instructions in the downloaded archive. (This method is not recommended for beginners.)

**Verifying Installation:**

* Open a terminal window (Windows Command Prompt, macOS Terminal, Linux Terminal).
* Type the following commands and press Enter after each:

```bash
node -v   # This should print the installed Node.js version
npm -v    # This should print the installed npm version
```

**Congratulations!** You have successfully installed Node.js on your system.

**Additional Resources**

* Node.js Official Website: [https://nodejs.org/en/download/package-manager](https://nodejs.org/en/download/package-manager)
* npm Package Manager Documentation: [https://docs.npmjs.com/](https://docs.npmjs.com/)


**Note:** This guide provides a basic overview of Node.js installation. Refer to the official documentation linked above for detailed information specific to your operating system and preferred installation method.

## Below is the installation guide for Django

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
