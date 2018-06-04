* Find and remove file name contains 'car'

  - find | grep car | xargs rm -f 
  - source links [stackoverflow](https://stackoverflow.com/questions/20858524/delete-a-list-of-files-with-find-and-grep)

* Find first word and exclude second word contains the first

  - grep -nr "\bflask\b" --exclude="flaskweb" .
  
* Find the word exclude the file with some ext postfix
  - grep -nr "flask" --exclude=*.rst
  
