# include <iostream.h>
# include <conio.h>

 void main ()
  {
   clrscr ();
   int i,a[100],N;
   int sum=0;
   cout<<"\n Enter Number:";
   cin>>N;
   for (i=0;i<N;i++)
    {
     cout<<"\n Enter Number:";
     cin>>a[i];
    }
   for (i=0;i<N;i++)
    {
     sum=sum+a[i];
    }
     if (sum==0)
      {
       for (i=0;i<N;i++)
	{
	 cout<<"\t"<<a[i];
	}
       }
       else
	{
	 cout<<"\n It is incorrect.";
	}

    getch ();
   }
