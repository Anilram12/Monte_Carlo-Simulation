{
 u=runif(100000);
 l=0.5;
	
 u1=array(100000);
 x=array(100000);
	
 for(i in 1:100000)
    {
     u1[i]=((1+l)-sqrt(((1+l)^2)-(4*l*u[i])))/(2*l);
     x[i]=qnorm(u1[i],mean=1,sd=2);
     cat(x[i],"\n")
    }
	
 print(mean(x));
 print(var(x));
 hist(x,breaks=50,col="red")
}

