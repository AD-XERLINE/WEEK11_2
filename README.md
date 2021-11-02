# WEEK11_2
โปรแกรมรายสัปดาห์ที่ 11 อันที่ 2


    #include <stdio.h>

    main(){
    	int i;
    	float S;
    	float score[10];
    	float sum = 0;
	
    	for(i=0;i<10;i++){
    		printf("\nStudent Height Information [%d] = ",i);
    		scanf("%f",&score[i]);
    		sum += score[i];
    	}
    	S=sum/10.0;
    	printf("\nAVERAGE = %.2f",S);
    }
