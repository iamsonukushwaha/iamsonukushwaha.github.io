

**Using `zip` and `unzip` Commands with Examples**

The `zip` and `unzip` commands are used to create and extract compressed zip archives on Linux and Unix systems. Here are some examples of how to use these commands:

**Using `zip`**:

1. **Create a zip archive**:
   To create a zip archive of a directory or file, use the `zip` command. For example:

   ```bash
   zip -r archive.zip directory/
   ```

   This command will create a zip archive named `archive.zip` containing the contents of the `directory` and its subdirectories.

2. **Create a zip archive with multiple files**:
   You can add multiple files to a zip archive like this:

   ```bash
   zip archive.zip file1.txt file2.txt
   ```

   This will create `archive.zip` containing `file1.txt` and `file2.txt`.

3. **Add files to an existing zip archive**:
   To add files to an existing zip archive, use the `-u` option:

   ```bash
   zip -u archive.zip newfile.txt
   ```

   This will add `newfile.txt` to the `archive.zip` if it doesn't already exist.

4. **Password-protect a zip archive**:
   To create a password-protected zip archive, use the `-P` option followed by the password:

   ```bash
   zip -r -P secret archive.zip directory/
   ```

   This will create `archive.zip` with the contents of `directory` and password-protect it with "secret."

**Using `unzip`**:

1. **Extract a zip archive**:
   To extract the contents of a zip archive, use the `unzip` command:

   ```bash
   unzip archive.zip
   ```

   This will extract the contents of `archive.zip` into the current directory.

2. **Extract a zip archive to a specific directory**:
   To extract a zip archive to a specific directory, use the `-d` option:

   ```bash
   unzip archive.zip -d /path/to/directory
   ```

   This will extract the contents of `archive.zip` to the specified directory.

3. **List the contents of a zip archive**:
   To list the contents of a zip archive without extracting them, use the `-l` option:

   ```bash
   unzip -l archive.zip
   ```

   This will display a list of files and directories within `archive.zip`.

4. **Extract a password-protected zip archive**:
   If you have a password-protected zip archive, you'll be prompted to enter the password when using the `unzip` command:

   ```bash
   unzip archive.zip
   ```

   You'll be prompted to enter the password.


