### Hello, World!

```cpp
#include <iostream>
#include <string>

using namespace std;

int main() {
    struct Person {
        string name;    
        string birthPlace; 
        string hobby;     
        string favorites;  
    };

    Person myInfo;
    myInfo.name = "3582-490";
    myInfo.birthPlace = "Moscow";
    myInfo.hobby = "Collecting stamps";
    myInfo.favorites = "Fairuz and Beethoven";

    cout << "Name: " << myInfo.name << endl;
    cout << "Birth Place: " << myInfo.birthPlace << endl;
    cout << "Hobby: " << myInfo.hobby << endl;
    cout << "Favorites: " << myInfo.favorites << endl;

    return 0;
}
```
