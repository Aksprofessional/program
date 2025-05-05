# to check where does coordinates lie.c

#include <stdio.h>

int main() {
    // Write C code here
    int x,y,b,p;
    printf("enterx and y=");
    scanf("(%d,%d)",&x,&y);
    if(x==0&&y==0)
    printf("origin");
    else if(y==0)
    printf("x-axis");
    else if(x==0)
    printf("y-axis");
    return 0;
}
