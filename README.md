# Recipe Preparation Agent

*Problem Statement No. 16: Recipe Preparation Agent*

This project's goal is to create a RAG-based AI system that helps users cook meals using only the ingredients they have on hand. It serves as a personal AI assistant to make everyday cooking smarter, simpler, and more sustainable.

---

## Project Description

The Recipe Preparation Agent is designed to solve the common problem of food waste and the daily challenge of deciding what to cook. By leveraging a Retrieval-Augmented Generation (RAG) system, this agent provides tailored recipe suggestions based on a user's available groceries.

Key features include:
* *Recipe Retrieval:* The system retrieves relevant recipes based on a list of ingredients provided by the user.
* *Step-by-Step Instructions:* It generates clear, step-by-step cooking instructions, adapting them to the user's ingredient limitations.
* *Ingredient Substitutions:* The agent can offer intelligent substitutions for missing ingredients.
* *Dietary and Preference Adjustments:* It provides cooking tips and can make dietary adjustments based on user preferences or restrictions (e.g., vegetarian, gluten-free, etc.).

This project is built to reduce food waste and save time, turning simple pantry items into practical and delicious meal solutions.

## Technologies Used

This project utilizes key technologies and services to deliver a robust AI-driven solution.

* *IBM Cloud Lite Services:* [Mention specific services if you know them, e.g., IBM Watson Assistant, IBM Cloudant, etc. If not, you can keep it general.]
* *IBM Granity:* A mandatory component used for [explain how you used IBM Granity, e.g., for vector indexing, RAG system, etc.].
* *Python:* The core programming language for the agent's logic.
* *Jupyter Notebook:* The primary environment used for development and demonstration of the RAG system.

## Repository Structure

* notebook_RecipePrepAgent-wxnotebook_da_inuz0xvpzi.ipynb: The main Jupyter Notebook where the logic for the Recipe Preparation Agent is developed and demonstrated.
* vector_index.json: This file likely contains the vector embeddings for the recipe data, which are crucial for the RAG system's retrieval component.
* wx_prompt.json: This file is likely used for storing the prompts or system instructions for the AI model.
* project.json: A configuration file for the project.
* Barkavi's-sandbox.zip: The original zipped file containing the project's assets.

## How to Run the Project

To run this project, you will need a Python environment with Jupyter Notebook installed.

1.  *Clone the repository:*
    bash
    git clone [https://github.com/Barkavi26/IBM-SkillsBuild-Internship.git](https://github.com/Barkavi26/IBM-SkillsBuild-Internship.git)
    
2.  *Navigate to the project directory:*
    bash
    cd IBM-SkillsBuild-Internship
    
3.  *Open the Jupyter Notebook:*
    bash
    jupyter notebook
    
    This command will open a browser window.
4.  *Launch the notebook:* Click on notebook_RecipePrepAgent-wxnotebook_da_inuz0xvpzi.ipynb to open and run the code cells.

*Note:* Ensure you have the necessary dependencies installed. You may need to run pip install [package-name] for any libraries used within the notebook.

## Author

* *Barkavi26* - [Link to your GitHub profile](https://github.com/Barkavi26)
