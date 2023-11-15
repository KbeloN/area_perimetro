#include <stdlib.h>
#include <stdio.h>
#include <math.h>
int main()
{
	float r, a, p;
	const float pi = 3.14;
	
	printf("Digite o raio da circunferencia: ");
	scanf("%f", &r);
	a = (r * r) * pi;
	p = (r * 2) * pi;
	printf("\n O valor da area: %f", a);
	printf("\n O valor do perimetro: %f", p);
	return (0);
}
