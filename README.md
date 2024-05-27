
#include <iostream>
#include <cmath>

int main() {
    double number, result;

    std::cout << "Enter a number to calculate the natural logarithm: ";
std::cin >> number;

    // Checking for a negative number
    if (number <= 0) {
        std::cout << "An incorrect number has been entered. The natural logarithm is not defined for negative numbers and zero." << std::endl;
    } else {
        result = log(number);
        std::cout << "The natural logarithm of a number " << number << " is equal to: " << result << std::endl;
    }

    return 0;
}
