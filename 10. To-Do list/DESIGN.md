A simple to-do application.

### Features
1. Add task.
2. Remove task.
3. Update task details.
4. Archive task - not removed, but hidden from view.
5. Search and filter tasks by - is archived, is completed, tags, due date range, title and description (full text search).
6. Real-time synchronization of changes over web socket.

### Data model.
1. Task:
    * Title.
    * Description (optional) (Markdown formatting).
    * Due date (optional).
    * Tags (unique per project) (optional).
    * Is completed - boolean.

2. Project
    * Title.
    * Description (optional).
    * Color
    * Icon.

3. Tag
    * Title
    * Color