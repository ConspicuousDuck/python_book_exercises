Step by step

ex01

mkdir my_folder
cd my_folder
touch one.py two.py (creates two files)

vim one.py (text edits the file one.py)
i(insert text two)
print('This is file one')
<ESC key>
wq + ENTER (saves and exits vim)

vim two.py (text edits the file two.py)
i(insert text to file)
print('This is file two')
<ESC key>
wq!(saves and exit vim)

(back to terminal)

python3 one.py
->This is file one

python3 two.py
->This is file two

-All done ex01-


