HhF03's first blog in github

#include <iostream> // 头文件
#include <cmath>
#include <windows.h>
#define I(a) a * 2
#define AK(a, b) a + b
#define IOI(a, rp) abs(a - rp)
using namespace std;
int main(){
    int a, rp = 0;
    cin >> a;
    while (1){
    	cout << I(AK(a, IOI(a, rp++))) + 1 << endl;
	Sleep(1000);
    }
    return 0;
}
