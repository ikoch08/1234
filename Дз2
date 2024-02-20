#include  
 
using namespace std; 
 
struct Person { 
string name; 
int age; 
double weight; 
double height; 
}; 
 
int main() { 
int N; 
 
cout << "Enter the number of people: "; 
cin >> N; 
 
Person* people = new Person[N]; 
 
for (int i = 0; i < N; i++) { 
    cout << "Enter the name of person " << i+1 << ": "; 
    cin >> people[i].name; 
    cout << "Enter the age of person " << i+1 << ": "; 
    cin >> people[i].age; 
    cout << "Enter the weight of person " << i+1 << ": "; 
    cin >> people[i].weight; 
    cout << "Enter the height of person " << i+1 << ": "; 
    cin >> people[i].height; 
} 
 
for (int i = 0; i < N; i++) { 
    cout << "Person " << i+1 << ": " << endl; 
    cout << "Name: " << people[i].name << endl; 
    cout << "Age: " << people[i].age << endl; 
    cout << "Weight: " << people[i].weight << endl; 
    cout << "Height: " << people[i].height << endl; 
} 
 
delete people; 
 
return 0; 
}

double middle(int height, int weight){
    for (const Person& person : people) { 
        if (person.height == targetHeight) { 
            sum += person.weight; 
            count++; 
        } 
    } 
 
    if (count == 0) { 
        return 0.0; 
    } 
 
    return sum / count; 
    }
}
