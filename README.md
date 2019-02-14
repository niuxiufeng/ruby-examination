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
 
## 2. step, times, upto, downto methods

 ### step
 object.step(limit, stepon){ |x|  
 do something...  
 }  
 when loop (object + stepon * index) > limit ,exit the loop **index** from 0, add 1 step 
 
 ```
 1.2.step(4.8, 1.4){|x|    # 1
 puts x
 }
 ```
 
 ### result
 ```
 1.2
 2.599999999996
 4.0
 ```
 
 ### times 
