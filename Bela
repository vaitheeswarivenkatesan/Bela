import java.util.*;

public class Bela{
    public static void main(String[] args){
        Scanner kb=new Scanner(System.in);
        int n=kb.nextInt();
        char s=kb.next().charAt(0);
        int sum=0;
        if(n>=1 && n<=100 &&(s=='S'||s=='H'||s=='D'||s=='C')){
            for(int i=0;i<4*n;i++){
                String u=kb.next();
                char x=u.charAt(0);
                char y=u.charAt(1);
                boolean domi=false;
                if(y==s){
                    domi=true;
                }
                switch(x){
                    case 'A':sum=sum+11;
                                break;
                    case 'K':sum=sum+4;
                                break;
                    case 'Q':sum=sum+3;
                                break;
                    case 'T':sum=sum+10;
                                break;
                    case '8':sum=sum+0;
                                break;
                    case '7':sum=sum+0;
                                break;
                    case 'J':if (domi)sum=sum+20;
                             else sum=sum+2;
                                break;
                    case '9':if(domi) sum=sum+14;
                             else sum=sum+0;
                                break;
                }
            }
        }
        System.out.println(sum);
    }
}
