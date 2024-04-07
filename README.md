#include <iostream>

using namespace std;

class Adam {
  public:
  string name = "Adam";
  int age = 14;
  string hobbys[3] = {"Gaming, ", "Coding, ", "and Computer Science"};

  void welcome() {
      cout << "Hello, my name is " << this->name << ", and I'm " << this->age << ", and I like " << hobbys[0] << hobbys[1] << hobbys[2] << ".";
  }
};

int main() {
  Adam Adom;

  Adom.welcome();
  
  return 0;
}
