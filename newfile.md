    package cn.java.test;
     
    public class demo {
    	public static void main(String[] args) {
    		
    		String s = "abc";
    		String s1 = "abc";
    		String s2 = new String("abc");
    		
    		System.out.println(s==s1);            //���Ϊtrue
    		System.out.println(s.equals(s1));     //���Ϊtrue
    		System.out.println(s==s2);            //���Ϊfalse
    		System.out.println(s.equals(s2));     //���Ϊtrue
    		
    		
    	}
    }

# ֧�֡���׼��markdow- - 

------------