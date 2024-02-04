#include <stdio.h>  
int main() {  
int m, n, i, j,k,Operation; 
int a[m][n], b[m][n], c[m][n];
int matrix[10^5][10^5];
printf("\nChoose the Operation: \n");
printf("1. Addition\n");
printf("2. Subtraction\n");
printf("3. Matrix Multiplication\n");
printf("4. Matrix Transpose\n");
printf("\nEnter your choice: ");
scanf(" %d", &Operation);
switch (Operation){
case 1:
printf("Enter the number of rows and columns of the matrices:");
scanf("%d%d", &m, &n);  
printf("Enter the elements of the first matrix: \n");  
for (i = 0; i < m; i++) {  
    for (j = 0; j < n; j++) {  
        scanf("%d", &a[i][j]);  
    }  
}  
printf("Enter the elements of the second matrix: \n");  
for (i = 0; i < m; i++) {  
    for (j = 0; j < n; j++) {  
        scanf("%d", &b[i][j]);  
    }  
}  
for (i = 0; i < m; i++) {  
  for (j = 0; j < n; j++) {  
     c[i][j] = a[i][j] + b[i][j];  
  }  
}  
printf("The sum of the two matrices is: \n");  
for (i = 0; i < m; i++) {  
  for (j = 0; j < n; j++) {  
     printf("%d ", c[i][j]);  
  }  
  printf("\n");  
}  
break;
case 2:
printf("Enter the number of rows and columns of the matrices:");
scanf("%d%d", &m, &n);  
printf("Enter the elements of the first matrix: \n");  
for (i = 0; i < m; i++) {  
    for (j = 0; j < n; j++) {  
        scanf("%d", &a[i][j]);  
    }  
}  
printf("Enter the elements of the second matrix: \n");  
for (i = 0; i < m; i++) {  
    for (j = 0; j < n; j++) {  
        scanf("%d", &b[i][j]);  
    }  
}  
for (i = 0; i < m; i++) {  
  for (j = 0; j < n; j++) {  
     c[i][j] = a[i][j] - b[i][j];  
  }  
}  
printf("The subtraction of the two matrices is: \n");  
for (i = 0; i < m; i++) {  
  for (j = 0; j < n; j++) {  
     printf("%d ", c[i][j]);  
  }  
  printf("\n");  
}  
break;
case 3:
printf("Enter the number of row:");    
scanf("%d",&m);    
printf("Enter the number of column:");    
scanf("%d",&n);    
printf("Enter the first matrix element:\n");    
for(i=0;i<m;i++)    
{    
for(j=0;j<n;j++)    
{    
scanf("%d",&a[i][j]);    
}    
}    
printf("Enter the second matrix element:\n");    
for(i=0;i<m;i++)    
{    
for(j=0;j<n;j++)    
{    
scanf("%d",&b[i][j]);    
}    
}    
    
printf("Multiplication of the matrix:\n");    
for(i=0;i<m;i++)    
{    
for(j=0;j<n;j++)    
{    
c[i][j]=0;    
for(k=0;k<n;k++)    
{    
c[i][j]+=a[i][k]*b[k][j];    
}    
}    
}    
for(i=0;i<m;i++)    
{    
for(j=0;j<n;j++)    
{    
printf("%d\t",c[i][j]);    
}    
printf("\n");    
}  
break;
case 4:
printf("Enter the number of rows: ");  
scanf("%d", &m);  
printf("Enter the number of columns: ");  
scanf("%d", &n);  
printf("Enter the elements of the matrix:\n");  
for(int i=0; i<m; i++){  
    for(int j=0; j<n; j++){  
        scanf("%d", &matrix[i][j]);  
    }  
}  
for(int i=0; i<m; i++){  
    for(int j=0; j<n; j++){  
        int temp = matrix[i][j];  
        matrix[i][j] = matrix[j][i];  
        matrix[j][i] = temp;  
    }  
}  
printf("The transposed matrix is:\n");  
for(int i=0; i<n; i++){  
    for(int j=0; j<m; j++){  
        printf("%d ", matrix[j][i]);  
    }  
    printf("\n");  
} 
}
return 0;  
}  
