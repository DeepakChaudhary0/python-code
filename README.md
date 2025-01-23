# python-code
use to find subject grade and percentage

subNum=(input("how many subjects to find grade and percentage?"))
if((subNum=="2")or(subNum=="two")or(subNum=="Two")):
    s1=input("enter first subject : ")
    s2=input("enter second subject : ")
    ns1=float(input("marks of first subject: "))
    ns2=float(input("marks of second subject : "))
    percent=[(ns1+ns2/200)*100]

    if((ns1<=100)and(ns1>=90)):
        ns1g=print("grade A in",s1)
    elif((ns1<=89)and(ns1>=80)):
        ns1g=print("grade B in",s1)   
    elif((ns1<79)and(ns1>=70)):
        ns1g=print("grade C in",s1)    
    elif((ns1<69)and(ns1>=60)):
        ns1g=print("grade D in",s1)    
    elif((ns1<59)and(ns1>=0)):
        ns1g=print("fail in",s1) 

    if((ns2<=100)and(ns2>=90)):
        ns2g=print("grade A in",s2)
    elif((ns2<=89)and(ns2>=80)):
        ns2g=print("grade B in",s2)   
    elif((ns2<79)and(ns2>=70)):
        ns2g=print("grade C in",s2)    
    elif((ns2<69)and(ns2>=60)):
        ns2g=print("grade D in",s2)    
    elif((ns2<59)and(ns2>=0)):
        ns2g=print("fail in",s2)    
        

    print("percentage of",s1,"and",s2, "is ",percent)

elif((subNum=="3")or(subNum=="three")or(subNum=="Three")):
    s1=input("enter first subject : ")
    s2=input("enter second subject : ")
    s3=input("enter third subject : ")
    ns1=float(input("marks of first subject: "))
    ns2=float(input("marks of second subject : "))
    ns3=float(input("marks of second subject : "))
    percent=[(ns1+ns2+ns3/300)*100]
    if((ns1<=100)and(ns1>=90)):
        ns1g=print("grade A in",s1)
    elif((ns1<=89)and(ns1>=80)):
        ns1g=print("grade B in",s1)   
    elif((ns1<79)and(ns1>=70)):
        ns1g=print("grade C in",s1)    
    elif((ns1<69)and(ns1>=60)):
        ns1g=print("grade D in",s1)    
    elif((ns1<59)and(ns1>=0)):
        ns1g=print("fail in",s1) 

    if((ns2<=100)and(ns2>=90)):
        ns2g=print("grade A in",s2)
    elif((ns2<=89)and(ns2>=80)):
        ns2g=print("grade B in",s2)   
    elif((ns2<79)and(ns2>=70)):
        ns2g=print("grade C in",s2)    
    elif((ns2<69)and(ns2>=60)):
        ns2g=print("grade D in",s2)    
    elif((ns2<59)and(ns2>=0)):
        ns2g=print("fail in",s2)    
        
    if((ns3<=100)and(ns3>=90)):
        ns3g=print("grade A in",s3)
    elif((ns3<=89)and(ns3>=80)):
        ns3g=print("grade B in",s3)   
    elif((ns3<79)and(ns3>=70)):
        ns3g=print("grade C in",s3)    
    elif((ns3<69)and(ns3>=60)):
        ns3g=print("grade D in",s3)    
    elif((ns3<59)and(ns3>=0)):
        ns3g=print("fail in",s3)   
   
    print("percentage of",s1,",",s2,"and",s3, "is ",percent)


