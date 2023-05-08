

# CommentToxicity

CommentToxicity is a Python-based application that uses machine learning models to determine the toxicity level of comments. The application is designed to detect comments that contain hateful or inappropriate language and help flag them for further review.

This application is based on the Perspective API developed by Jigsaw, which is a machine learning tool that helps identify toxic language in online comments. CommentToxicity provides an easy-to-use interface for accessing the power of the Perspective API, making it a valuable tool for moderators, community managers, and anyone else who needs to manage online comments.

## Getting Started

To use CommentToxicity, you'll need to install Python and several Python packages. You can install these packages using pip, the Python package installer. Here are the steps to get started:

1. Install Python by downloading and running the installer from the official Python website.
2. Open a command prompt or terminal window.
3. Use the following command to install the required packages:

   ```
   pip install -r requirements.txt
   ```

4. Once the packages are installed, run the application using the following command:

   ```
   python main.py
   ```

## How it Works

CommentToxicity uses the Perspective API to analyze comments and determine their toxicity level. The Perspective API is a machine learning tool that has been trained on a large dataset of comments to recognize patterns of toxic language. When you enter a comment into CommentToxicity, the application sends the comment to the Perspective API, which returns a score indicating the comment's toxicity level.

The score is a value between 0 and 1, where 0 indicates that the comment is not toxic at all, and 1 indicates that the comment is highly toxic. CommentToxicity uses this score to determine whether the comment should be flagged for further review.

## Contributing

Contributions to CommentToxicity are always welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them to your branch.
4. Push your branch to your fork.
5. Open a pull request.

