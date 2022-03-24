# Zookeeper Frequently Used Commands
- Zookeeper Client site commands
  - start
    ```shell
      bin/zkCli.sh -server server1:2181
    ```
  - check zookeeper list
    ```shell
    ls -s /
    ```
  - create node
    ```shell
    create node /test "test for study zookeeper"
    ```
  - check node information 
    ```shell
    get -s /test
    ```
  - monitor registration 
    ```shell
    get -w /test
    ls -w /test 
    ```
  - delete node
    ```shell
    deleteall /test
    ```
    