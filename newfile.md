    package cn.java.test;
     
    public class demo {
    	public static void main(String[] args) {
    		
    		String s = "abc";
    		String s1 = "abc";
    		String s2 = new String("abc");
    		
    		System.out.println(s==s1);            //结果为true
    		System.out.println(s.equals(s1));     //结果为true
    		System.out.println(s==s2);            //结果为false
    		System.out.println(s.equals(s2));     //结果为true
    		
    		
    	}
    }

# 支持“标准”markdow- - 

------------