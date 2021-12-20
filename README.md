# Automation
public class Primenumber{

public static void main(String[]args){
int n=10;
for(int i=1; i<=n;i++){
    int num=i;
 for (int j=2;j<i;j++){
int rem=i%j;
    if (rem==0){
System.out.println(i+"This is not a prime number");

}if (i==num-1){
 System.out.println(i+"This is a prime number");
}

}

}

}


}
