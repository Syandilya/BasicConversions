/***************************************************************************************/
	//Octal to Binary
	public static int octodeci(String t){
	     
	     for(int i=0;i<t.length();i++)
	     {
	         char c=t.charAt(i);
	         if(c>'8')
	         {
	             System.out.println("InvalId Input");
	             return 0;
	         }
	     }
	     int sum=0;
	     int c=Integer.parseInt(t);
	     
	     for(int i=0;i<t.length();i++)
	        {
	            int r=c%10;
	            c=c/10;
	            sum=sum+(int)(r*Math.pow(8,i));
	        }
	        return sum;
	    }
	public static StringBuilder decitobin(int t)
	{
	    StringBuilder c=new StringBuilder();
	    while(0<t)
	    {
	        int k=t%2;
	        t=t/2;
	        c.append(k);
	    }
	    return c.reverse();
	}
