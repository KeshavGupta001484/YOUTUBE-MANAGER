# YouTube Video Manager

Welcome to the YouTube Video Manager! This Python application provides a simple yet powerful way to manage a collection of YouTube videos. With features like adding, updating, deleting, and listing videos, this program is ideal for anyone looking to organize their video data efficiently.

## Key Features

- **List Videos**: Display all saved YouTube videos with their titles and durations in an organized format.
- **Add Videos**: Seamlessly add new videos to your collection by providing a title and duration.
- **Edit Videos**: Update the title or duration of any existing video in the list.
- **Delete Videos**: Remove unwanted videos from your collection with ease.
- **Persistent Storage**: All changes are saved to a local JSON file (`youtube.txt`), ensuring your data remains intact between sessions.

## Prerequisites

- Python 3.7 or higher installed on your system.

## Getting Started

Follow these steps to set up and run the YouTube Video Manager:

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Run the Program**:
   ```bash
   python youtube_manager.py
   ```

## Application Workflow

1. **File Handling**:
   - The application uses a JSON file (`youtube.txt`) to store and retrieve video data.
   - If the file does not exist, the program initializes an empty list and creates the file upon saving.

2. **Interactive Menu**:
   - The program features an intuitive menu for easy navigation.

3. **CRUD Operations**:
   - Perform Create, Read, Update, and Delete actions on your video collection.

## Menu Options

1. **List All YouTube Videos**:
   - Displays all videos currently saved in the system.
   ```
   Example Output:
   **************************************************
   1. My First Video , Duration: 5:00
   2. Travel Vlog , Duration: 12:15
   **************************************************
   ```

2. **Add a New YouTube Video**:
   - Prompts you to enter the video title and duration.
   ```
   Enter video title: Cooking Tutorial
   Enter video time: 15:30
   ```

3. **Update a YouTube Video**:
   - Choose a video by its index and update its details.
   ```
   Enter the index of the video you want to update: 1
   Enter new video title: Advanced Cooking
   Enter new video time: 18:45
   ```

4. **Delete a YouTube Video**:
   - Select a video by its index to remove it from the collection.
   ```
   Enter the index of the video you want to delete: 2
   ```

5. **Exit the Application**:
   - Closes the program gracefully.

## Example Workflow

```
Welcome to YouTube Manager! Choose an option:
1. List all YouTube Videos
2. Add a new YouTube Video
3. Update a YouTube Video
4. Delete a YouTube Video
5. Exit the App
Enter your choice: 2

Enter video title: Summer Vacation
Enter video time: 20:00
Video added successfully!

Returning to main menu...
```

## Why Use This Program?

- **Ease of Use**: The intuitive interface makes managing your videos straightforward.
- **Lightweight**: No external dependencies, ensuring seamless setup and performance.
- **Persistence**: Your data is saved locally, so it’s always available.
- **Customizable**: Modify the code to tailor it to your specific needs.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request. Let’s make this tool even better together.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

Organize your YouTube video collection effortlessly with
