# TQPF
One-Step method to build CRISPR_Base
1.	Whether Windows or Linux, make sure your computer is installed MySQL database successfully.
2.	For Windows, first, download the “CRISPR_Base.sql” file to “D:” disk. Second, login to the MySQL database as root, use the command “source D:\CRISPR_Base.sql”. The database building process will take a few minutes, please wait patiently.
3.	For Linux, first, download the “CRISPR_Base.sql” file into “/home” directory. Second, login to the MySQL database as root, use the command “source /home/CRISPR_Base.sql”. 
4.	If the “CRISPR_Base.sql” file doesn’t locate in the place as above, please change the corresponding file path correctly. If can’t login to the MySQL as root, please delete the first line in CRISPR_Base.sql, select a proper database in MySQL and then use the same command “source D:\ CRISPR_Base.sql” to insert the tables of CRISPR_Base.
