


- ``` #!/bin/bash ```
- ``` prefix= $1 ```
- ``` start= $2 ```
- ``` end=$3 ```
- ``` if ((i=$start; i<end; i++)) ```
- ``` do ```
- ```mkdir "prefix$i" ```
- ``` done ```