---
layout: post
title: General VO CheatSheet
date: 2022-04-14
author: Shadow Walker
tags: [OPSP, CheatSheet]
toc: true
comments: true
---

## BQ

### Self Intro


### Why Company

First, XXX is a **big company. It has a lot of users**. The products in XXX have a huge impact. So if I get a chance to contribute to XXX’s projects it would make me feel very proud of myself. 

Second, XXX is **a great place for career development and personal growth**. There are lots of experienced engineers in XXX. I’m excited about this job opportunity, as it would allow me to collaborate and learn a lot from these experienced engineers. I also heard that XXX provides resources to provide skill training to improve employees’ skills. 
		
Third, XXX **has a great working environment**. I love the values of XXX. XXX is a company that believes in diversity and equity. XXX actively recruits people from diverse backgrounds to build a supportive and inclusive workplace. Work there will make me have a sense of belonging.

### Mistake/Conflict (PHP-Firebase)

- Situation

	When I worked as an intern in 3to1, our team **started a new project**. The project manager decides to use PHP as our backend language since most people feel comfortable with it. 

- Task

	As the requirements grew, I realized that **PHP was not the best choice** for our project. It was easy to start with, but not extendable and suitable for our project. 

- Action

	I did a lot of research and finally found **Google Firebase was the best choice** for our use case. It was a **brand new backend server** at that time, and it was very powerful. It had **comprehensive documentation and was easy to start with**. 

- Result

	I **persuaded my supervisor** to use Google Firebase and migrated our project to it successfully. If I had another chance, I would **first do some research and discuss with teammates** to decide which technology to use before starting to work on a project. 	
### Solve a problem (reproduce bug)

- Situation

	I remember when I did the internship in American Family Insurance, I **met a very difficult bug**. 

- Task

	The **application crashed randomly whenever the user input some policy numbers**. The problem did not always happen so it was v**ery hard to reproduce**. At first, I thought maybe some of the policy numbers triggered some bugs related to functions, but that was not the case. 

- Action
	
	I read through the code and tried all the possible edge cases in my mind but still **failed to reproduce the bug.** In the end, I **asked the person who reported the problem** to help reproduce this issue, and finally figured out how the bug happened.  
	
- Result

	It was not about the numbers, but due to some of the **special characters** within the numbers that cannot be handled by the program. I **modified the program to handle those special characters** and solved the problem. 

### Challenge (take new project)

- Situation

	When I did the internship in Amfam, a work **colleague left unexpectedly**. He had been responsible for a project for a long time. 

- Task

	My supervisor asked for a volunteer to take ownership of the project, and I decided to take it. To be honest, **I prefer to work under pressure** and saw this as an opportunity to help out the company in their hour of need. 

- Action

1. After taking the project, I **read through the project plan** and user requirements. Although the **timeline was really tight**, I realized that we could still catch up and finish this project on time. During our scrum meeting, I pointed out that to catch up the deadline, we should **focus on the primary functions of this program** and put the most important needs in the priority. I created **a new plan** based on our situation. I also **break the whole development timeline into several parts** and set up deadline for each one of them. With my plan, I delivered the project successfully within the budge of time. 

2. After taking the project, I realized the **backend technology he used was outdated**, and couldn't handle large requests. I **read through the project thoroughly and then created a project plan**. I decided to use Google Firebase as our backend server, and I persuaded my manager to use it. With the efforts I made, I **delivered the project within the budget on time**. 

- Result

	My supervisor was **satisfied** with my work and effort, and **appreciated my commitment** to deliver this important project on time. 
	
### Conflict 2 (Flutter-Native iOS developing)

- Situation

	When I worked as an intern in 3to1, our team **was planning to build an app** based on our webiste. Our manager suggested to use **Google Flutter**. Flutter is a framework that allows building mobile apps for **both iOS and Andriod platform.** Our team thought it was convnient, so we decided to use it. 

