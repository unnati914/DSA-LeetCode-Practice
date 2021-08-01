DSA LEETCODE PRACTICE
print till n 


 Scanner scn = new Scanner(System.in);
        int low = scn.nextInt();
        int high = scn.nextInt();
        
        for(int n = low; n<=high;n++){
            int count =0;
            for(int div =2; div*div<=n;div++){
                if(n%div ==0){
                    count++;
                    break;
                }
            }
            if(count == 0){
                System.out.println(n);
            }
        }
    }
}
All fibonacci series till n

public static void main(String[] args) {
      
      Scanner scn = new Scanner(System.in);
      int n = scn.nextInt();
      
      int a =0;
      int b =1;
      for(int i =0; i<n;i++){
          System.out.println(a);
          int c = a+b;
          a =b;
          b =c;
      }
   }
  }
