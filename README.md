# Gamified Task List Widget

Welcome to the Gamified Task List Widget! This interactive widget allows you to manage tasks with a fun and engaging points system. As you complete tasks, you'll earn points and level up, with celebratory balloons appearing each time you reach a new level.

## Features

- **Add Tasks**: Easily add tasks to your list.
- **Complete Tasks**: Check off tasks to earn points.
- **Strike-through Completed Tasks**: Tasks are struck through when marked as completed.
- **Delete Tasks**: Remove tasks from your list without affecting your points.
- **Points System**: Earn points for completing tasks and level up.
- **Level Up**: Celebrate with falling balloons when you reach a new level.
- **Progress Bar**: Visualize your progress towards the next level.

## Requirements

- Python 3.x
- Streamlit (Install via `pip install streamlit`)

## Getting Started

### Run Locally

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/gamified-task-list-widget.git
    cd gamified-task-list-widget
    ```

2. **Install Dependencies**

    Ensure you have Streamlit installed:

    ```bash
    pip install streamlit
    ```

3. **Run the App**

    ```bash
    streamlit run gamified_task_list.py
    ```

    This command will start a local server. Open the URL provided in your browser to interact with the widget.

### Deploying

To make the widget available online, deploy it to a cloud service like [Streamlit Cloud](https://streamlit.io/cloud), [Heroku](https://www.heroku.com/), or any other platform of your choice.

1. **Streamlit Cloud**:
   - Create an account at [Streamlit Cloud](https://streamlit.io/cloud).
   - Follow the instructions to deploy your app using your GitHub repository.

2. **Heroku**:
   - Create a `Procfile` with the following content:

     ```
     web: streamlit run gamified_task_list.py
     ```

   - Deploy your app following [Heroku's deployment guide](https://devcenter.heroku.com/articles/git).

### Embedding in Notion

1. Deploy your Streamlit app to a public URL.
2. In Notion, create an Embed block.
3. Paste the URL of your deployed Streamlit app into the Embed block.

## Contributing

If you'd like to contribute to the development of this widget, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Commit your changes and push them to your fork.
4. Open a pull request to merge your changes into the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please contact [your-email@example.com](mailto:your-email@example.com).

---

Enjoy managing your tasks with a touch of gamification!
