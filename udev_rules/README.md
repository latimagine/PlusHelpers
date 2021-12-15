Notes
=====

The revopoint3d rules file contains rules for the `Surface HD 20`. Add rules for other *product id* if needed.

Install
=======

~~~shell
for file in *.rules
do
    sudo cp $file /etc/udev/rules.d/.
done
~~~