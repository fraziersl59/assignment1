#include <iostream>
#include <string>

int main()
{
std::cout<<"Hello, world!!!\n";
  std::string name;
  std::cout << "What is your name?\n ";
  getline (std::cin, name);
  std::cout << "What's up, " << name << "?!?!\n"; 
  std::cout<<"What's good with ya?\n";
}
