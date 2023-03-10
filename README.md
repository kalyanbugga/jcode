# jcode
forpr

https://kalyanbugga.github.io/jcode/ I WILL TRY MY BEST

JAVA ANAGRAM CODE 

class Anagram
{
	public static void main(String[] args) 
	{
		System.out.println("listen","silent");
	}
	static boolean anagram(String s1,String s2){
		while (true)
		{
           if (s1.length()!=s2.length) return false;
		   if(s1.length==0 && s2.length==0) return true;

		   char c=s1.CharAt(0);
		   s1=s1.replace(c+" "," ");
		   s2=s2.replace(c+" "," ");


		}
	}
}


Thank you ,Will give another update
