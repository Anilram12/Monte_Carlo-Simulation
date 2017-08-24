{
 c=2;
 l=0.1;
 y=NULL;
 n=2000;
 count=0;
	
 X=rnorm(n,mean=1,sd=2);
 U=runif(n);
 P=ecdf(X);
 k=NULL;
	
 for(i in 1:n)
    {
     k[i]=((1+l)-2*l*P(X[i]))/c;
	
     if(U[i]<=k[i])
       {
	y[count]=X[i];
	count=count+1;
       }
    }
	
 print(y);
 print(count);
 hist(y, col="red",breaks=50, xlab="random nos. generated")
 print(mean(y));
 print(var(y));
}
	
