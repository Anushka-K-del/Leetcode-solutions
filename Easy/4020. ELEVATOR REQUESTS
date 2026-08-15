class Solution {
    public int elevatorRequests(int n, int[] requests) 
    {
        int tt=0;
        int cf=0;
        for( int i=0;i<requests.length;i++)
            {
                int nf=requests[i];
                    int diff=nf-cf;
                if(diff<0)
                {
                    diff=-diff;
                }
                tt=tt+diff;
                cf=nf;
            
            }
        return tt;
        
    }
}
