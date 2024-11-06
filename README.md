# learning shell
This is a testing purpose to edit code

## sed commands
syntax : sed -i -e operation1 -e operation2 file
Ex: sed -i -e '/root/ d' -e '2d' file

note - if we dont give -i option then it will make changes on the output not on the file
 sed -e '/root/ d' /etc/passwd
 sed -e '/root/ a hello world' /etc/passwd
 sed -e '/root/ i hello world' /etc/passwd
 sed -e 's/root/ADMIN/' /etc/passwd

