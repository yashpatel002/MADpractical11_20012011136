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
