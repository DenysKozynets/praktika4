Практична робота №4 Козинець Денис

    #include <stdio.h>

    int main() {
    int n;
    scanf("%d", &n);

    int count = 0;
    for (int m = 1; m < n; m++) {
        if (n % (m + 1) == m) {
            count++;
        }
    }

    printf("%d\n", count);
    return 0;
    
    }
