//if e else aprender
#include <iostream>
#include <math.h>

using namespace std;
int soma (int x, int y) {
    return x + y;
}

int subtraaaa (int x, int y) {
    return x - y;
}
    
int multicaplica (int x, int y) {
    return x * y;
}

int divisa (int x, int y) {
    return x / y;

}
    
  int potenciacao (int x, int y) {
      return pow(x,  y);}

 int radiciacao (int x) {
    return sqrt(x);
  }
  void title () {
      cout<< "----~~~~~~~~~~~~~~~~~~~~~~----" << endl;
    cout<< "       Calculadora Rupestre " << endl;
    cout<<   "----~~~~~~~~~~~~~~~~~~~~~~----" << endl;
    cout<< endl;
    }
    
int main(){

    int x, y, input;
    
    title();
    cout<< "Digite um numero aqui: ";
    cin >> x;
    cout<< endl;
    cout<< "Digite o otro numero aqui: ";
    cin >>y;
    cout<< endl;

    system("clear");
    title();
    cout<< "Quer que eu calcule em que operacão? (10 reais para eu fazer)" << endl;
    cout<< "1. soma" << endl;
    cout<< "2. subtração" << endl;
    cout<< "3. multiplicação" << endl;
    cout<< "4. divisão" << endl;
    cout<< "5. potenciacão" << endl;
    cout<< "6. Radiciação" <<endl;
    cout<< endl;
    cout<< "responda utilizando numeros: ";
    cin>> input;

    switch(input) {
        case 1:
    cout<< "A soma desses numero é qual mesmo.... aé :" << soma (x,y) << endl;
       break;
       case  2:
    cout<< " subtracao de 0 - 0 é :" << subtraaaa (x,y) << endl;
    break;
    case 3:
    cout<< "Acho que a multiplicação é essa :" << multicaplica (x,y) << endl;
    break;
    case 4:
     cout<< "usei a calculadora aqui e o resulado da divisão é :" << divisa (x,y) << endl;
    break;
    case 5:
    cout<<"usei a calculadora aqui e o resulado da potencia é :" << potenciacao(x,y) << endl;
    break;
      case 6:
        cout<< "me disseram que o resultado é : " << radiciacao(x) << endl;
      break;
    default:
    cout<< "UGA buga sou burro n entendi";
    break;
    }
    return 0;
        
    }
