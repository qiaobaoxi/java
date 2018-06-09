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
