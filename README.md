# My-first-program-
My first GitHub project
#include <iostream>
#include <string>
using namespace std;

int main() {
    string login = "waheed ali";
    int password = 12345;

    // Check both login and password
    if (login == "waheed ali" && password == 12345) {
        cout << "Login successful!" << endl;
    } else {
        cout << "Invalid login or password." << endl;
    }

    return 0;
}
