#include<stdio.h>

main( )
{
int score;
printf( "과목의 점수를 입력하세요 : " );
scanf( "%d", &score);

if (score >=90 )
{
    printf( "수\n" );
}

else if (score >=80)
{
    printf( "우\n" );
}

else if (score >= 70)
{
    printf( "미\n" );
}

else if (score >= 60)
{
    printf( "양\n" );
}

else
{
   printf("가\n");
}
}