- Task

	As the requirements grew, I realized that **Flutter was not the best choice** for our project. It was easy to use, but it was **too new**. None of our teammates have any experience of using it. And there are **so few demo** projects in the market. More importantly, after several testing, I realized that the **performance is disappointing**. It was also hard to adjust the envrionment for both platforms. 

- Action

	I did a lot of research and finally found **Google Flutter** may not be a reasonable choice for our app. It was much safer to **switch to native iOS developing** which used Swift on Xcode. The native iOS developing will not deliver our product on both Andriod and iOS platform, but it will **guarantee a stable and extendable iOS app**. 

- Result

	I **persuaded my supervisor** to switch to native iOS developing. It was a hard choice. We will ending up only have an iOS app instead of apps on both platforms, but it was far better than failure products on both platforms. My supervisor agreed with my proposal, and because of my decision, we deliverd the app **on time**. 
	
### Conflict 3 (Production and patch up)

FollowUp 不要说 manager 的不是. 

- Situation

	When I did the internship in Amfam, we were pushing a **new version onto our production server**. However, **during the testing, it showed a bug** that we had not yet fixed. 
	
- Task

	My supervisor did a code review. After **comparing the new version code to the old one**, he believed that **the new changes couldn't lead us to this bug**. He told us, the production sever and the testing server had **differnt environment settings**. Although the testing server had showed some bugs, he believed that the program would be ok in the production server. Although I have doubts about his judgement, I **believe that my manager** was always able to see a bigger picture than me. As a result, I **decided to follow** his instructions. 

- Action

	Although, we decided to push the code onto production server on time. I **spent my own time fixing this issue** on the testing server. To be honest, although I **decided to follow my manager**, I always prefer to have a backup plan in case of need. After digging it out, I figured that this problem could also be **happening in the production server**. First, I **fixed the problem on the testing server**. Then I created a report and set up a meeting with my manager to **demonstrate why this problem could also happen in the production server and why we should fix this problem**. My manager **agreed** with my solution and **pushed my version of code onto the production server** on time. 
	
- Result

	My manager was **satisfied** with my work and effort, and **appreciated my commitment** to my work. Due to my backup plan, we were able to deliver our project **sucessfully on time**. 
	
### PHP vs Firebase

**Choose Firebase:**

