# How to Create a Basic Static Website Using Markdown With GitHub Pages

![Github Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)  ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

## Introduction


Hi there! 👋 I'm Suheda and I'm currently studying IT at OAMK.For one of my assignments, I was tasked with creating a public static website using __only Markdown__ for formatting, and hosting it on __GitHub Pages__.

Markdown is a lightweight markup language that makes it easy to format text without needing to write HTML, which simplifies the entire process. As part of the assignment, I decided to write this guide to show you how you can do the same. Whether you’re a fellow student working on a similar task or just someone curious about building a simple website with Markdown, this tutorial will walk you through the entire process. By the end, you’ll have a working static website up and running! 🌐

Let’s dive in and get started with your very own Markdown-powered website! 🚀

If you'd like to see the end result of this guide, check out the live version of the website below:

[![Live Website](https://img.shields.io/badge/Live%20Website-Up%20and%20Running-brightgreen)](https://suheda-snr.github.io/static-website-guide/)

---

## Prerequisites

Before you start, _ensure_ you have:

- A **GitHub account**.
- Basic understanding __Git__ and __GitHub__.

---

## Step 1: Create a GitHub Repository

1. Log in to your GitHub account.
2. Click on the **"+" icon** in the upper right corner and select **"New repository."**
3. Enter the repository name (e.g., `my-markdown-site`) and description.
4. Set the repository to **public** or **private** as preferred.
5. Click on **"Create repository."**

---

## Step 2:  Build Your Markdown Website

### 1. Create Your Markdown File

In your local computer, create and navigate to your project folder:

```bash
mkdir myprojectfolder
cd myprojectfolder
```

Then, create your project file:
> [!WARNING]
> If you only have other Markdown files (like about.md), GitHub Pages won’t know which one to display as the homepage. Ensure that the root of your repository contains an index.md file.

```bash
touch index.md
```
Alternatively, you can clone this repository if you want to start with a predefined structure:

```bash
git clone https://github.com/suheda-snr/static-website-guide.git
```

> [!NOTE]
> For a comprehensive guide on writing and formatting Markdown, check out  [GitHub's Markdown Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). 

### 2. Enhance Your Editing Experience
To enhance your Markdown editing experience, consider installing extensions for your code editor. These extensions can help you write and preview Markdown more efficiently.


### 3. Write Your Content

Now that you have your file set up, start adding your content. Here’s a simple structure to follow:

#### Sample Content Structure

```markdown
    # Welcome to My Markdown Site

    This website is created using Markdown and hosted on GitHub Pages.

    > [!TIP]
    > Use headings to organize your content and improve readability.

    > [!NOTE]
    > To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the hierarchy level and typeface size of the heading.

    ## Title 1
    -Write your content here and style with markdown

    ### Ordered List Example

    1. Nested List
        - 
        -
    2. 
    3. 
    
    ## Title 2 

    ### Unordered List Example 
    You can make an unordered list by preceding one or more lines of text with -, *, or +.
    -
    *
    +

    ### Subtitle 1
    Some content

    ### Subtitle 2
    Some content

    ### Some extra examples for Markdown features
    - **Bold text**: Use `**double asterisks**` or `__double underscores__`.
    - **Italic text**: Use `*single asterisk*` or `_single underscore_`.
    - Alerts: To add an alert, use a special blockquote line specifying the alert type (TIP, NOTE, IMPORTANT, WARNING,CAUTION), followed by the alert information in a standard blockquote.
        > [!TIP]
        > your information
```

## Step 3: Push Your Markdown File to GitHub

> [!WARNING]
> **Important:** Ensure you have set your remote URL correctly to avoid pushing to the wrong repository. Double-check your GitHub username and repository name before executing the push command.

1. Open your terminal or command prompt.
2. Navigate to your project directory.
3. Initialize a new Git repository:
   ```bash
    echo "# my-markdown-site" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/yourusername/my-markdown-site.git
    git push -u origin main
   ```

## Step 4: Enable GitHub Pages

1. Go to your GitHub repository.
2. Click on **"Settings."**
3. Scroll down to the **"Pages"** section.
4. Select the branch (e.g., `main`) as the source for GitHub Pages.
5. Click **"Save."**

Once you have completed these steps, your website will be accessible at the following URL format:
`https://yourusername.github.io/your-repo-name/`

> [!IMPORTANT]
> Ensure to replace `yourusername` with your GitHub username and confirm your default branch name (it might be `master`).

---

## Conclusion

You’ve successfully created a basic static website using Markdown and hosted it on GitHub Pages. This guide serves as a foundation for further customization and exploration of Markdown capabilities.

> [!NOTE]
> Check the  [Markdown Guide](https://www.markdownguide.org/) for more advanced syntax options!


## Contact Information

If you have any questions or feedback regarding this project, feel free to reach out to me:

- **Name:** Suheda Sener
- **Email:** [![Email Badge](https://img.shields.io/badge/Email-suhedasyda@gmail.com-orange?style=flat&logo=gmail&logoColor=white)](mailto:suhedasyda@gmail.com)
- **GitHub:** [![GitHub Profile](https://img.shields.io/badge/-suheda--snr-181717?style=flat&logo=github&logoColor=white)](https://github.com/suheda-snr)
- **LinkedIn:** [![LinkedIn Profile](https://img.shields.io/badge/-SuhedaSener-blue?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/suheda-sener/)


**Thank you for your interest in my project!** 😊✨
