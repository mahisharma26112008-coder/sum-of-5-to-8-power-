# sum-of-5-to-8-power-

#include <iostream>
using namespace std;

int main() {
    int sum = 0;

    for (int i = 5; i <= 8; i++) {
        sum = sum + i * i;
    }

    cout << "Sum = " << sum;

    return 0;
}
