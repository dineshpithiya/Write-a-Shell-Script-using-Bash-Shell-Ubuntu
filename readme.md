## how to create shell script

### Connect your ubuntu via terminal
1.	
	> Create new folder or in existing folder using your any editor like nano or vim, create new .sh file [naming convention a you will - more better as per script action]	
	```
		nano xyz-script-name.sh
	```
2.	
	> Write any script Like
	```	
		echo "This is list directory script tested by dinesh pithiya"
		ls
		echo "Directory listing successful"
	```

3.
	> Save and exit
	```	
		ctr+x
		yes and [enter]
	```
4.
	> Run shell script
	```	
		. xyz-script-name.sh
	```
5.
	> Set cronjob and set path for the shell script
	```
		* * * * * aws s3 sync /var/www/source-directory/ s3://bucket-name/
	```