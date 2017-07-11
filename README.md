# QnA_game
Q and A game
//Dominc Newton
//July 7, 2017

//**********************************************

#include <iostream>
using namespace std;

//**********************************************

void getAnswers(int, string, string, string, string);
void displayStory();

//**********************************************

int main()
{
  int age;
  string name,
        animal,
        soul,
        weapon;
 }
       
//**********************************************

void getAnswers(age, name, animal, soul, weapon)
{
  cout << "What are you called traveller?";
  cin >> name;
  cout << endl;
  
  cout << "And what manner of creature is this by your side?"
  cin >> animal;
  cout << endl;
  
  cout << name << ", look deep within yourself. What color is the essence of your being?"
  cin >> soul;
  cout << endl;
  
  cout << "I fear battle is eminent in these lands. Should you need to defend yourself against life threatening forces,
           which weapon do you choose?"
  cin >> weapon;
  cout << endl;
}

//************************************************

void displayStory()
{
  cout << name << ", 
}
