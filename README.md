#include<stdio.h>
#include<math.h>
int main() {
    double A,B,C,X,Y,Z;
    scanf("%lf %lf %lf",&A,&B,&C);
    X = (B*B)-(4*A*C);
    if((A==0) || (X<0))
    printf("Impossivel calcular\n");
    else
    {
    Y = ((-B+sqrt(X))/(2*A));
    Z = ((-B-sqrt(X))/(2*A));
    printf("R1 = %.5lf\n",Y); 
    printf("R2 = %.5lf\n",Z);
    }
    
    return 0;
}
