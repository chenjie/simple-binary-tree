# simple-binary-tree
A simple example of Java binary tree. It also generates a String representation of the tree.

## Getting Started

### Prerequisites

* JDK 8
* Eclipse

### Download source code
```
# Change to HOME directory
$ cd ~

# Clone this repo
$ git clone https://github.com/jellycsc/simple-binary-tree.git
```

### Open this project in Eclipse
The following instructions are based on Eclipse 4.6.1 on macOS.
```
File -> Open Projects from File System... -> Directory... -> [HOME/simple-binary-tree] -> Finish -> Run BinaryTree.java
```

### Example BinaryTree
```
BinaryTree tree = new BinaryTree();
System.out.println(tree);
tree.addValue("A", null, false);
System.out.println(tree);
tree.addValue("B", "A", false);
System.out.println(tree);
tree.addValue("C", "B", true);
System.out.println(tree);
tree.addValue("D", "A", true);
System.out.println(tree);
```

### String representation
```
()
(A () ())
(A () (B () ()))
(A () (B (C () ()) ()))
(A (D () ()) (B (C () ()) ()))
```

## Authors

| Name             | GitHub                                     | Email
| ---------------- | ------------------------------------------ | -------------------------
| Chenjie Ni       | [jellycsc](https://github.com/jellycsc)    | nichenjie2013@gmail.com

## Thoughts and future improvements

* Since this is a rather simple beginner's project, no further improvements will be made.

## Contributing to this project

1. Fork it [![GitHub forks](https://img.shields.io/github/forks/jellycsc/simple-binary-tree.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/jellycsc/simple-binary-tree/fork)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to your feature branch (`git push origin my-new-feature`)
5. Create a new Pull Request

Details are described [here](https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project).

## Bug Reporting [![GitHub issues](https://img.shields.io/github/issues/jellycsc/simple-binary-tree.svg)](https://github.com/jellycsc/simple-binary-tree/issues/)

Please click `issue` button above↑ to report any issues related to this project  
OR you can shoot an email to <nichenjie2013@gmail.com>

## License
This project is licensed under the MIT License - see [LICENSE](LICENSE) file for more details.

