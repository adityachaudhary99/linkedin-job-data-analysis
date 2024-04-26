# LinkedIn-Job-Data-Analysis

Welcome to the **LinkedIn Job Data Analysis** repository! This project aims to to analyze LinkedIn job data for the first quarter of 2024 to answer questions such as:

1. What skills are most in demand by employers for specific job roles?
2. What is the job posting trend overtime?
3. What is the distribution of job levels for specific job roles?
4. What is the distribution of job types for specific job roles?
5. What are the top 10 required skills for a specific job role according to data?

**For this project, We will be using this specific job role as "Machine Learning Engineer".**

By extracting relevant LinkedIn data, we can explore career paths, identify trends, and make informed decisions related to talent sourcing, workforce development, and industry insights.

## Project about 
It's a project for 30 Day ML challenge by Break-Into-Data 
([Website](https://merinova.substack.com/),
[Discord](https://discord.gg/engQhPaVrX))

## Dataset
[Kaggle-Dataset-Link](https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024)

## Project Dashboard

![alt text](.LinkedIn_dashboard.png)



# Reproducing from scratch

## Getting Started

Follow these steps to set up and run the project on your local machine:

1. **Clone the Repository:**
   - Open your terminal or command prompt.
   - Run the following command to clone the repository:
     ```
     git clone https://github.com/your-username/project-name.git
     ```

2. **Navigate to the Project Directory:**
   - Change your working directory to the cloned project folder:
     ```
     cd project-name
     ```

3. **Install Dependencies:**
   - Make sure you have the necessary dependencies installed (e.g., Python, Node.js, etc.).
   - If there's a `requirements.txt` or `package.json` file, run:
     ```
     pip install -r requirements.txt
     ```
     
4. **Run the Project:**
   - Execute the jupyter notebook to see project results.

## Kaggle API Setup Guide

The Kaggle API allows you to interact with Kaggle datasets, competitions, and kernels from the command line. Follow the steps below to install and configure the Kaggle API on different operating systems:

### Windows

1. **Install Python and pip:**
   - Make sure you have Python 3 and the package manager pip installed on your Windows machine.

2. **Install the Kaggle API:**
   - Open a command prompt or PowerShell.
   - Run the following command to install the Kaggle API:
     ```
     pip install kaggle
     ```

3. **Get Kaggle API Credentials:**
   - Log in to Kaggle or create an account if you don't have one.
   - Go to your account settings and navigate to the "API" section.
   - Click "Create New API Token" to download a file named `kaggle.json`.

4. **Place `kaggle.json` in the Right Location:**
   - Move the downloaded `kaggle.json` file to `C:\Users\<YourUsername>\.kaggle\`.

5. **Set Permissions:**
   - Right-click on the `kaggle.json` file, go to Properties > Security, and ensure that your user account has read permissions.

6. **Test Authentication:**
   - Open a new command prompt or PowerShell.
   - Run the following command to verify authentication:
     ```
     kaggle datasets list
     ```

### Linux and Mac

1. **Install Python and pip:**
   - Ensure you have Python 3 and pip installed on your system.

2. **Install the Kaggle API:**
   - Open a terminal.
   - Run the following command to install the Kaggle API:
     ```
     pip install kaggle
     ```

3. **Get Kaggle API Credentials:**
   - Log in to Kaggle or create an account if needed.
   - Go to your account settings and navigate to the "API" section.
   - Click "Create New API Token" to download `kaggle.json`.

4. **Place `kaggle.json` in the Right Location:**
   - Move the downloaded `kaggle.json` file to `~/.kaggle/`.

5. **Set Permissions:**
   - In the terminal, run:
     ```
     chmod 600 ~/.kaggle/kaggle.json
     ```

6. **Test Authentication:**
   - Run the following command to verify authentication:
     ```
     kaggle datasets list
     ```

### Usage

You're all set! You can now use the Kaggle API from the command line. Explore datasets, download files, and participate in Kaggle competitions.

Remember to keep your `kaggle.json` file secure and never share it publicly.

## Contributing

If you'd like to contribute to this project, feel free to submit pull requests or open issues. We welcome your feedback and ideas!
