
class Jala {
	public static void main(String[] args){
		int i=4;
		int j=0;
		try{
	    	 int k=i/j;
	       }
	    catch(ArithmeticException ae)
	       {
	    	   System.out.println("Number can't be divided by zero : "+ae);
	       }
	    finally
	    {
	    	System.out.println("Byeee!!!!");
	    }
	}
}
