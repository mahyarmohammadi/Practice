#include <stdio.h>

/* Here I declared a square root function */

int sq (float);

int main ()
{
	float a , b , c;
	printf ("Please give me 3 coefficients of a 2nd order equation. \n");
	scanf ("%f" , &a);
	scanf ("%f" , &b);
	scanf ("%f" , &c);
	float r1 , r2 , d;
	d = b*b - 4*a*c; //calculating delta amount
	r1 = (-b + sq(d))/(2*a); //calculating final results
	r2 = (-b - sq(d))/(2*a);
	printf ("The answers are %f & %f \n", r1 , r2);
	return 0;
}

/* Here I define the declared function. This is Newton's method of calculating
the square roots of a desired number. For more information, you can check the link below:
https://en.wikipedia.org/wiki/Newton's_method#Square_root_of_a_number */

int sq (float s)
{
	float m , l;
	int i;
	l = 10;
	for (i = 1; i < 6 ; i++)
	{
		m = l - (((l*l)-s)/(2*l));
		l = m;
	}
	return m;
}
