include <iostream>
using namespace std;
int main(){
  //hear we are taking salary or person
int yoursalary;
  cout<<"your salary\n";
  cin>>yoursalary;
  /*now taking from hom much time person providing service*/

  int serviceyear;
  cout<<"year of service you provide\n";
  cin>>serviceyear;

  //now applying condition
if(serviceyear>5){
  auto z=((yoursalary*5)/100);
cout<<"bonus you get:"<<z<<endl;
  cout<<"total salary you get:"<<yoursalary+z<<endl;
}
  else{
    cout<<"you get only:"<<yoursalary<<endl;
  }
  return 0;

}
