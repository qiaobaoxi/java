# java
        System.out.println("您好");
        Scanner in = new Scanner(System.in);
    //  System.out.println("echo:"+in.nextLine());
        final int amont=100;
        int price;
        price=in.nextInt();
        System.out.println(amont+"-"+price+"="+(amont-price)); 
    
    
    //  TODO Auto-generated method stub
        System.out.println("您好");
        Scanner in = new Scanner(System.in);
        // System.out.println("echo:"+in.nextLine());
        int amont=0;
        int price=0;
        System.out.print("请输入面额");
        amont = in.nextInt();
        System.out.print("请输入金额");
        price=in.nextInt();
    
       Scanner in =new Scanner(System.in);
        int x;
        int y;
        System.out.println("请输入两个数");
        x = in.nextInt();
        y = in.nextInt();
        int max=0;
        if(x>y) {
        	max=x;
        }else {
        	max=y; 
        }
        System.out.println(max);
        
        int type=1;
        switch(type) {
          case 1:
	          System.out.println("nihao");
	          break;
          case 2:
	          System.out.println("nihao1");
	          break;
          case 3:
	          System.out.println("nihao3");
	          break;    
              
        }
	
	
	int x;
	double sum = 0;
        int cnt = 0;
	int[] numbers = new int[100]
        x = in.nextInt();
	while(x != -1){
	  numbers[cut] = x;
	  sum += x;
	  cnt ++;
	  x = in.nextInt();
	}
	if(cnt >0){
	  double average = sum/cnt;
	  for(int i=0;i<cnt; i++){
	    if(numbers[i]>average){
	       System.out.printIn(numbers[i])
	    }
	  }
	}
	
	public static boolean isPrime(int i){
	  boolean isPrime = true;
	  for( int k=2; k<i;k++){
	    if(i % k == 0){
	      isPrime = false;
	      break;
	    }
	    return isPrime;
	  }
	 
	}
	
	
	
	
