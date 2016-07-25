# fqueue
High perform perisistant queue on file system. 

### How it works

* Based on MappedByteBuffer
* Two types of files: data files and commit files (index files). 

  Data files functions as an AOF log, recording the data push to the fqueue. 
  
  Commit files records the current read position, and current read file.
  

### Future support

* Random access data in queue.

