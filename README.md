# Level 0

To solve this level and get the password I used ls and cat command.

    -- > ls
  
    -- > cat readme

# Level 1

I searched for how to read files starting with '-' and used th information to solve the first level

    -- > cat < -

# Level 2

For this level I just enclose the entire name including space in apostrophe(') to pass it as a single argument

    -- > cat 'spaces in this filename'

# Level 3

For this level I first change my directory to inhere

    -- > cd inhere

Then I list all the directories using (-a) which I found by looking at the manual for ls command

    -- > ls -a
    
Then I simply open the hidden files using cat command

    -- > cat .hidden

# Level 4

My first thought was to open individual file but that would not have worked if the number of files was really large
So I searched for way to find file types and finally used the following command to find out my desired file

    -- > file ./-file*

# Level 5
