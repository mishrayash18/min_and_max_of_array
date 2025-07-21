# min_and_max_of_array
// MINIMUM AND MAXIMUM OF AN ARRAY
#include <iostream>
using namespace std;

int main() {
    int max=0, min=1000;
    int array[5] = {20,40,10,80,30};
    
    for (int i=0; i<5; i++) {
        if (array[i]>max) {
            max = array[i];
        }
    }
    cout << "the max of this array is ";
    cout << max << endl;

    for (int i=0; i<5; i++) {
        if (array[i]<min) {
            min = array[i];
        }
    }
    cout << "the min of this array is ";
    cout << min;
}

