# pop_back

**Description** : pop_back() function is used to remove the last element from the list container and hence decreases the size of conatiner by 1.

**Example**:
```cpp
    //Run Code To Demonstrate use of list.pop_back()
    #include <iostream>
    #include <list>

    int main(){
        // create a list object containing integers
        std::list<int> my_list{10,20,30,40,50};
        
        std::cout << "Original list : ";
        for(auto it = my_list.begin();it != my_list.end();++it){
            std::cout << *it << " ";
        }
        
        // Pop the last element from the list
        my_list.pop_back();
        
        std::cout << "\nAfter popping last element from the list : ";
        for(auto it = my_list.begin();it != my_list.end();++it){
            std::cout << *it << " ";
        }
        return 0;
    }

```
**[Run Code](https://rextester.com/ROT23751)**
