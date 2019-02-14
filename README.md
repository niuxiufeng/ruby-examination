# ruby-examination

## 1. heredoc

 use `<<` as input redirection. 
 ### example 
 ``` 
 puts <<'EOF'  # EOF is a single word ,must same as the end singnal
 hello,  
 ruby  
 EOF           # should same as the word after << ,any word is ok
 here 
``` 

### result
 ```
 hello,/nruby/n
 ```
 
