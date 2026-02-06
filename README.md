
---
## 💻 `programs.cpp`
# 1️⃣ Read and Display Elements of an Array
```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter number of elements: ";
    cin >> n;
    int arr[n];

    cout << "Enter elements:\n";
    for(int i = 0; i < n; i++) {
        cin >> arr[i];
    }

    cout << "Array elements are: ";
    for(int i = 0; i < n; i++) {
        cout << arr[i] << " ";
    }
    cout << endl;

    return 0;
}

```
# 2️⃣ Sum of All Elements in an Array

```cpp
#include <iostream>
using namespace std;

int main() {
    int n, sum = 0;
    cout << "Enter number of elements: ";
    cin >> n;
    int arr[n];

    cout << "Enter elements:\n";
    for(int i = 0; i < n; i++) {
        cin >> arr[i];
        sum += arr[i];
    }

    cout << "Sum of all elements: " << sum << endl;

    return 0;
}

```
# 3️⃣ Copy One Array into Another

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter number of elements: ";
    cin >> n;
    int arr1[n], arr2[n];

    cout << "Enter elements of first array:\n";
    for(int i = 0; i < n; i++) {
        cin >> arr1[i];
    }

    // Copy elements
    for(int i = 0; i < n; i++) {
        arr2[i] = arr1[i];
    }

    cout << "Elements of second array: ";
    for(int i = 0; i < n; i++) {
        cout << arr2[i] << " ";
    }
    cout << endl;

    return 0;
}

```
# 4️⃣ Print Array Elements at Even Index Positions

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter number of elements: ";
    cin >> n;
    int arr[n];

    cout << "Enter elements:\n";
    for(int i = 0; i < n; i++) {
        cin >> arr[i];
    }

    cout << "Elements at even index positions: ";
    for(int i = 0; i < n; i += 2) {
        cout << arr[i] << " ";
    }
    cout << endl;

    return 0;
}

```
# 5️⃣ Read and Display a 2D Array (Matrix)

```cpp
#include <iostream>
using namespace std;

int main() {
    int rows, cols;
    cout << "Enter number of rows and columns: ";
    cin >> rows >> cols;
    int matrix[rows][cols];

    cout << "Enter matrix elements:\n";
    for(int i = 0; i < rows; i++) {
        for(int j = 0; j < cols; j++) {
            cin >> matrix[i][j];
        }
    }

    cout << "Matrix is:\n";
    for(int i = 0; i < rows; i++) {
        for(int j = 0; j < cols; j++) {
            cout << matrix[i][j] << " ";
        }
        cout << endl;
    }

    return 0;
}

```
# 6️⃣ Print All Elements of a Matrix in Row-wise Order

```cpp
#include <iostream>
using namespace std;

int main() {
    int rows, cols;
    cout << "Enter number of rows and columns: ";
    cin >> rows >> cols;
    int matrix[rows][cols];

    cout << "Enter matrix elements:\n";
    for(int i = 0; i < rows; i++) {
        for(int j = 0; j < cols; j++) {
            cin >> matrix[i][j];
        }
    }

    cout << "Matrix elements in row-wise order: ";
    for(int i = 0; i < rows; i++) {
        for(int j = 0; j < cols; j++) {
            cout << matrix[i][j] << " ";
        }
    }
    cout << endl;

    return 0;
}

```
# 7️⃣ Print All Elements of a Matrix in Column-wise Order

```cpp
#include <iostream>
using namespace std;

int main() {
    int rows, cols;
    cout << "Enter number of rows and columns: ";
    cin >> rows >> cols;
    int matrix[rows][cols];

    cout << "Enter matrix elements:\n";
    for(int i = 0; i < rows; i++) {
        for(int j = 0; j < cols; j++) {
            cin >> matrix[i][j];
        }
    }

    cout << "Matrix elements in column-wise order: ";
    for(int j = 0; j < cols; j++) {
        for(int i = 0; i < rows; i++) {
            cout << matrix[i][j] << " ";
        }
    }
    cout << endl;

    return 0;
}



