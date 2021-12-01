# sekolah-artis
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    //int t untuk tinggi badan
    int t;
    //int b untuk berat badan
    int b;
    //int u untuk umur
    int u;
    cin >> t >> b >> u;
    
    if (t>170 && b>55 && u>=15){
        cout <<"Lolos"<<endl;

}    else{
        cout <<"Tidak Lolos"<<endl;
}
    return 0;
}