- If you need to use real-time database eg. online chatting app
- if have not worked on server side programming languages before
- Want to build the backend part of the app in shorter time. Firebase simplifies the development process
- Free if you have users less in ten thousands of users (assuming you don't use intensive data storage)

**Choose PHP/MySQL when**

- If you like the concept of relational database
- If you are familiar with a server-side programming language
- If you like to use SQL queries
- Will be cheap if you have more than hundreds of thousands of users or you use intensive data storage.

Generally if your project is used by many users firebase is expensive(eg. above 10,000 monthly active users), but for a simple project it is easy to setup, saves you server cost.
	

## Data Structure

### LinkedList

三道题即可:  
       
- LRU (LC146)   
- MergeSort  
- random pointer (已TTT). 

### PriorityQueue

* 物理结构：数组［A，B，C］
* 逻辑结构：complete tree，
* 以最小堆：父节点小于子节点，左子节点和右子节点不一定谁谁大谁小
* poll()：O(lgn)
* remove()＝在一维数组里删除一个元素：O(n)
* add：O（lgn）
* search：O(n）

### TreeMap

red-black tree

- remove : O(lgn)
- search: O(lgn)
- add: O(lgn)

**When we need to remove or search an element frequently, use treeMap rather than PriorityQueue.**

### HashMap/HashSet

-  for add, remove and look-up operation of HashSet/HashMap takes O(1) time.

**How HashMap work?**

- **Array + LinkedList/red-black tree**

- HashMap maintains an array of the bucket. But when we store or retrieve any key-value pair, HashMap calculates the index of the bucket for each and every operation. **The Key object is used to calculate the index of the bucket**. 

- a hash value is calculated using the key’s hash code by calling its **hashCode()**  method. This hash value is used to **calculate the index in the array** for storing the Entry objects.

- When two objects have the same hashcode, they are put into the **same bucket** using a **linkedList**. If the linkedlist is too long, it will be converted into a red-black tree. 

### Tree 

![](https://lh3.googleusercontent.com/pw/ACtC-3dUCfqUIZvnpi1QE5ITj7I_RKWrzw48ara9uZvKtGbsi0bdAzSyae-sIei1xv4bdu82Ct7BwiY2jal4XOjcj8jqE33tZtsq1hR-ueLfBJ-njcf3Qfg7oeSyhiNXcVauySfs0oHITFB1RAXQX0Ykl9tF=w970-h450-no?authuser=0)

**InOrder**

(Left, Root, Right) : 4 2 5 1 3

```java
    /* Given a binary tree, print its nodes in inorder*/
    void printInorder(Node node) 
    { 
        if (node == null) 
            return; 
  
        /* first recur on left child */
        printInorder(node.left); 
  
        /* then print the data of node */
        System.out.print(node.key + " "); 
  
        /* now recur on right child */
        printInorder(node.right); 
    } 
```

---

```java
public List<Integer> inorderTraversal(TreeNode root) {
    List<Integer> res=new ArrayList<>();
    if (root==null) return res;

    Stack<TreeNode> stack=new Stack<>();
    TreeNode curr=root;

    while(curr!=null || !stack.isEmpty()){
        while (curr!=null){
            stack.push(curr);
            curr=curr.left;
        }
        curr=stack.pop();
        res.add(curr.val);
        curr=curr.right;
    }
    return res;
}
```



**PreOrder (DFS)**

(Root, Left, Right) : 1 2 4 5 3

```java
    /* Given a binary tree, print its nodes in preorder*/
    void printPreorder(Node node) 
    { 
        if (node == null) 
            return; 
  
        /* first print data of node */
        System.out.print(node.key + " "); 
  
        /* then recur on left sutree */
        printPreorder(node.left); 
  
        /* now recur on right subtree */
        printPreorder(node.right); 
    } 
```

---

```java
public List<Integer> preorderTraversal(TreeNode root) {
    LinkedList<Integer> ans = new LinkedList<>();
    Stack<TreeNode> stack = new Stack<>();
    if (root == null) return ans;

    stack.push(root);
    while (!stack.isEmpty()) {
        TreeNode cur = stack.pop();
        ans.add(cur.val);
        if (cur.right != null) {
            stack.push(cur.right);
        } 
        if (cur.left != null) {
            stack.push(cur.left);
        }
    }
    return ans;
}
```


**PostOrder**

(Left, Right, Root) : 4 5 2 3 1


```java
    /* Given a binary tree, print its nodes according to the 
      "bottom-up" postorder traversal. */
    void printPostorder(Node node) 
    { 
        if (node == null) 
            return; 
  
        // first recur on left subtree 
        printPostorder(node.left); 
  
        // then recur on right subtree 
        printPostorder(node.right); 
  
        // now deal with the node 
        System.out.print(node.key + " "); 
    } 
```

---

```java
public List<Integer> postorderTraversal(TreeNode root) {
	// 这里非常重要要用LinkedList, 因为下面要用addFirst. 
	LinkedList<Integer> ans = new LinkedList<>();
	Stack<TreeNode> stack = new Stack<>();
	if (root == null) return ans;
	
	stack.push(root);
	while (!stack.isEmpty()) {
		TreeNode cur = stack.pop();
		ans.addFirst(cur.val);
		if (cur.left != null) {
			stack.push(cur.left);
		}
		if (cur.right != null) {
			stack.push(cur.right);
		} 
	}
	return ans;
}
```

**Balanced Binary Tree**

a binary tree in which the left and right subtrees of every node differ in height by no more than 1.

![](https://lh3.googleusercontent.com/pw/AM-JKLU0tyNnSzNLcRCQXTE-9FPddX49SrLzoY17Oci5hZGUj2lrzhmAPp6mIXDnxVXnBVSy29t_UkYLPXPE9mDqqxQGO0XXSuhtmYvQBiei8bpSMWe76dPjdX1N5WLPCInD43lHtQQNk0Ytr3CUIeDNhDiI=w342-h221-no?authuser=2)

**Full Binary Tree**

![](https://lh3.googleusercontent.com/pw/AM-JKLVH3C5BPTQXvefIRKc8jmQrhQ_gfhogQsRev2PQ1vuId77KME6EtZ9MKAAuka57iQjES4ReTSljycc-QZxYdPNcNx0S9lDudC2L7WPIDfUShwG_a8bvkNZScwum6HVzJCQl2hkfJxhqMvFJUAhWVsS_=w320-h300-no?authuser=2)

**Complete Binary Tree**

![](https://lh3.googleusercontent.com/pw/AM-JKLWjAFO77pgAh8ppF1JvwBisHva-1g_Q7s-jNLTYPJWVOPFL-NnAfVnNtnX5dBxYJ4aCLGIMcDxQUbIg3yzgZWZNJgjS3D_xiOliuNvJKtk44FjxUoUgK8XwFgG0s4ukcgVs1CpXJKntOZ5SZJ_mn8jc=w322-h248-no?authuser=2)

### Trie

LC1268, LC588 需要刷熟. 两道都是Amazon 50道会员. 

```java
class Trie{
	Map<Character, Trie> links = new HashMap<>();
	boolean isEnd;
}
```

	

## Algorithm

### Space Complexity

Data | SC
---|---
`Map<Integer, Integer>`| O(n)
`Map<Integer, List<Integer>>` | O(n^2)   O(nm)
`Map<Integer, List<List<Integer>>` | O(n^3)
`int[][]` | O(n^2)
`int[]` | O(n)


### Sorting

- Time Complexity: Bubble Sort, Insertion Sort, Select Sort O(n^2), MergeSort, QuickSort O(nlogn)
- Space Complexity: Bubble Sort, Insertion Sort, Select Sort O(1), MergeSort O(n), QuickSort O(1). 

### Bubble Sort

Time: O(n^2),  Space: O(1)

1. Repeatedly swapping the adjacent elements if they are in wrong order.
2. First go from 0 to n-1, keep swaping so we have the largest element in the end. 
3. Then go from 0 to n-2, and so on. 
4. If no swap happens, then break loop. It will take at most n-1 times to traverse the array. 


### Selection Sort

Time: O(n^2),  Space: O(1)

Repeatedly finding the minimum element from unsorted part and putting it at the beginning. 

### Insertion Sort

Time: O(n^2),  Space: O(1)

1. Iterate from arr[1] to arr[n] over the array.
2. Compare the current element (key) to its predecessor.
3. If the key element is smaller than its predecessor, compare it to the elements before. Move the greater elements one position up to make space for the swapped element.

### Merge Sort

Time: O(nlgn),  Space: O(n)

- break the given array in the middle. 
- Keep breaking each part until we get each subarray with single element. 
- Since each array only have one element, so they are all sorted. Then we merge these arrays back together. It only takes O(n) to merge two sorted arrays. So the divide will take O(logn), which gives us total time complexity of O(nlogn).

```java
public static void mergeSort(int[] arr){
    int[] temp =new int[arr.length];
    internalMergeSort(arr, temp, 0, arr.length-1);
}
private static void internalMergeSort(int[] arr, int[] temp, int left, int right){ 
    //当left==right的时，已经不需要再划分了
    if (left<right){
        int middle = (left+right)/2;
        internalMergeSort(arr, temp, left, middle);          //左子数组
        internalMergeSort(arr, temp, middle+1, right);       //右子数组
        mergeSortedArray(arr, temp, left, middle, right);    //合并两个子数组
    }
}
// 合并两个有序子序列
private static void mergeSortedArray(int arr[], int temp[], int left, int middle, int right){ 
    int i=left;      
    int j=middle+1;
    int k=0;
    // Sort and combine into a new temp array. O(n)
    while (i<=middle && j<=right){
        temp[k++] = arr[i] <= arr[j] ? arr[i++] : arr[j++];
    }
    while (i <=middle){
        temp[k++] = arr[i++];
    }
    while ( j<=right){
        temp[k++] = arr[j++];
    }
    //把数据复制回原数组
    for (i=0; i<k; ++i){
        arr[left+i] = temp[i];
    }
}
``` 

### Quick Sort

Time: O(nlgn),  Space: O(1)

- Select a 'pivot' element from the array and partitioning the other elements into two sub-arrays, one subarray with elements less than the pivot element, the other with elemnts greater or equal to the pivot element. 
- The sub-arrays are then sorted recursively until only one element is left in each subarrays. 

```java
public static void quickSort(int[] arr){
    qsort(arr, 0, arr.length-1);
}
private static void qsort(int[] arr, int left, int right){
    if(left<right){
        int pivot = partition(list, left, right);
        qSort(list, left, pivot-1);
        qSort(list, pivot+1, right);
    }
}
public static int partition(int[] arr, int left, int right) {
    int pivot = arr[left];
    // 1. move pivot to end
    swap(arr, left, right);
    int store_index = left;

    // 2. move all smaller elements to the left
    for (int i = left; i <= right; i++) {
      if (arr[i] < pivot) {
        swap(arr, store_index, i);
        store_index++;
      }
    }

    // 3. move pivot to its final place
    swap(arr, store_index, right);
    return store_index;
  }

  public static void swap(int[]arr, int a, int b) {
    int tmp = arr[a];
    arr[a] = arr[b];
    arr[b] = tmp;
  }
```

### Two Pointers | Binary Search

```java
while (left < right) {
     int m = left + (right - left)/2  
     if(nums[m] < target) {
    	Left = m + 1  
    } else {
	Right = m 
   }
}
```

### Topological Sort

1. Build graph
2. set indegree for each node. 
3. put the nodes with zero indegree into the queue. 
4. poll queue, update indegree, if indgree is zero, put into the queue. 
5. return true if the element polled equals the total node count. 

### Dijkstra

同上. 不需要背, 但算法原理需要CC. LC743.

### Prim

LC1135 在 会员50道理. 所以这个也需要掌握. 

###  Tarjan

[Tarjan算法](https://www.cnblogs.com/nullzx/p/7968110.html)

## OOD

### 要点

- 先确认需求, function 会写不会写先 放一边, OOP一定要考虑全. 每一个都问一下需不需要支持.
- 然后确认所有case, 一定要跟面试官确认所有的可能需求, 然后确认edge case.
- 最后再开始写代码. 千万不要着急写代码.
	- 先不要写function里面的东西, 把function**根据上面的需求一个一个都列出来**, retrun 和 parameter写出来. 
	- parameter 能用id用id, 用不了id, 再用string, int之类. 
	- 必须有**unique id**, 
	- 必须有增删改查. 
	- **Parameter**从用户角度出发
	- Service class应该是给所有用户共同调用, 而不是给每个客户都单独创建一个service.  
	- 考虑Service 的时候, 注意Service 应该是一个Singleton 一直在run, 而不是在被call的时候才突然启用. 
	- 注意var **命名规范, 多写注释.** OOD必须多解释, 不然面试官不懂在干什么. 
	- Service 方法一定要写**public**. 

## Grammar

- Deque 语法不熟, 掌握相应基本操作. 
- Random 语法 (LC 384)


```java
String[] pathArr = filePath.split("/");
```

```java
// substring
String s="SachinTendulkar";  
System.out.println(s.substring(6));//Tendulkar  
System.out.println(s.substring(0,6));//Sachin  
```


## Edge Case

不需要背, 但靠前需要扫一眼: 

1. array为null或者len是0
2. array中的元素有重复
3. string为null或者是""
4. string的字符是否有重复
5.  string的字符是否存在特殊字符. 
5. int型的数字应该注意转换成long来计算防治越界
6. int型的数字要考虑正负，0，和最大值及最小值
7. 栈要检查是否为空
8. 链表一般要开一个新节点以便回归头节点
9. 链表要注意next是否为空

## After Interview


* What is your code language
* What is day to day life
* How to onboarding new team member 