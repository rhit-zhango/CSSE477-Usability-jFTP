# JFTP Usability Lab

## Build and run

Use a full JDK 21 installation with desktop Java support.

### Eclipse

1. Choose **File > Import > General > Existing Projects into Workspace**.
2. Select the extracted project folder and finish the import.
3. Set the project's Java runtime to JDK 21.
4. Open `src/java/net/sf/jftp/JFtp.java` and run it as a Java application.

The project configuration includes the supplied `lib` class folder and excludes
the optional Log4J adapter. Keep `lib` in the project: it contains required
third-party classes and image resources, not just optional dependencies.

### Apache Ant

From the project folder, run:

```text
ant run
```

To build without launching the application:

```text
ant jars
```

Run the resulting application with:

```text
java -jar build/jars/jftp.jar
```

## Using the application

Connect the remote pane to the FTP server provided for the activity. Keep the
local pane on the local filesystem, browse to a file, select it, and use the
Upload arrow. Messages appear in the application's log.

Uploads accept readable regular files. Directories and the parent-directory
entry cannot be uploaded. Directory navigation and creating a remote directory
are still available. Use the Upload button for transfers; drag/drop and clipboard
upload are unavailable in this version.

## Team information

- Enter your team name and team member information below

---

**Team Name**
- Name:

---
**Team Member #1**
1. Team member name:  
2. Your rose-hulman.edu userid: 
3. Your github userid: 

**Team Member #2**
1. Team member name:  
2. Your rose-hulman.edu userid: 
3. Your github userid: 

**Team Member #3**
1. Team member name:  
2. Your rose-hulman.edu userid: 
3. Your github userid: 

**Team Member #4**
1. Team member name:  
2. Your rose-hulman.edu userid: 
3. Your github userid: 

Add additional team member info lines if you have more than 4 on your team
