#include <cs50.h>
#include <stdio.h>

int get_start_size (void);

int get_end_size (void);

int main(void)
{   
    
   int a = get_start_size();
    // TODO: Prompt for start size
   int b;
   do
   {
       b= get_end_size();
   }
   while (b<=a);
  
   
    int n = 0;
    do
    {
     a = a + (a/3) - (a/4);
     n++;
    }
    while (a < b);
    // TODO: Calculate number of years until we reach threshold
    printf("Years: %i\n",n);
    // TODO: Print number of years
}

int get_start_size (void)

{
    int a;
    do
    {
        a = get_int("Start size:");
    }
    while(a<9);
    return a;

}

int get_end_size (void)

{   
    int b;
    
    {
        b = get_int("End size:");
    }
 
    return b;
}
