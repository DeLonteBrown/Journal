# Journal
Summarize the project and what problem it was solving.

-I choose the last project since its the freshest in my mind. The biggest problem I had with this project was more with time, though this project was very fun and challenging in some aspsects as I think I recoded the program roughly 4 to 5 times with only the realizing by the 3 time I did not read the directions properly to understanding as I did not originally have the the Class identified and was coding everything in the int main(). This project focused on the code reading information from a file and outputting the amount of times a list of words appeared as a histogram or count the amount of times it appears. 

What did you do particularly well?

-I think I did better in simplifying my best buisness practices as I used to be too detail in explaining code using comments on top paying more attention to attention to detail to avoid syntax errors.


Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?

-Thinking back to previous assignments, I think if I created a header file and another .cpp file to separated the code it would have made it cleaner and easier to grasp where I was making making mistake especially when trying to sort my code.

Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
-do {
        cout << "\nMenu\n";
        cout << "1. Search for an item\n";
        cout << "2. Print the frequency list\n";
        cout << "3. Print a histogram\n";
        cout << "4. Exit\n";
        cout << "Enter your choice: ";
        cin >> choice;
        switch (choice) {
        case 1:
            searchItem();
            break;
        case 2:
            printFrequencyList();
            break;
        case 3:
            printHistogram();
            break;
        case 4:
            cout << "Exiting program...\n";
            break;
        default:
            cout << "Invalid choice. Try again.\n";
        }
    } while (choice != 4);
    
Getting the do {}while code correct was a very hard challenge, I did refer to online videos since I understand better having someone explain things to me as I was not properly grasping it when looking back over the zybooks. My original code on my laptop was utilizing the if statement but using the do {} while with switch statements gave me a better transition when the code is utilized especially for user validation. 


What skills from this project will be particularly transferable to other projects or course work?

-conditional statements I will say gave me a better practice and forced me to grasped a deeper understanding that I think I can use well in future personal projects and classes. 

How did you make this program maintainable, readable, and adaptable?

-The program is easily readable and simple comments to explain certain parts of the code without being overwhelming to any reader. The word document provided also gives a brief explaination of the code and program. 