elif((subNum=="4")or(subNum=="four")or(subNum=="Four")):
    s1=input("enter first subject : ")
    s2=input("enter second subject : ")
    s3=input("enter third subject : ")
    s4=input("enter fourth subject : ")

    ns1=float(input("marks of first subject: "))
    ns2=float(input("marks of second subject : "))
    ns3=float(input("marks of second subject : "))
    ns4=float(input("marks of second subject : "))
    percent=[(ns1+ns2+ns3+ns4/300)*100]
    if((ns1<=100)and(ns1>=90)):
        ns1g=print("grade A in",s1)
    elif((ns1<=89)and(ns1>=80)):
        ns1g=print("grade B in",s1)   
    elif((ns1<79)and(ns1>=70)):
        ns1g=print("grade C in",s1)    
    elif((ns1<69)and(ns1>=60)):
        ns1g=print("grade D in",s1)    
    elif((ns1<59)and(ns1>=0)):
        ns1g=print("fail in",s1) 

    if((ns2<=100)and(ns2>=90)):
        ns2g=print("grade A in",s2)
    elif((ns2<=89)and(ns2>=80)):
        ns2g=print("grade B in",s2)   
    elif((ns2<79)and(ns2>=70)):
        ns2g=print("grade C in",s2)    
    elif((ns2<69)and(ns2>=60)):
        ns2g=print("grade D in",s2)    
    elif((ns2<59)and(ns2>=0)):
        ns2g=print("fail in",s2)    
        
    if((ns3<=100)and(ns3>=90)):
        ns3g=print("grade A in",s3)
    elif((ns3<=89)and(ns3>=80)):
        ns3g=print("grade B in",s3)   
    elif((ns3<79)and(ns3>=70)):
        ns3g=print("grade C in",s3)    
    elif((ns3<69)and(ns3>=60)):
        ns3g=print("grade D in",s3)    
    elif((ns3<59)and(ns3>=0)):
        ns3g=print("fail in",s3)  

    if((ns4<=100)and(ns4>=90)):
        ns4g=print("grade A in",s4)
    elif((ns4<=89)and(ns4>=80)):
        ns4g=print("grade B in",s4)   
    elif((ns4<79)and(ns4>=70)):
        ns4g=print("grade C in",s4)    
    elif((ns4<69)and(ns4>=60)):
        ns4g=print("grade D in",s4)    
    elif((ns4<59)and(ns4>=0)):
        ns4g=print("fail in",s4)

   
    print("percentage of",s1,",",s2,",",s3,"and",s4, "is ",percent)

elif((subNum=="5")or(subNum=="five")or(subNum=="Five")):
    s1=input("enter first subject : ")
    s2=input("enter second subject : ")
    s3=input("enter third subject : ")
    s4=input("enter fourth subject : ")
    s5=input("enter fifth subject : ")

    ns1=float(input("marks of first subject: "))
    ns2=float(input("marks of second subject : "))
    ns3=float(input("marks of third subject : "))
    ns4=float(input("marks of fourth subject : "))
    ns5=float(input("marks of fifth subject : "))
    percent=((ns1+ns2+ns3+ns4+ns5/300)*100)
    if((ns1<=100)and(ns1>=90)):
        ns1g=print("grade A in",s1)
    elif((ns1<=89)and(ns1>=80)):
        ns1g=print("grade B in",s1)   
    elif((ns1<79)and(ns1>=70)):
        ns1g=print("grade C in",s1)    
    elif((ns1<69)and(ns1>=60)):
        ns1g=print("grade D in",s1)    
    elif((ns1<59)and(ns1>=0)):
        ns1g=print("fail in",s1) 

    if((ns2<=100)and(ns2>=90)):
        ns2g=print("grade A in",s2)
    elif((ns2<=89)and(ns2>=80)):
        ns2g=print("grade B in",s2)   
    elif((ns2<79)and(ns2>=70)):
        ns2g=print("grade C in",s2)    
    elif((ns2<69)and(ns2>=60)):
        ns2g=print("grade D in",s2)    
    elif((ns2<59)and(ns2>=0)):
        ns2g=print("fail in",s2)    
        
    if((ns3<=100)and(ns3>=90)):
        ns3g=print("grade A in",s3)
    elif((ns3<=89)and(ns3>=80)):
        ns3g=print("grade B in",s3)   
    elif((ns3<79)and(ns3>=70)):
        ns3g=print("grade C in",s3)    
    elif((ns3<69)and(ns3>=60)):
        ns3g=print("grade D in",s3)    
    elif((ns3<59)and(ns3>=0)):
        ns3g=print("fail in",s3)  

    if((ns4<=100)and(ns4>=90)):
        ns4g=print("grade A in",s4)
    elif((ns4<=89)and(ns4>=80)):
        ns4g=print("grade B in",s4)   
    elif((ns4<79)and(ns4>=70)):
        ns4g=print("grade C in",s4)    
    elif((ns4<69)and(ns4>=60)):
        ns4g=print("grade D in",s4)    
    elif((ns4<59)and(ns4>=0)):
        ns4g=print("fail in",s4)

    if((ns5<=100)and(ns5>=90)):
        ns5g=print("grade A in",s5)
    elif((ns5<=89)and(ns5>=80)):
        ns5g=print("grade B in",s5)   
    elif((ns5<79)and(ns5>=70)):
        ns5g=print("grade C in",s5)    
    elif((ns5<69)and(ns5>=60)):
        ns5g=print("grade D in",s5)    
    elif((ns5<59)and(ns5>=0)):
        ns5g=print("fail in",s5)    

    
    print("percentage of",s1,",",s2,",",s3,s4,"and",s5 ,"is ",percent)    


