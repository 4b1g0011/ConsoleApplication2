# #include <iostream> //引入 C++ 的標準輸入輸出庫
using namespace std; //命名空間 std，簡化後面的程式碼

int main() {
    int n, sum = 0; //定義整數變數 n 和 sum，並初始化為 0
    cin >> n; //從標準輸入讀入一個整數，存入變數 n
    for (int i = 1; i <= n; i++) { //從 1 到 n 開始迭代
        if (i % 3 == 0) { //如果 i 是 3 的倍數
            sum += i; //將 i 加入總和
        }
    }
    cout << sum << endl; //輸出總和，並換行
    return 0; //回傳 0，表示程式正確結束
}
