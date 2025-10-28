#include <iostream>
#include <string>
using namespace std;

int main(){
    string username;
    // Each question correct = 1 point
    int score =0;
    int choice;

    cout << "                Welcome to the Cactus knowledge Quiz!" << endl;
    cout << "-------------------------------------------------------------------------" << endl;
    cout << "What's your name? ";
    cin >> username;
    cout << "Hello, " << username << "! Let's see how much you know about cacti. " << endl;
    cout << " " << endl;
    
    // Question 1
    cout << "1.How do Cacti store water? " << endl;
    cout << "1 In their leaves" << endl;
    cout << "2 In their stems" << endl;
    cout << "3 In their roots" << endl;
    cout << "Enter 1, 2, or 3: " << endl;
    cin >> choice;

    if ( choice == 2) {
        cout << "Correct! Cacti store water in their stems." << endl;
        score +=1;
    } else {
        cout << "Incorrect. Cacti actually store water in their stems." << endl;
    }
    cout << " " << endl;
    
    // Question 2
    cout << "2. Where are cacti naturally found? " << endl;
    cout << "1 Rainforests" << endl;
    cout << "2 Deserts" << endl;
    cout << "3 Mountains" << endl;
    cout << "Enter 1, 2, or 3: " << endl;
    cin >> choice;

    if (choice == 2){
        cout << "Nice! Desserts are their natural habitat." << endl;
        score +=1;
    } else if (choice == 1) {
        cout << "Nope! Too much rain for cacti." << endl;
    } else { 
        cout << "Not quite! They prefer hot, dry climate." << endl;
    }

    // Question 3
    cout << "3. What adaptation helps cacti reduce water loss? " << endl;
    cout << "1 Spines" << endl;
    cout << "2 Flowers" << endl;
    cout << "3 Flat leaves" << endl;
    cout << " Enter 1, 2, or 3: " << endl;
    cin >> choice;

    if (choice == 1){
        cout << "Correct! Spines reduce evaporation and protect them." << endl;
        score +=1;
     } else {
        cout << "Incorrect. It's the spines that help prevent water loss." << endl;
     }

     // Question 4
     cout << "4. Which cactus produces edible fruit , that could be used in drinks ? " << endl;
     cout << "1 Prickly Pear" << endl;
     cout << "2 Saguaro" << endl;
     cout << "3 Barrel Cactus" << endl;
     cout << "Enter 1, 2, or 3: " << endl;
     cin >> choice;

     if (choice == 1) {
        cout << "You're right! Prickly Pear fruit is edible and delicious." << endl;
        score +=1;
    } else if (choice == 2 || choice ==3) {
        cout << "Close! But Prickly Pear is the one used in most food and drinks" << endl;
    }

    // Question 5 Switch
    cout << "5. What color is a healthy cactus? " << endl;
    cout << "1 Bright green" << endl;
    cout << "2 Pale yellow" << endl;
    cout << "3 Brown" << endl;
    cout << "Enter 1, 2, or 3: " << endl;
    cin >> choice;

    switch (choice) {
        case 1: cout << "Correct! Bright green means it's thriving." << endl;
        score +=1;
        break;
        // If break isnt included all the reposonses will print
        case 2: cout << "Pale yellow can mean too much sun or water, it's actually Bright green." << endl;
        break;
        case 3: cout << "Brown = Bad news for your cactus!It's actually Bright green." << endl;
        break;
    }

    // Quiz Results
    cout << "-------------------------------------------------------------------------" << endl;
    cout << "Quiz Complete!" << endl;
    cout << username << " ,your final score is: " << score << " out of 5." << endl;

    if (score ==5) {
        cout << "Cactus Expert - You really know your succulents!" << endl;
    } else if (score >=3) {
        cout << "Cactus Enthusiast - You're learning fast!" << endl;
    } else {
        cout << "Im sorry but you're a cactus newbie - Keep studying, you'll get there thought!" << endl;
    }
    cout << " " << endl;
    cout << " " << endl;
    cout << "Thanks for playing, " << username << "! Keep it green." << endl;
    

    

    return 0;
}
     
