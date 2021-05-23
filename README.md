# -c-star-5
I used the (for) to take a picture of the star. ver5
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
int main() {
	int i, j, n;
	scanf("%d", &n);
	for (i = 1; i <= n * 2; i++) {
		for (j = 1; j <= n; j++) {
			if (i % 2 == 0 && j % 2 == 0)
				printf("*");
			else if (i % 2 == 1 && j % 2 == 1)
				printf("*");
			else
				printf(" ");
		}
		printf("\n");
	}
	return 0;
}
