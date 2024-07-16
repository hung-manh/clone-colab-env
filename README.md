# Colab Virtual Environment Setup and Export

This script helps you create a virtual environment in Google Colab, install dependencies from a `requirements.txt` file, create an archive of the environment, and copy it to your Google Drive for high-speed download.

**Description:**

1. Creates a virtual environment named after `venv_name`.
2. Installs dependencies specified in `requirements.txt`.
3. Creates an archive named `archive_name` containing the virtual environment.
4. Copies the archive to the specified location in your Google Drive.

**Usage:**

1. **Mount Google Drive:**
   - Mount your drive
2. **Run the Script:**
   - Copy and paste the entire script into a new Colab notebook cell.
   - Execute the cell by pressing `Shift` + `Enter`.
3. **Change the VIRTUAL_ENV in the activate file:**
    - Open the `activate` file located in the virtual environment directory. Usually, it is located at `venv_name/bin/activate`.
    - Set `VIRTUAL_ENV="localtion_of_your_env_located"` in the `activate` file.

**Output:**

- A virtual environment named after `venv_name` will be created.
- Dependencies will be installed from the specified `requirements.txt` file.
- An archive named `archive_name` containing the virtual environment will be created in your Colab environment.
- The archive will be copied to the specified location in your Google Drive.

**Additional Notes:**

- You can adjust the variable values to suit your needs.
- Make sure the `requirements.txt` file is present in the specified location.


