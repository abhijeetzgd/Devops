# Initialize a new Git repository
git init

# List all files, including hidden ones
ls -a

# Check the status of the repository
git status

# Create a new file named hello.txt
touch hello.txt

# Write "hello dosto" to hello.txt
echo "hello dosto" > hello.txt 

# Display the contents of hello.txt
cat hello.txt 

# Check the status again to see changes
git status

# Create two new files, nibba.txt and nibbi.txt
touch nibba.txt nibbi.txt

# Check the status to see all files
git status

# List files in the current directory
ls

# (Optional) Clear the terminal
git

# Clear the terminal screen
clear

# Check the status again
git status

# Stage nibba.txt for commit
git add nibba.txt 

# Check the status to see staged files
git status

# Commit changes with a message
git commit -m "nibba commited"

# Set global Git username
git config --global user.name "abhijeetzgd"

# Set global Git email
git config --global user.email "abhijeetzgd@gmail.com"

# Commit again after setting user info
git commit -m "nibba commited"

# Check the status of the repository
git status

# Check the status of nibba.txt specifically
git status nibba.txt 

# Stage nibbi.txt for commit
git add nibbi.txt 

# Stage hello.txt for commit
git add hello.txt 

# Check the status to see staged files
git status

# Remove hello.txt from the working directory
rm hello.txt 

# Check the status after removal
git status

# Restore hello.txt from the last commit
git restore hello.txt 

# List files to confirm hello.txt is restored
ls

# Check the status again
git status

# Commit nibbi.txt with a message
git commit -m  "commiting Nibbi" nibbi.txt 

# List files to see current directory
ls

# Check the status again
git status

# Commit hello.txt with a message
git commit -m "commiting hello" 

# Check the status once more
git status 

# List files in the directory
ls

# Check the status to see if any changes exist
git status

# Write "me nibba hu" to nibba.txt
echo "me nibba hu" > nibba.txt 

# Check the status to see changes
git status

# Stage nibba.txt for commit
git add nibba.txt 

# Commit nibba.txt with a message
git commit -m "commited nibba" nibba.txt 

# View commit history
git log

# List branches in the repository
git branch

# Clear the terminal screen
clear

# List branches again to confirm
git branch

# Create and switch to a new branch named dev
git checkout -b dev

# List files in the current directory
ls

# Append "I am nibbu" to nimbu.txt
echo "I am nibbu" >> nimbu.txt

# Display the contents of nimbu.txt
cat nimbu.txt 

# Check the status to see changes
git status

# Stage nimbu.txt for commit
git add nimbu.txt 

# Commit nimbu.txt with a message
git commit -m "added new nimbu" nimbu.txt 

# List files to see current directory
ls

# View commit history
git log

# Clear the terminal screen
clear

# Switch back to the master branch
git checkout master 

# Check the status of the master branch
git status

# List branches to confirm current branch
git branch

# List files in the current directory
ls

# View commit history in a compact format
git log --oneline

# Switch back to the dev branch
git checkout dev 

# View commit history in a compact format for dev branch
git log --oneline

# Display command history
history
