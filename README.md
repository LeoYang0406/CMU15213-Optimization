# Optimization of coding

### Code Motion
  Reduce computation frequency
  - always produce same result
  - especially move code out of the loop

      Void set_row(double *a, double *b, long j, long n){
        long j;
        for (j = 0; j < n; j++){
            a[n*i + j] = b[j];
        }
        
       Void set_row(double *a, double *b, long j, long n){
        long j;
        int ni = n*i;
        for (j = 0; j < n; j++)
            a[ni + j] = b[j];  
         }
       }
  
    
    
      
### Reduction in Strength
    

