# rclonerr

A streamlined, interactive Bash script that uses **rclone** and **fzf** to simplify file transfers between your local machine and cloud storage. Instead of typing out long paths, you can navigate your remotes visually using a fuzzy-search interface.

---

## 🚀 Features

* **Interactive Selection**: Uses `fzf` to select files and folders from both remote and local sources.


* **Operation Modes**: Offers a simple menu to toggle between **Download** and **Upload** tasks.


* **Performance Tuning**: Pre-configured with `--multi-thread-streams` and `--multi-thread-cutoff` for high-speed transfers.


* **Efficient Listing**: Utilizes `--fast-list` and `--checkers` to quickly pull directory structures from the cloud.


* **Visual Feedback**: Displays a real-time progress bar for all file transfers.



---

## 📋 Prerequisites

Before using `rclonerr`, ensure you have the following installed and configured:

1. **rclone**: Must be installed and configured with at least one remote.


2. **fzf**: Required for the interactive menus.


3. **Bash**: The script is written as a shell script.



---

## 🛠️ Usage

1. **Make the script executable**:
```bash
chmod +x rclonerr

```


2. **Run the script** by specifying the name of your rclone remote:
```bash
./rclonerr your_remote_name

```



### Operations:

* **Download**:
* The script lists files/folders on the remote.


* Select an item to copy it to your current local directory.




* **Upload**:
* Select a file or folder from your current local directory.


* Select a destination folder (or ROOT) on the remote.





---

