# 2D-ARRAY-creation
#include <iostream>
using namespace std;
int main()
{
    // int arr[3][4];
    // for(int i = 0; i<3; i++){             //i is column here
    //     for(int j = 0; j<4; j++){          // j is row here
    //         cin>>arr[i][j];
    //     }
    // }
    int arr[3][4];
    for(int i = 0; i<4; i++){                          //i is row here
        for(int j = 0; j<3; j++){                  //j is column here
            cin>>arr[j][i];
        }
    }

    for(int i = 0; i<3; i++){
        for(int j = 0; j<4; j++){
            cout<<arr[i][j] << " ";
        }
        cout<< endl;
    }
    return 0;
}
