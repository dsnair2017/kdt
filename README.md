# kdt
KDT Framework

1. Setup git and clone this repository.
2. Ensure Java JDK 1.8 or later is installed.
3. Install Eclipse (Eclipse auto-installer may have a remote host offline as of 12/12. Full installation may be necessary).
4. Ensure Eclipse recognizes JDK 1.8 or later (Window->Preferences->Java->Installed JREs).
5. Select Maven settings Window->Preferences->Maven-> Download Artifact Sources and Window->Preferences->Maven-> Download Artifact JavaDoc.

Eclipse project setup:
1. In Eclipse, File->Import->Git->Projects from Git.
2. Choose: Existing local repository.
3. Browse for and select the downloaded git repository folder (contains the .git file) by pressing Add.
4. Check the folder's checkbox and press Finish.
5. Select the 'Import as general project' radio button.
6. Provide a project name, press Finish.
7. Right-click the project in Package Explorer, go to Configure->Convert to Maven Project.
