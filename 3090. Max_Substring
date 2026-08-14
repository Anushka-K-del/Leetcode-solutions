class Solution {
    public int maximumLengthSubstring(String s) 
    {
        int maxlen=0;
        for(int i=0;i<s.length();i++)
        {
           
           for(int j=i;j<s.length();j++)
           {
            char c1=s.charAt(j);
            String word=s.substring(i,j+1);
            int c=word.length()-word.replace(String.valueOf(c1),"").length();
            
            if(c>2)
            {
                break;
            }
            
            int len=word.length();
            if(len>maxlen)
            {
                maxlen=len;
            }
           }
            }
            return maxlen;
    }
}

           

            
        
        
    
