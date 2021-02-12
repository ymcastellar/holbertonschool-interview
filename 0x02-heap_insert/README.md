# 0x02. Heap Insert

## More Info

### Data structures
Please use the following data structures and types for binary trees. Don’t forget to include them in your header file.

#### Basic Binary Tree
```
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};
```
#### Max Binary Heap
```
typedef struct binary_tree_s heap_t;
```
## Author ✒️

_Developed by_

**Yoyman Castellar** :computer: :man: 

- Github - [ymcastellar](https://github.com/ymcastellar)
- Twitter - [@CastellarYoyman](https://twitter.com/CastellarYoyman)
- LinkedIn - [yoyman-castellar](https://www.linkedin.com/in/yoyman-castellar/) 