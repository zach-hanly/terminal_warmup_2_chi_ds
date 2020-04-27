
In this warmup we are going to exercise your newly gained terminal powers.  Open a terminal window, and navigate to where this readme lives.  Then, follow the instructions below.

1. Navigate to folder_4 which lives somewhere in folder_1. Use cd

2. Navigate up one directory to folder_3 using ..

3. Create a text file named your_name_here.txt using touch

4. Add your name and favorite food to the text file

5. Move the file to folder_2

6. Copy and move the file to folder_4

7. Remove the file from folder_2

8. Navigate to root directory

9. Use find to print out the path of your file

10. Navigate to the warmup directory. Make a new copy of folder_1 and all of its subdirectories, and rename it folder_1_copy. Then, delete folder_1 and all of its subdirectories.



```python

"""
1. cd folder_1/folder_2/folder_3/folder_4
2. cd ..
3. touch jane_doe.txt
4.a echo 'Jane Doe' > jane_doe.txt
4.b echo 'burrito' >> jane_doe.txt
5. mv jane_doe.txt ..
6. cp ../jane_doe.txt folder_4/
7. rm ../jane_doe.txt
8. cd /
9. find . -name 'jane_doe.txt'
10a. cd 'path/to/warmupfolder'
10b. cp -r folder_1/ folder_1_copy
10c. rm -rf folder_1
"""
```
