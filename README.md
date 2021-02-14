# CHAPTER-4-DATA-1A
UNIT 2
CHAPTER 4 EXERCISE DATA 1A CAROLINA TORRES ARJONA

# 4-1

    #include <stdio.h>
    #include <strings.h>
    /*PRINT YOUR NAME, SOCIAL SECURITY NUMBER,, AND DATE OF BIRTH */

    int main(void)
    {
    printf("Name:           Carolina Torres Arjona\n");
    printf("SSN:            978274980903\n");
    printf("Date of birth:  May 13th, 2000");

    return(0);
    }



# 4-2

    #include <stdio.h>

    /*PROGRAMM TO PRINT AN "E" USING "*" 
    WITH A HEIGHT OF 7 AND A WIDHT OF 5*/

    int main(void) {

      printf("\n*****\n");
      printf("*\n");
      printf("*\n");
      printf("*****\n");
      printf("*\n");
      printf("*\n");
      printf("*****\n\n");

    return 0;
  }

# 4-3

    #include <stdio.h>
    /* AREA AND PERIMETER OF A RECTANGLE WITH A 
    WIDTH OF 3 IN AND A HEIGHT OF 5 IN  */
    int W = 3;
    int H = 5;
    int A, P;

    int main(void) {

    A = W*H;
    P = (3*2)+(5*2);

      printf("THE AREA IS %d INCHES", A);
      printf("\nTHE PERIMETER IS %d INCHES", P);

    /*TO DO THE SAME BUT WITH A RETANGLE OF WIDHT 6.8, 
    AND LENGHT OF 2.3 INCHES BOTH, THE CODE HAS
    TO CHANGE INSTEAD OF "int" WE WILL
    USE "float" TO BE ABLE TO WORK WITH DECIMALS,
    AND IN THE OPERATIONS PUT A "." IN THE NUMBERS.
    ALSO INSTEAD OF "%d" TO SHOW THE RESULTS WE WILL
    USE "%f". */

      return 0;
    }

# 4-4


    #include <stdio.h>
    //PROGRAMM TO PRINT "HELLO" HEIGHT OF 7 AND WIDTH OF 5

    int main(void) {
      printf("-   -  –---- -     -     -----\n");
      printf("|   |  |     |     |     |   |\n");
      printf("|   |  |     |     |     |   |\n");
      printf("|---|  ----- |     |     |   |\n");
      printf("|   |  |     |     |     |   |\n");
      printf("|   |  |     |     |     |   |\n");
      printf("-   -  ----- ----- ----- -----\n");
      return 0;

    }

# 4-5

    #include <stdio.h>
    /* PROGRAMM QITH DELIBERATE MISTAKES */
    float ERROR1 = 3.33;
    int ERROR2  = 110;
    char ERROR3[3] = "car";

    int main(void) {
      printf("ERROR 1 %d", ERROR1);//FLOAT
      printf("ERROR 1 %f", ERROR2);//INTEGER
      printf("ERROR 3 %d", ERROR3);//CHARACTER

      return 0;
    }
  
# 4-6
    #include <stdio.h>

    //PROGRAMA PARA CALCULAR CUANTOS AÑOS 
    //TE PUEDEN QUEDAR DE VIDA

    int F, A, B, D, VIDA ;
    int main(void) {
      VIDA = 30;
    printf("\nRESPONDE LAS PREGUNTAS CON 1= si, 0=no\n\n");
    printf("¿FUMAS DIARIO?\n");
    scanf("%d",&F);
    if(F==1)
    {
      VIDA = VIDA -6;
    }
    else
    {}

    printf("¿ERES ALCOHOLICO?\n");
    scanf("%d",&A);

    if(A==1)
    {
      VIDA = VIDA - 4;
    }
    else
    {}
    printf("¿ERES BOXEADOR?\n");
    scanf("%d",&B);

    if(B==1)
    {
      VIDA = VIDA -2;
    }
    else
    {}
    printf("¿CONSUMES DROGAS?\n");
    scanf("%d",&D);
    if(D==1)
    {
      VIDA = VIDA -4;
    }
    else
    {}

    printf("\nTE QUEDAN %d AÑOS DE VIDA", VIDA);


    return 0;
    }
