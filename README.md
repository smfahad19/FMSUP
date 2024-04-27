#Using structureFunction 
	#include <iostream>
	using namespace std;

 	struct car{
 		int model;
 		float year;
 		char company;
};
	struct employe{
		char section;
		float age;
		char department;
	};
	int main(){
		struct car toyota;
		
		toyota.model = 19;
		toyota.year =2019;
		toyota.company = 'T';
		
		cout<<"The Model of car = "<<toyota.model<<endl;
		cout<<"The Year you get car = "<<toyota.year<<endl;
		cout<<"Which company is this = "<<toyota.company<<endl;
		
		
		struct employe ali;
	
		ali.section = 'A';
		ali.age = 20;
		ali.department = 'A';
		
		cout<<"Your section is "<<ali.section<<endl;
		cout<<"Your age is "<<ali.age<<endl;
		cout<<"Your department is "<<ali.department<<endl;
		
		
	return 0;
}
