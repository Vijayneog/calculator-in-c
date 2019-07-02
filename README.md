
        #include<stdio.h>
  
        int main()
        {
	  char operation;
	  int num1, num2, result = 0;
	
  	
	printf("\n ");
  	scanf("%d%c%d", &num1,&operation, &num2);
  	
  	switch(Operator)
  	{
  		case '+':
  			result = num1 + num2;
  			break;
  		case '-':
  			result = num1 - num2;
  			break;  			
  		case '*':
  			result = num1 * num2;
  			break;
  		case '/':
  			result = num1 / num2;
  			break;
		case '%':
			result = num1 % num2;
      break;
		default:
			printf("\n You have enetered an Invalid Operator ");				    			
	}
  
	printf("%d", result);
	
        return 0;
         }
