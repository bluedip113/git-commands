# git-commands


### 1. **Use `pipreqs` to create a `requirements.txt`**

   `pipreqs` is a tool that can automatically generate a `requirements.txt` file based on imports in your project files.

   - Install `pipreqs` if you haven’t:
     ```bash
     pip install pipreqs
     ```

   - Run `pipreqs` in the root directory of the project:
     ```bash
     pipreqs /path/to/your/project
     ```

### 2. **Set Up a Virtual Environment**
   Create a virtual environment to isolate the project dependencies.

   ```bash
   python -m venv env
   ```

   Then, activate the virtual environment:
   - On **Windows**:
     ```bash
     .\env\Scripts\activate
     ```

- To install dependencies from a `requirements.txt` file, use the following command:

```bash
pip install -r requirements.txt
```
