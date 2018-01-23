# ~ (WIP)

#### Developer:
Adrian Agnic

##### Current Usage Instructions:
* Requirements:
  * python3
* Run:
  ```commandline
  cd tilde/python/
  ```
  Enter Python3 interpreter:
  ```commandline
  python
  ```
  ```commandline
  from blockchain.blockchain import Blockchain
  bc = Blockchain()
  bc.add_new_block('Hello World', 'me', 'you')
  bc.chain
  ```

#### TODO:
* profiling
* refactor variable/method names and access, refactor conditionals
* serialize objects for file write
* unittests
* CLI
* Dockerfile
* dev server
