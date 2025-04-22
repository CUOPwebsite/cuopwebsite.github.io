# Cooper Union Organization of Part Time Faculty Website Content

Welcome! This repository holds the content for the CUOP website. The website is automatically built and updated whenever changes are made here. You do not need to install or run any special software (like Hugo) on your own computer to contribute.

## How to Create a New Post

Adding a new post to the website is straightforward. You will create a new file in the `content/posts` folder of this repository.

Here are the steps:

1.  **Navigate to the `content/posts` folder:** In this repository, go to the directory named `content`, then into the `posts` directory.
2.  **Create a New File:** In the `posts` folder, you can create a new file. On the GitHub website interface, you'll usually see an option like "Add file" -> "Create new file".
3.  **Name Your File:** Give your file a descriptive name ending in `.md` (which stands for Markdown). A good practice is to include the date, like `YYYY-MM-DD-brief-title.md`. For example: `2025-04-22-welcome-message.md`.
4.  **Add the Header Section (Post Metadata):** Every post *must* begin with a special section called "front matter" enclosed by `---` lines. This tells the website the post's title, date, and other information.

    Copy and paste this structure at the very beginning of your new file:

    ```markdown
    ---
    title: "Your Post Title Here"
    date: YYYY-MM-DDTHH:MM:SS-04:00 # The date and time of the post
    # Optional: uncomment the lines below if you want to use them
    # bookComments: false # Set to true to enable comments for this post
    # bookSearchExclude: false # Set to true to exclude this post from site search
    ---

    # This is where your post content begins
    ```
    *   **Replace `"Your Post Title Here"`** with the actual title of your post. This will appear as the headline on the website.
    *   **Replace `YYYY-MM-DDTHH:MM:SS-04:00`** with the current date and time you are creating the post. The format is Year-Month-DayTHour:Minute:Second followed by the timezone offset. You can often just use the date `YYYY-MM-DD` if the exact time isn't critical, like `date: 2025-04-22`.
    *   The lines starting with `#` are comments and are ignored. You can uncomment `bookComments: false` or `bookSearchExclude: false` and change `false` to `true` if you need those options, but they are not required.

5.  **Write Your Post Content:** Below the second `---` line, you can write the actual text of your post using **Markdown** formatting.
6.  **Save and Commit Your Changes:** Once you are finished writing, save the file. If you are using the GitHub website interface, you will see a section at the bottom to "Commit changes". Enter a brief description of your changes (e.g., "Add new post about X"), and click "Commit directly to the `main` branch".

## How Updates Go Live

**This is the important part:** As soon as you save/commit your changes to the `main` branch of this repository (by clicking the "Commit" button on GitHub or pushing changes if you are using Git locally), GitHub automatically rebuilds the website with your changes and publishes it.

**You do not need to run any commands or perform any extra steps to deploy your post.** Just save the file in the `content/posts` folder and commit the change!

## Need Help with Formatting or GitHub?

*   **Markdown Formatting:** Markdown is a simple way to add formatting like headings, bold text, lists, and links using plain text. You can learn the basics here:
    [Markdown Guide](https://commonmark.org/help/)

*   **Using GitHub:** If you are new to GitHub, the simplest way to add a post is often directly through the GitHub website. Here are some guides on editing files directly on GitHub:
    [Editing files in your repository - GitHub Docs](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files)

*   **Git Basics:** If you prefer to use Git commands on your computer, you can learn more about Git basics here, though this is not necessary for basic post updates using the GitHub website:
    [Git Handbook - GitHub Docs](https://docs.github.com/en/get-started/git-basics)
