# Data-Structure-CPP
git clone https://github.com/Abdelrahman-Azzam111/Data-Structure-CPP.git
cd Sata-Structure-CPP


#include "Stack.h"

int main() {
    Stack<int> stack;

    stack.push(10);
    stack.push(20);
    stack.push(30);

    std::cout << "Top element: " << stack.top() << std::endl;

    stack.pop();
    std::cout << "Top element after pop: " << stack.top() << std::endl;

    return 0;
}