elif((subNum=="6")or(subNum=="six")or(subNum=="Six")):
    s1=input("enter first subject : ")
    s2=input("enter second subject : ")
    s3=input("enter third subject : ")
    s4=input("enter fourth subject : ")
    s5=input("enter fifth subject : ")
    s6=input("enter sixth subject : ")

    ns1=float(input("marks of first subject: "))
    ns2=float(input("marks of second subject : "))
    ns3=float(input("marks of third subject : "))
    ns4=float(input("marks of fourth subject : "))
    ns5=float(input("marks of fifth subject : "))
    ns6=float(input("marks of sixth subject : "))
    percent=((ns1+ns2+ns3+ns4+ns5+ns6/300)*100)
    if((ns1<=100)and(ns1>=90)):
        ns1g=print("grade A in",s1)
    elif((ns1<=89)and(ns1>=80)):
        ns1g=print("grade B in",s1)   
    elif((ns1<79)and(ns1>=70)):
        ns1g=print("grade C in",s1)    
    elif((ns1<69)and(ns1>=60)):
        ns1g=print("grade D in",s1)    
    elif((ns1<59)and(ns1>=0)):
        ns1g=print("fail in",s1) 

    if((ns2<=100)and(ns2>=90)):
        ns2g=print("grade A in",s2)
    elif((ns2<=89)and(ns2>=80)):
        ns2g=print("grade B in",s2)   
    elif((ns2<79)and(ns2>=70)):
        ns2g=print("grade C in",s2)    
    elif((ns2<69)and(ns2>=60)):
        ns2g=print("grade D in",s2)    
    elif((ns2<59)and(ns2>=0)):
        ns2g=print("fail in",s2)    
        
    if((ns3<=100)and(ns3>=90)):
        ns3g=print("grade A in",s3)
    elif((ns3<=89)and(ns3>=80)):
        ns3g=print("grade B in",s3)   
    elif((ns3<79)and(ns3>=70)):
        ns3g=print("grade C in",s3)    
    elif((ns3<69)and(ns3>=60)):
        ns3g=print("grade D in",s3)    
    elif((ns3<59)and(ns3>=0)):
        ns3g=print("fail in",s3)  
    else:
        print("invalid number")
 
    if((ns4<=100)and(ns4>=90)):
        ns4g=print("grade A in",s4)
    elif((ns4<=89)and(ns4>=80)):
        ns4g=print("grade B in",s4)   
    elif((ns4<79)and(ns4>=70)):
        ns4g=print("grade C in",s4)    
    elif((ns4<69)and(ns4>=60)):
        ns4g=print("grade D in",s4)    
    elif((ns4<59)and(ns4>=0)):
        ns4g=print("fail in",s4)
    else:
        print("invalid number")

    if((ns5<=100)and(ns5>=90)):
        ns5g=print("grade A in",s5)
    elif((ns5<=89)and(ns5>=80)):
        ns5g=print("grade B in",s5)   
    elif((ns5<79)and(ns5>=70)):
        ns5g=print("grade C in",s5)    
    elif((ns5<69)and(ns5>=60)):
        ns5g=print("grade D in",s5)    
    elif((ns5<59)and(ns5>=0)):
        ns5g=print("fail in",s5)
    else:
        print("invalid number")  

    if((ns6<=100)and(ns6>=90)):
        ns6g=print("grade A in",s6)
    elif((ns6<=89)and(ns6>=80)):
        ns6g=print("grade B in",s6)   
    elif((ns6<79)and(ns6>=70)):
        ns6g=print("grade C in",s6)    
    elif((ns6<69)and(ns6>=60)):
        ns6g=print("grade D in",s6)    
    elif((ns6<59)and(ns6>=0)):
        ns6g=print("fail in",s6) 
    else:
        print("invalid number") 


    
    print("percentage of",s1,",",s2,",",s3,s4,s5,"and",s6 ,"is ",percent)        
