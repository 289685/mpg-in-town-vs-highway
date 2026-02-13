#include <iostream>

using namespace std;

int main() {

    double ts, mpgt, mpgh;
// this will take in information for tank size
    cout<<"enter tank size ";
    cin>>ts;
// this will take in information for how many mpg in town
    cout<<"enter mpg in town ";
    cin>>mpgt;
// this will take in information for how many mpg on highway
    cout<<"enter mpg on highway ";
    cin>>mpgh;
// this will calculate the equation
    double dit = ts*mpgt, doh = ts * mpgh;
    cout<<"you can travel " << dit <<" miles in town and "<< doh << " miles on highway";

    return 0;
}
