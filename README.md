# DayPost

## Table of Contents
<details markdown="1"> 
<summary>Project Overview
</summary>

Built on the Flask framework, **DayPost** is a real-time messaging application crafted to streamline and enhance swift chat conversations. Its user-friendly interface empowers users to engage in instant messaging effortlessly.

**DayPost**, powered by Flask, establishes a robust foundation for real-time chat applications. This foundation allows users to concentrate on meaningful conversations with friends, colleagues, or anyone they wish to connect with in real time.

**DayPost** contains user-centric features, including a secure login/register system, user-following functionality, and a blog posting feature. It is built for real-time communication and simplifies the process of chatting with others.
</details>


<details markdown="1"> 
<summary>Installation
</summary>

To get started with **DayPost**, follow these steps to install and set up the project in your local development environment:

1. **Clone the Repository**: 
   - Clone the DayPost repository from GitHub using the following command:
     ```
     git clone https://github.com/NeelarghyaK/DayPost.git
     ```

2. **Navigate to the Project Directory**: 
   - Move into the project directory using the following command:
     ```
     cd DayPost
     ```

3. **Create and Activate a Virtual Environment (Optional but Recommended)**: 
   - To manage dependencies effectively, consider using a virtual environment. Use the following commands to create and activate one:

For Windows:
python -m venv venv
venv\Scripts\activate

For macOS/Linux:
python3 -m venv venv
source venv/bin/activate


4. **Initialize the Database**: 
- **DayPost** uses a database to store chat messages and user information. Initialize the database by running these commands:
  ```
  flask db init
  flask db migrate
  flask db upgrade
  ```

5. **Start the Flask Development Server**: 
- Launch the Flask development server with the following command:
  ```
  flask run
  ```

6. **Access DayPost**: 
- Open your web browser and visit http://localhost:8030 to access DayPost locally. You'll see the **DayPost** chat interface.

These instructions assume you have Python and pip installed on your system.
</details>
<details markdown="1"> 
<summary>Usage
</summary>

To use **DayPost** effectively, follow these guidelines:

1. **Registration**: Start by registering for a new account on **DayPost**. Provide the necessary details to create your account.

2. **Login**: After registering, log in to your account using your credentials. DayPost will authenticate your credentials and grant you access to the chat interface.

3. **Chat Conversations**: Use the chat interface to engage in real-time conversations with other users. Select a user from the list, type your message, and click "Send" to initiate a chat.

4. **Receive Messages**: Messages sent to you will appear in the chat interface.

5. **Log Out**: Log out of your account when you're done with your chat session to keep your account secure.

</details>

<details markdown="1"> 
<summary>Contact
</summary>

Feel free to drop suggestions at neelarghyak10@gmail.com
</details>
