#include <iostream>
// to calculate age of dog, in human yrs for dog older than 2.
int main() {

  std::string dog_name; // Print Dog's Name
  
  std::cout << "Enter your Dog's Name: ";
  std::cin >> dog_name;

  int dog_age;
  
  std::cout << "Enter yous Dog's Age: "; // Print Dog's Age
  std::cin >> dog_age;
  
   int early_years =21, later_years, human_years;
  // 1st 2 years dog's life is equal to 21 human years
  
  later_years = (dog_age - 2) * 4;
   // later years count as 4 human years

   human_years = early_years + later_years;
   // Your age of dog in human years is calculated by above formula

std::cout << "My name is "<< dog_name << "! Ruff Ruff, I am  " << human_years << " years old in human years.BOWW Boww woww... \n "; 
return 0;
}
