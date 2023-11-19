#include <iostream>
using namespace std;
#define NUMERO 5
int dobrarNumero(int numero) {
    return numero * 2;
}
int main() {
    int resultadoDobro = dobrarNumero(NUMERO);
        cout << resultadoDobro << endl;
    return 0;
}
