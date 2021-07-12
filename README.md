System.out.println("Enter the number of stone : ");  
        int numberOfStone = input.nextInt();
        char arr[]=new char [numberOfStone];
        int count=0;
        char c ='0';
        for (int i = 0; i < arr.length; i++) {
            arr[i]=input.next().charAt(0);
            if(arr[i]==c)
                count++;
            c=arr[i];
            
        }
        System.out.println(count);
