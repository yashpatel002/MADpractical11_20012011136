# MADpractical11_20012011136

AIM: Create Note Android Application that can add Note, edit Note, delete Note, and set reminder date & time of note. By using Broadcast Receiver, AlarmManager set reminder of note. By using SQLite, store all notes data.

1.Create two Activities like MainActivity, NoteViewActivity according to below UI design.

2.Use RecyclerView Code from Practical-9 to display Note Data.

3.Use Broadcast Receiver, Time Picker Dialog, service & AlarmManager code from Practical-7

4.Create Note class with member variables like id, title, subTitle, Description, modifiedTime, reminderTime:Long, isReminderEnable:Boolean & create membor methods like getCurrentDateTime(), getMillis(), setReminder(), isValid(), getReminderText(), saveNote(), getHour(), getMinute(), calculateReminder() 

5.Create DatabaseHelper Class for SQlite with member methods like insertNote(), getNote(id), getAllNotes(), getNotesCount(), updateNote(), deleteNote().

6.Use Databinding in gradle file to easy way integrate xml into kotlin file

7.Use Material 3 design for UI

8.create class NotesData with companion object and it will store column name of table and create table query.

9.Create NoteViewActivity. It will show while reminder notification is turned up and user click on notification. It will also show when click on Note in recyclerView. After clicking on notification NoteViewActivity should be open with full description of that note. 

10.Note should be deleted by clicking on icon of Delete. Note should not be added if any one field of note is empty.

11.Some notes have reminder time so add reminder time in alarmManager with note id & it should be receive in broadcast receiver & in broadcast receiver notification should be generated with title & description of note.

12.If More than one notes have reminder time then notification should be displayed for each note separately.

13.Create Common Custom Dialog Box for add, edit note.

14.Create RecyclerView & its adapter to display all notes.


## Android Studio:
![Android studio](https://user-images.githubusercontent.com/110655668/202735030-c3496025-ffb6-4cde-a9b1-7d8d72764545.png)

## Light Mode:
![1](https://user-images.githubusercontent.com/110655668/202735284-6cad267e-b61a-4f68-9169-746d93edcf7b.png)
![light1](https://user-images.githubusercontent.com/110655668/202735400-7be7a63c-74af-410b-bba9-95f02f5881f7.png)
![light2](https://user-images.githubusercontent.com/110655668/202735443-83c6466e-e0eb-4218-86aa-d05d72ceb496.png)
![Light3](https://user-images.githubusercontent.com/110655668/202735449-17728d92-9998-4b67-9c4b-708b68f5cf34.png)
![Light4](https://user-images.githubusercontent.com/110655668/202735454-e9577fd7-0dc8-4546-86c4-abc46e4c58c4.png)
![Light5](https://user-images.githubusercontent.com/110655668/202735464-3f3f78c5-8d13-4fdf-811a-70c254cdf206.png)


## Dark Mode:

![Dark1](https://user-images.githubusercontent.com/110655668/202736488-fdebe20b-f45c-46f0-b76c-beb91e0c675a.png)
![Dark2](https://user-images.githubusercontent.com/110655668/202736690-ddfead24-a25b-4ce3-ab72-6935cccbd428.png)
![Dark3](https://user-images.githubusercontent.com/110655668/202736700-536bb273-7a71-4dbb-8c78-665dce5d3168.png)
![Dark4](https://user-images.githubusercontent.com/110655668/202736704-5de39195-ac53-4f67-942e-8613e8f91377.png)
![Dark5](https://user-images.githubusercontent.com/110655668/202736711-b52630a9-3719-4165-8bee-d471e690c174.png)


