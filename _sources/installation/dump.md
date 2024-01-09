# Load Dumps (using pgadmin)

In pgadmin, open the Tools menu and select PSQL Tool. 
![](img/dump.png)

You will see the following window.

![](img/beforedump.png)

In the window that you see, paste the following command: 
`\i <path to your file>` and press enter. 

![](img/dumpcode.png)

After the dump is loaded, you will see something like this:

![](img/afterdump.png)

Once the process is complete, you will see the `fakedata` schema and `testindex` table under the `schema`. (Please refresh it like in the image below)

![](img/dumprefresh.png)

I have listed some of the issues that Windows users in session 2 experienced. 

- You need to use a forward slash in the file path as that is how file path looks in windows(e.g., `\i 'C:/dumpname.sql'`)

If you are getting any permission-related issues;

- You want to start pgadmin as an administrator.
- You might also want to try to move the file from current folder to `C:/` so the path to the file is `C:/dumpname.sql` and then try `\i 'C:/dumpname.sql'` in pgadmin.
- Having folder names with spaces is not a good practice, so if you have so, please change the folder name without spaces. The previous step of moving the dump (.sql file) to `C:/`  will help no matter what.