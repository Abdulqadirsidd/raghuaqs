# learning shell
This is a testing purpose to edit code

office working and comitting and pushing
for the confirmation
Always update the project
always mark codes as completed
Linux doesn't require file extension
Code is developed in windows/MAc. These OSs does require file extension, else they will be able to help
Addition to this , editor also would be needing this extension because to understand / suggest you what code you are writing.
Coming to shell, we provide extension usually as .sh to tell that is a shell script or .bash to exclusively tell that is bash shell script ( not neede

## Sed command
syntax : sed -1 -e opertaion1 -e operation2 file
Ex: sed -i -e '/root/ d' -e '2d' file

Note - if we don't give 'i' option then it will make changes on the output not on the file

'''shell
sed -e '/root/ d' /etc/passwd
sed -e '/root/ a hello world' /etc/passwd
sed -e '/root/ i hello world' /etc/passwd
sed -e '1 i hello world' /etc/passwd
sed -e 's/root/ADMIN' /etc/passwd
